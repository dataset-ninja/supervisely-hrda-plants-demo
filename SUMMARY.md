**Supervisely HRDA Plants Demo** is a dataset for instance segmentation, semantic segmentation, and semi supervised learning tasks. Possible applications of the dataset could be in the agricultural and robotics industries. The dataset presented here is not the original one. Learn more on the dataset's homepage.

The dataset consists of 2284 images with 1482 labeled objects belonging to 2 different classes including *sugar beet* and *weed*.

Images in the Supervisely HRDA Plants Demo dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. There are 2000 (88% of the total) unlabeled images (i.e. without annotations). There are 3 splits in the dataset: *unlabeled* (2000 images), *validation* (222 images), and *labeled* (62 images). The dataset was released in 2023 by the <span style="font-weight: 600; color: grey; border-bottom: 1px dashed #d3d3d3;">Supervisely</span>.

Here is the visualized example grid with animated annotations:

[animated grid](https://github.com/dataset-ninja/supervisely-hrda-plants-demo/raw/main/visualizations/horizontal_grid.webm)
