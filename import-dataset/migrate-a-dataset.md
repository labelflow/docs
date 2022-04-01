---
description: How to migrate a dataset to another workspace
---

# 📦 Migrate a Dataset

Let's imagine you want to move a dataset from a workspace that we'll call `old-workspace`  __  to __ `new-workspace`. For now you'll need to export your dataset in the COCO format and import them back into the new workspace.

### 1. Export your  datasets

* Go to your old workspace https://labelflow.ai/old-workspace
* Open the dataset you wish to migrate
* Click on Export in the top right
  * Select the COCO format
  * In the displayed options, choose to **export the annotations only**, it will save a JSON file to your computer

![Export your local datasets in the COCO format.](<../.gitbook/assets/image (7).png>)

### 2. Create a new workspace (go to [step 3](migrate-a-dataset.md#import-your-local-datasets) if you already have one)

* Click on `Create workspace` by opening the workspace switcher (top left - or [click here](https://labelflow.ai/local/datasets?modal-create-workspace\&workspace-name=))![](<../.gitbook/assets/image (9).png>)
* Name your workspace (it has to be unique across the entire LabelFlow community)
* Sign-in if you are not already signed-in
* You now have an online workspace in the workspace switcher. Select it.![](<../.gitbook/assets/image (10) (1).png>)

### 3. Import your dataset to the `new-workspace`

* Create a new dataset. This dataset is hosted in your `new-workspace`.\
  Make sure you have selected your `new-workspace` in the workspace switcher (see above)
* Click on the dataset card to open the image gallery view
* Click on the **Add images** button
  * Start by uploading the images you had in your `old-workspace` dataset you have exported at [step 1](migrate-a-dataset.md#1.-export-your-local-datasets). Once done, close the import modal to come back to the image gallery view.
  * Click on Add images a 2nd time and drop the COCO (.json) annotation file you have exported at step 1.
* That's it :tada: . Click on your images, your annotations and the classes have been imported.

**You should repeat this operation for every dataset you wish to migrate.**
