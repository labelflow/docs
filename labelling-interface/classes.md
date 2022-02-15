# 🎨 Classes

A class is a category in which labels are classified. It helps group similar labels together, which is essential for any labeling project. A class is defined by its name and has its own color to help differentiate it from the others.

### Create New Classes

When you create a new labeling project, it comes with the default class "None". These are the simple steps you need to take to create more labels

1. Right-click on an existing label
2. Click on the search field and write the name of the new class
3. Press enter or click on the button that says "Create class \[New\_Class] "

{% embed url="https://youtu.be/UwPV3Mu2yOY" %}

{% hint style="info" %}
You can easily import classes to a new dataset from an existing dataset.

1. **In your existing dataset having the classes you wish to copy**
   1. Click on `Export`
   2. Select the COCO export format, and activate the option `Avoid image names collision`
2. **In your new dataset**
   1. Click on `Add Images`
   2. Drag and drop the COCO export file created at step 1
{% endhint %}

### Edit Classes

The classes tab in your project space shows all the information about all the classes in your project. The total number of classes is also visible to help you, as well as the number of occurrences for each class. Furthermore, this screen details the keyboard shortcuts that can be used to quickly select the appropriate class.&#x20;

You can change the name of a class by selecting the edit icon and giving your class a new name.

You can also delete a class and all labels associated with it will be classified as "None".

![](<../.gitbook/assets/Screenshot 2021-12-30 at 09.48.34.png>)

### Managing  Complex Taxonomies&#x20;

LabelFlow can accommodate complex taxonomies, allowing users to manage very specific use cases.&#x20;

The use of the `/` to separate classes and subclasses is widely used and easily comprehensible: `Class/Subclass1/Subclass2`&#x20;

An example schema could be: `Object/Material/Defect` for infrastructure inspections, or even `Object/Type/Material/Defect`.&#x20;

Using this methodology to manage complex taxonomies and use-cases allows for the classes to be easily interpreted once exported.

![](<../.gitbook/assets/Screenshot 2021-12-30 at 09.46.11.png>)
