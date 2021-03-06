# Steel Defect Detection

## Domain- Quality Inspection

## Taking Severstal Steel Defect Detection Competition to Production

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/thumb76_76.png](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/thumb76_76.png)

[Severstal: Steel Defect Detection](https://www.kaggle.com/c/severstal-steel-defect-detection)

credits- 

[UNet starter kernel (Pytorch) LB>0.88](https://www.kaggle.com/rishabhiitbhu/unet-starter-kernel-pytorch-lb-0-88/data?select=train.csv)

### Deployment Setup

- An Industry simulation setup is used to demonstrate the final application of Image Segmentation in Manufacturing Industry.
- The setup consists of a two station PLCs, It simulates machining operations and movements of components around the manufacturing plant on conveyor belts. It also simulates different inspections using RFID, Proximity sensors.
- We are using Intel realsense D435i camera to capture the image of the component at a desired location and moment.

### Inference

- The model is build in Pytorch and Trained on an Nvidia GPU
    - Model- unetmodelscript
    - Trained model file- model.pth-

        [model - Google Drive](https://drive.google.com/drive/folders/1oSMs4X-fH6TStNBZZeXti9s1CGiE_BY3?usp=sharing)

    - The code for inference script can be found in the repo
- Two types of cases are tested
    - Defective Component
    - Non-defective Component
- After capturing the image, frame is processed and the result is displayed as a segmentation mask.

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160658.jpg](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160658.jpg)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160559.jpg](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160559.jpg)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160753.jpg](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160753.jpg)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160624.jpg](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/IMG_20210226_160624.jpg)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/p0_Color.png](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/p0_Color.png)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/p1_Color.png](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/p1_Color.png)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/1.png](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/1.png)

![Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/2.png](Steel%20Defect%20Detection%20c2640c68a99045979a30526b056b2b13/2.png)