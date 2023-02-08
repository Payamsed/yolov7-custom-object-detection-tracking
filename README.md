# yolov7-custom-object-detection
1.First open the ipynb file
2.Upload the train,val,test videos to the drive
3.Run the blocks of codes. In each block there is enough explonation for the steps.
4. At first there is a code which will train and gives the best weight in the 'yolov7'-->'runs'-->'train'-->'weights'-->'best.pt' file can be used for training.
5. using the 'detect.py' with the 'best.pt' weight the model detects the objects and counts and saves the results in 'yolov7'-->'runs'-->'detect'.
6. The results for one of my traing weight is in this folder.
7. The saved weight file is named as 'best.pt' you can use the 'detect.py' code and see the results.
8. The 'hyp.scratch.custom.yaml' file shows the configuration of training model. The following are the settings in which the 62 percent accuracy was achieved:

