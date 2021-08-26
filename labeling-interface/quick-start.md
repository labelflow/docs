# Quick start

Let us take the case that you are making an AI model that identifies rhinos from an image for wildlife protection services. You need to train your model with high-quality labeled images so you can produce an effective tool against poaching. These are the steps you can follow to get prepare the high-quality labeled images.

### 1. Gather Image Dataset

The first step is to gather a dataset of images containing rhinos. You can save it online or store it locally on your computer. Your data stays in its original location during the entire project so that you are in control of your data.

### 2. Create a project for your data set

![](https://lh6.googleusercontent.com/hc3wdUh4WrUcTGTsx5pf9BBnIRNZ1dgCBRy0xkmKF2cAshOdEFraiFOdRV-_h_obA8S1RPzghxrMYS7lAii1yCSAuMgE-9NSGESFbrky_q_1r0vVK5JWtlPZRABd1QroFXhzpJZc)

Navigate to [LabelFlow](www.labelflow.ai) and you will be welcomed with this interface. Press “Start Labeling”. Click on “Create new project” and give your project a name. Now press “Start Labeling” and enter your project.

### **3. Import your images**

![](https://lh5.googleusercontent.com/-ta_FrnrUH15PCbE65-8v3oL1eeP3s8dT7bal7umEdDW_KZNBQcmshMXJZnruyoQCO7QcnspxcfopoMzoTgcfKxzL5HOOY-sLlLo2tP1z6ux0r9wWCjlktldM1kfgAKXg3utq7MM)

Press “Add images” and you drop all the images that you will label for this project. You can drag and drop the images onto the screen or paste the URL to your database. You can also drop the URL to your database if your images are on the cloud.

It will lead you to a gallery where you can see all your pictures.""

Select the image you would like to label first and away we go!  


### 4. Label Images

#### Bounding Box

![](https://lh3.googleusercontent.com/oJ07s47ne-dkuIy94_OQUrP3BWHGsfoG44gPtraFSSJVm14tZKJv2i5mtg09BITuJGAGeZ9zh98tMC4Dj6idT7ZZgKT0U9m5nxZJH2QwjWHP1W89IOPH79MyCG1K74lPObd_zw8O)

Select the bounding box tool and click on the edges of the Rhinos you would like to label. Two guiding lines will be available to help you select the edges. Right-click on the bounding box to specify the class of the label. Labels are colored by class for convenience.  


#### Polygon

![](https://lh3.googleusercontent.com/g9-tURADK7BmteeYc4Lw2wLble271Wq8fzq8YWrUnE4L8fANZli0wYehgAYcUNRMchnZDA3yLlTssa1GXlM4EGjGYrU6SuyJNPt6HaHuQaofREUDiMuOMn6mcrAMmCoeVIhfz0gi)

Select the small arrow on the drawing tool and choose the polygon tool. Draw a polygon around the rhino and adjust the vertices at the end by dragging them.

Navigate between your images by simply choosing the next image you would like to label or clicking the small arrows at the bottom left. You can also use the left and right arrow keys.

{% hint style="info" %}
Click on the keyboard icon on the top right to see the complete list of shortcuts
{% endhint %}



![](../.gitbook/assets/screen-shot-2021-08-19-at-1.03.26-pm.png)

Labels can overlap, intersect or encompass other labels. Zoom in on your images by using the top right button or by using the trackpad.  
Create as many label classes as you need.  


### 5. Export Labels

Once you are finished, select the export tool on the top right.

![](https://lh3.googleusercontent.com/3K_EKiUpd9e5fYxeGI078TwYKKu8QkWgj1we1kjTZLYofRfGeP-vQl7nyBdVfivbw_tL6hmFsFdc84MKDjN3s8wT2enHFHUqvZ9U1mdRQarK5qMhH9Bj9y-X_qdS4gJapFcb0zmv)

This will give you a small menu with information about the number of labels and allows you to specify the export format, including [COCO](https://cocodataset.org/#home).

Select your desired file type and it will download to your device.

Now you are ready to train your AI model! It’s that easy! 👌  


