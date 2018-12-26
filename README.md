# kaggleShapeClassificationWithPytorch

This classfier uses CNN's to classify input images into 4 shapes i.e. Circle, Square, Triangle and Star.
The dataset was taken from kaggle. the dataset API : kaggle datasets download -d smeschke/four-shapes


Architecture Of the Model used: A LeNet5 Model was used for Classfication Purpose
                                
                                1)6 Kernels of size (5,5) and stride 1 were applied to the input
                                2)The next layer includes a MaxPool Layer of filter size (2,2) and stride=2
                                3)The 3rd Layer consists of 16 kernels of size (5,5)
                                4)The 4th layer again consists of a maxpool layer
                                5)The 5th,6th layers are fully connected linear layers
                                6)The output layer consists of 4 nodes corresponding to the 4 possible classes
                                

FrameWork Used: PyTorch

The Code is written and run on Google Colaboratory.

Link To the LeNet5 paper: http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf

Link To The kaggle site of the dataset:https://www.kaggle.com/smeschke/four-shapes



