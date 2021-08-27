# Direct HTTPS access

While the GraphQL playground is a good way to learn, develop and interact with our Graph API, direct access to the API using HTTPS requests is done in production. 

As an example, here we will consider how to perform the following graphQL query with various tools. Here is the GraphQL query:

```graphql
query myQueryExample($numberOfImages:Int) {
  images(first:$numberOfImages){
    id
    name
  }
}
```

This query needs some variables to be executed. Here are the variables:

```python
{"numberOfImages":10}
```

This query can be executed in the playground like this:

![](../.gitbook/assets/image%20%283%29.png)

## HTTP

```http
POST  HTTP/1.1
Host: https://labelflow.ai/graphiql
Content-Type: application/json 
User-Agent: PostmanRuntime/7.15.2
Accept: */*
Cache-Control: no-cache
Host: https://labelflow.ai/graphiql
Accept-Encoding: gzip, deflate
Content-Length: 214
Connection: keep-alive
cache-control: no-cache

{
	"operationName":"myQueryExample",
	"variables":{"numberOfImages":10},
	"query":"query myQueryExample($numberOfImages:Int) {\n  images(first:$numberOfImages){\n    id\n    name\n  }\n}","variables":{"numberOfImages":2},"operationName":"myQueryExample"
}

```

## Node JS

```javascript
var request = require("request");

var options = { method: 'POST',
  url: 'https://labelflow.ai/graphiql',
  headers: 
   { 'cache-control': 'no-cache',
     Connection: 'keep-alive',
     'Content-Length': '214',
     'Accept-Encoding': 'gzip, deflate',
     Host: 'awsprismagraph.sterblue.com',
     'Cache-Control': 'no-cache',
     Accept: '*/*',
     'User-Agent': 'PostmanRuntime/7.15.2',
     'Content-Type': 'application/json' },
  body: 
   { operationName: 'myQueryExample',
     variables: { numberOfImages: 10 },
     query: 'query myQueryExample($numberOfImages:Int) {\n  images(first:$numberOfImages){\n    id\n    name\n  }\n}','variables':{'numberOfImages':2},'operationName':'myQueryExample' },
  json: true };

request(options, function (error, response, body) {
  if (error) throw new Error(error);

  console.log(body);
});

```

## Python using requests

```python
import requests

url = "https://labelflow.ai/graphiql"

payload = "{\"query\":\"query myQueryExample($numberOfImages:Int) {\n  images(first:$numberOfImages){\n    id\n    name\n  }\n}\",\"variables\":{\"numberOfImages\":2},\"operationName\":\"myQueryExample\"}"
headers = {
    'Content-Type': "application/json",
    'User-Agent': "PostmanRuntime/7.15.2",
    'Accept': "*/*",
    'Cache-Control': "no-cache",
    'Host': "labelflow.ai/graphiql",
    'Accept-Encoding': "gzip, deflate",
    'Content-Length': "214",
    'Connection': "keep-alive",
    'cache-control': "no-cache"
    }

response = requests.request("POST", url, data=payload, headers=headers)

print(response.text)

```

