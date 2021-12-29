# Auto polygons

The Auto polygon tool allows you to boost your labeling productivity.

You create a bounding box around the object you wish to label and an AI automatically transforms this bounding box into a precise polygon around your object.

![Auto Polygon. The fastest way to create a polygon around your object.](../../.gitbook/assets/output.gif)

## Refinements

### Move or add Auto Polygon keypoints

You can refine the automatically generated polygons by simply moving the target keypoint ![](<../../.gitbook/assets/Type=target, Size=16px.png>) and/or adding inside keypoints ![](<../../.gitbook/assets/Type=inside, Size=16px.png>) and outside keypoints ![](<../../.gitbook/assets/Type=outside, Size=16px.png>).

This is as simple as moving the target keypoint ![](<../../.gitbook/assets/Type=target, Size=16px.png>) and/or doing a click inside or outside the created polygon.

* ![](<../../.gitbook/assets/Type=target, Size=16px.png>) Target keypoint. **It must always be on the object you wish to label**. Else move it on the object.
* ![](<../../.gitbook/assets/Type=outside, Size=16px.png>) Outside keypoint. A click inside the polygon will add an outside keypoint and exclude this area from the polygon label.
* ![](<../../.gitbook/assets/Type=inside, Size=16px.png>) Inside keypoint. A click outside the polygon will add an inside keypoint and include this area to the polygon label.

{% hint style="info" %}
**Always start** by moving the target keypoint ![](<../../.gitbook/assets/Type=target, Size=16px.png>) to another position on the object if the generated polygon is not good enough.\
\
**Only after start** adding inside and outside keypoints.
{% endhint %}

{% embed url="https://youtu.be/uxS4eW2p5Cw" %}
Easily adjust an Auto Polygon geometry by adding inside or outside keypoints
{% endembed %}

### Manually adjust the polygon's geometry

* Click on ![](../../.gitbook/assets/Button.png) to activate the selection mode (or press `v` for the shortcut)
* Click on the polygon you want to edit
* Select the polygon edition mode ![](<../../.gitbook/assets/Toggle Button Edit.png>)(next to the class selection menu in the top left). You can press  `e` to switch between both edition mode.
* You can now drag any points on the contour to adjust the polygon geometry

This edition mode is also illustrated in the above video.
