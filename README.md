# Face-Iris
Multi-model biometric by fusion of face and iris

## papers for this topic  
includes face only, iris only and multi-modal system   
https://drive.google.com/open?id=1u3IqMlJp7VCJxEVFvG15zTY4BX8SH2lU

## traditional Hough transform iris segmentation(circle detection only)
![](https://github.com/stephenkung/Face-Iris/blob/master/pics/0.PNG)

## U-net iris segmentation result
The pretrained U-net for iris segmentation: https://github.com/jus390/U-net-Iris-segmentation     
This network is form paper: "End-to-End Iris Segmentation Using U-Net"     
![](https://github.com/stephenkung/Face-Iris/blob/master/pics/1.PNG)

## Haar cascade method to detect face and eye area result
![](https://github.com/stephenkung/Face-Iris/blob/master/pics/2.PNG)

## Face verfication code     
This code is a little large, I can't upload it to Github, so I put it in google cloud.    
it contains 2 versions of face verificaiton:      
1)VGG16+ Siamese network + contrastive loss, idea comes from DeepFace        
2)Inception + triplet loss, idea comes form FaceNet        
https://drive.google.com/drive/folders/16RES3HUE7N_AEEYRk862VyrzM5oDWjom?usp=sharing
