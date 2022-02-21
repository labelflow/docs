# 🧾 CSV

The CSV export format lists the labels contained in your dataset. Note that the polygon and classification labels are exported as bounding boxes.

You'll find several columns for every label:

* `imageId`: a unique identifier for every image
* `imageName`: speaks for itself...!
* `width`: width of the image in pixel
* `height`: height of the image in pixel
* `class`: name of the label class
* `xmin`, `ymin`, `xmax`, `ymax`: bounding box coordinates in pixel of its top left corner and bottom right corner
* `imageURL`: link to the image stored in LabelFlow

![Definition of xmin, ymin, xmax, ymax locating a bounding box in an image](<../.gitbook/assets/Untitled 3.jpg>)

{% hint style="info" %}
For security reasons, the image URL **is valid for 7 days only**. You can generate a new CSV export at any time to reset the validity dates of the URLs.
{% endhint %}
