---
description: Migrate a dataset in your local workspace to an online workspace
---

# 📦 Migrate a Local Dataset

{% hint style="info" %}
The local workspace feature is being discontinued.

**Migrate the datasets in your local workspace to an online workspace before Monday the 14th of February 2022 11:59 pm CET.**

PS: Online Workspaces are Free too
{% endhint %}

To not loose any data, you need to migrate your local datasets to an online workspace. It's an easy process. Follow these instructions:

### 1. Export your local datasets

* Go to [https://labelflow.ai/local](https://labelflow.ai/local)
* Open the dataset you wish to migrate
* Click on Export in the top right
  * Select the COCO format
  * **Export the annotations only**, it will save a JSON file to your computer

![Export your local datasets in the COCO format.](<../.gitbook/assets/image (7).png>)

### 2. Create an online workspace (go to [step 3](migrate-a-local-dataset.md#import-your-local-datasets) if you already have one)

* Click on `Create workspace` by opening the workspace switcher (top left - or [click here](https://labelflow.ai/local/datasets?modal-create-workspace\&workspace-name=))![](<../.gitbook/assets/image (9).png>)
* Name your workspace (it has to be unique across the entire LabelFlow community)
* Sign-in if you are not already signed-in
* You now have an online workspace in the workspace switcher. Select it.![](<../.gitbook/assets/image (10).png>)

### 3. Import your local datasets to the online workspace

* Create a new dataset. This dataset is hosted in your online workspace.\
  Make sure you have selected your Online Workspace in the workspace switcher first (see above)
* Click on the dataset card to open the image gallery view
* Click on the **Add images** button
  * Start by uploading the images you had in your local dataset you have exported at [step 1](migrate-a-local-dataset.md#1.-export-your-local-datasets). Once done, close the Import modal to come back to the image gallery view.
  * Click on Add images a 2nd time and drop the COCO (.json) annotation file you have exported at step 1.
* That's it :tada: . Click on your images, your annotations and the classes have been imported.

**You should repeat this operation for every dataset you wish to migrate.**

## Why are we shutting down the local workspace?

Early January 2022 we have released the [online workspace](../workspaces/introduction-to-workspaces.md) feature, among other things, it allows several team members to work together to annotate a given dataset.

In the background, providing local and online workspaces means we have now two completely different ways to manage image imports, exports and many other things. We also have to do technical compromises so that a given features work both locally and online.\
In the long run, keeping the local workspace would mean less performant features for you and more resources on our side to maintain LabelFlow.

The local workspace allowed us to launch LabelFlow early September 2021 without waiting for the online storage features. It allowed us to launch early and start capturing feedbacks.

Your data remains your data. By no means we will share it with any third party. It would be shooting ourselves in the foot. We have written it black on white in our [terms and condition](https://labelflow.ai/legal/terms-and-conditions):

![You own your data. The only persons having an access to it are the members of your workspace](<../.gitbook/assets/image (8).png>)

Dropping the Local workspace will allow our product and development team to push more cool features more regularly!
