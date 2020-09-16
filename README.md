# CNN-BUS-segment
Recently, the automatic segmentation of breast tumors in ultrasound (BUS) has been addressed using convolutional neural networks (CNN). Here, four public CNN-based semantic segmentation models for BUS segmentation are provided: 
1. Fully Convolutional Network (FCN) with AlexNet network.
2. U-Net network
3. SegNet using VGG16 and VGG19 networks.
4. DeepLabV3+ using ResNet18, ResNet50, MobileNet-V2, and Xception networks.

All the CNN models were fine-tuned using transfer learning on a dataset with 3061 BUS images acquired from seven ultrasound devices, excepting the U-Net model that was trained from scratch.
