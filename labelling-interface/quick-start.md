# 🤸 Quick Start

Let us take the case that you are making an AI model that identifies rhinos from an image for wildlife protection services. You need to train your model with high-quality labeled images so you can produce an effective tool against poaching. These are the steps you can follow to get prepare the high-quality labeled images.

### 1. Gather Image Dataset

The first step is to gather a dataset of images containing rhinos.

{% embed url="https://youtu.be/zqlL2XRtNLo" %}

### 2. Create a dataset

![](<../.gitbook/assets/Screenshot 2021-11-26 at 16.35.33.jpg>)

Navigate to [LabelFlow](https://www.labelflow.ai) and you will be welcomed with this interface. Press “Start Labeling”. Click on  “Create new dataset” and give your dataset a name. Now press “Start Labeling” and enter your dataset.

### **3. Import your images**

![](<../.gitbook/assets/arrow\_add\_images (1).png>)

Press “Add images” and you drop all the images that you will label for this project. You can drag and drop the images onto the screen or paste the URL to your database. You can also drop the URL to your database if your images are on the cloud.

It will lead you to a gallery where you can see all your pictures.

Select the image you would like to label first and away we go!\


### 4. Label Images

#### Bounding Box

![](<../.gitbook/assets/Screenshot 2021-11-26 at 16.41.50.jpg>)

Select the bounding box tool and click on the edges of the Rhinos you would like to label. Two guiding lines will be available to help you select the edges. Right-click on the bounding box to specify the class of the label. Labels are colored by class for convenience.\


#### Polygon

![](../.gitbook/assets/polygon\_tool.png)

Select the small arrow on the drawing tool and choose the polygon tool. Draw a polygon around the rhino and adjust the vertices at the end by dragging them.

Navigate between your images by simply choosing the next image you would like to label or clicking the small arrows at the bottom left. You can also use the left and right arrow keys.

{% hint style="info" %}
Click on the keyboard icon on the top right to see the complete list of shortcuts
{% endhint %}



![](../.gitbook/assets/screen-shot-2021-08-19-at-1.03.26-pm.png)

Labels can overlap, intersect or encompass other labels. Zoom in on your images by using the top right button or by using the trackpad. Create as many label classes as you need.\


### 5. Export Labels

![](<../.gitbook/assets/Screenshot 2021-11-26 at 16.45.51.jpg>)

Once you've finished, select the export tool on the top right.

A small pop-up will appear with information about the number of labels and will prompt you to specify the export format, such as [COCO](https://cocodataset.org/#home).

Select your desired file type and it will download to your device.

Now you are ready to train your AI model! It’s that easy! 👌\
