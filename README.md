# CNN for breast ultrasound segmentation
Recently, the automatic segmentation of breast tumors in ultrasound (BUS) has been addressed using convolutional neural networks (CNN). Here, four CNN-based semantic segmentation models for BUS segmentation are provided: 
1. Fully Convolutional Network (FCN) with AlexNet network.
2. U-Net network.
3. SegNet using VGG16 and VGG19 networks.
4. DeepLabV3+ using ResNet18, ResNet50, MobileNet-V2, and Xception networks.

All the CNN models were fine-tuned using transfer learning on a dataset with 3061 BUS images acquired from seven ultrasound devices, except the U-Net model, which was trained from scratch. These CNN models were developed in MATLAB 2020a using the Deep Learning Toolbox (The Mathworks, Boston, Massachusetts, USA). Each CNN model is saved in a MAT-file and can be downloaded from [drive.google.com](https://drive.google.com/uc?export=download&id=1eVClxI1dywZVNLciaJzj3S6Jrcc-lNS8) (749 MB).

Just run the file demo.m to download the CNN models automatically and segment some test BUS images.

![picture alt](https://github.com/wgomezf/CNN-BUS-segment/blob/master/cnnseg.png "CAD")

Any use of our CNN models, please cite:

Wilfrido Gomez-Flores and Wagner Coelho de Albuquerque Pereira, "A Comparative Study of Pre-trained Convolutional Neural Networks for Semantic Segmentation of Breast Tumors in Ultrasound", Computers in Biology and Medicine, Volume 126, 104036, 2020. https://doi.org/10.1016/j.compbiomed.2020.104036
