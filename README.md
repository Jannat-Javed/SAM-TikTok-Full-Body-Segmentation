## Full-Body TikTok Dancing Segmentation using Segment Anything Model (SAM)
<img src="https://github.com/your-username/your-repo-name/blob/main/pics/dancing.gif" alt="Dancing GIF" width="600"/>
In this project, we explore the use of the Segment Anything Model (SAM) by Facebook Research to perform instance segmentation on the Full-Body TikTok Dancing Dataset. The goal is to accurately segment dancing individuals in videos and images, enabling applications such as motion analysis, video editing, and augmented reality.

<p align="center">
  <div style="display: flex; justify-content: center;">
    <img src="https://github.com/Jannat-Javed/SAM-TikTok-Body-Segmentation/blob/main/masks/67_00180.png" alt="Image 1" width="250" style="margin-right: 10px;"/>
    <img src="https://github.com/Jannat-Javed/SAM-TikTok-Body-Segmentation/blob/main/masks/734_00360.png" alt="Image 2" width="250" style="margin-right: 10px;"/>
    <img src="https://github.com/Jannat-Javed/SAM-TikTok-Body-Segmentation/blob/main/masks/741_00120.png" alt="Image 3" width="250"/>
  </div>
</p>

## Features

**Instance Segmentation: Accurately segment full-body dancing individuals in images and videos.**

**Real-Time Processing: Optimized for real-time performance with GPU support.**

**Customizable Masks: Generate binary masks for each segmented individual.**

**Visualization Tools: Display original images alongside segmented results for comparison.**


## Dataset

This project uses the Full-Body TikTok Dancing Dataset from Kaggle. The dataset contains frames taken from videos of individuals dancing, along with corresponding COCO-format annotations for segmentation. I used the [TikTok Dances](https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-tiktok-dancing-dataset) dataset

**Dataset**

Images: Located in the test directory.

Annotations: Provided in the _annotations.coco.json file.


**Requirements**

Before running the project, ensure you have the following installed:

- Python 3.7 or higher

- OpenCV

- PyTorch

- Segment Anything Model (SAM)

- Roboflow API (for dataset download)

- Supervision

- Matplotlib (for visualization)
