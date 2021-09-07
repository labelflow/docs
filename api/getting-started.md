# Getting started

## GraphQL Playground

LabelFlow GraphQL playground is the best way to get started with the API. Just connect to [https://labelflow.ai/graphiql](https://labelflow.ai/graphiql) using any modern web browser, and get started. The interface should look like something like this.

![](../.gitbook/assets/image%20%285%29.png)

As the images on LabelFlow are stored locally only, there is no authentication needed. All queries and mutations will be done on a database stored locally in your browser.

## **Perform our first GraphQL Query**

Let’s write a graphQL query which asks for the ids**,** names, and dataset id of the first 10 images you have access to**:**

![](../.gitbook/assets/image%20%284%29.png)

```graphql
query images {
  images(first:10){
    id
    datasetId
    name
  }
}
```

You can now run the query by pressing the ▶️“Run Query Button” in the top left of the screen. You should see the response appear on the right side of the screen.

## **Access the interactive documentation**

Our Graph API is self-documented. **You can access all the documentation in the GraphQL playground.** There are several ways to benefit from the documentation:

* Automatic autocompletion of your queries
* Manual autocompletion of your queries, triggered by pressing CTRL-SPACE when writing a query in the query area
* Schema documentation, using the “Schema” Button on the right side of the screen.

Here is a screenshot showcasing both Autocompletion \(on the left side, in the query area\), and the schema documentation \(on the right side, in the sidebar\). Our API is based on the principle of OpenCrud \([https://github.com/opencrud/opencrud](https://github.com/opencrud/opencrud)\).

![](../.gitbook/assets/image%20%286%29.png)

