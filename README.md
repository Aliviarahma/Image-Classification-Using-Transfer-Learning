# Image-Classification-Using-Transfer-Learning

## Eye Disease Detection using Transfer Learning (DenseNet-121, EfficientNetB3, VGG-16, Resnet-152)
Eye Disease Detection using Transfer Learning (DenseNet-121)
This notebook contains Transfer Learning modeling which is used to detect Eye Disease based on retinal fundus image data. The dataset used is image data of eye disease consisting of cataract, diabetic retinopathy, glaucoma and normal classes and the method for image clssification is using model from transfer learning there are DenseNet-121, EfficientNetB3, VGG-16, Resnet-152. In this study the accuracy obtained with the DenseNet-121 model obtained an accuracy of 96.20%. In the process to facilitate training monitoring, custom callbacks are used. This custom callback is useful for controlling how many epochs to use. When carrying out the training process there is an H (halt) function to stop the ongoing training then rearrange the epoch and F to continue training.
