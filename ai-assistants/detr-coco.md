# 🥥 DETR - COCO

### Presentation

The DEtection TRansformer (DETR) model was trained by Facebook on the [COCO 2017 dataset](https://cocodataset.org/#explore) (118,000 images) and is hosted by Hugging Face. You can find its complete description card [here](https://huggingface.co/facebook/detr-resnet-50).

DETR - COCO AI Assistant outputs by default bounding boxes around the detected objects. If the detected object class does not exist in the dataset, the AI assistant will create it.

### Generate Polygons instead of Bounding Boxes

It is possible to transform a bounding box into a polygon by selecting the Post-process option. Note that the inference time will be slightly longer by selecting this option.

![Post-processing option to generate polygons instead of bounding boxes](<../.gitbook/assets/image (12).png>)

### Sample Image

![Automatic cat and dog detection by DETR - COCO AI Assistant](<../.gitbook/assets/image (11).png>)

### Classes

DETR - COCO AI Assistant is able to detect 90 different classes of objects (some better than others we must say...!)

```
person
bicycle
car
motorcycle
airplane
bus
train
truck
boat
trafficlight
firehydrant
streetsign
stopsign
parkingmeter
bench
bird
cat
dog
horse
sheep
cow
elephant
bear
zebra
giraffe
hat
backpack
umbrella
shoe
eyeglasses
handbag
tie
suitcase
frisbee
skis
snowboard
sportsball
kite
baseballbat
baseballglove
skateboard
surfboard
tennisracket
bottle
plate
wineglass
cup
fork
knife
spoon
bowl
banana
apple
sandwich
orange
broccoli
carrot
hotdog
pizza
donut
cake
chair
couch
pottedplant
bed
mirror
diningtable
window
desk
toilet
door
tv
laptop
mouse
remote
keyboard
cellphone
microwave
oven
toaster
sink
refrigerator
blender
book
clock
vase
scissors
teddybear
hairdrier
toothbrush
```
