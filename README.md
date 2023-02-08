# yolov7-custom-object-detection
First open the ipynb file.

Upload the train,val,test videos to the drive.

Run the blocks of codes. In each block there is enough explonation for the steps.

At first there is a code which will train and gives the best weight in the 'yolov7'-->'runs'-->'train'-->'weights'-->'best.pt' file can be used for training.

using the 'detect.py' with the 'best.pt' weight the model detects the objects and counts and saves the results in 'yolov7'-->'runs'-->'detect'.

The results for one of my traing weight is in this folder.

The saved weight file is named as 'best.pt' you can use the 'detect.py' code and see the results.

The 'hyp.scratch.custom.yaml' file shows the configuration of training model. The following are the settings in which the 62 percent accuracy was achieved:

