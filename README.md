Parameters :

Requirement already satisfied: torchsummary in /usr/local/lib/python3.6/dist-packages (1.5.1)
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 32, 14, 14]             320
              ReLU-2           [-1, 32, 14, 14]               0
       BatchNorm2d-3           [-1, 32, 14, 14]              64
         MaxPool2d-4             [-1, 32, 7, 7]               0
           Dropout-5             [-1, 32, 7, 7]               0
            Conv2d-6             [-1, 64, 5, 5]          18,496
================================================================
Total params: 18,880
Trainable params: 18,880
Non-trainable params: 0



