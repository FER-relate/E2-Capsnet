# E2-Capsnet
E2-Capsule Neural Networks for Facial Expression Recognition Using AU-Aware Attention

by Shan Cao, Yuqian Yao and Gaoyun An

The paper is under review.

To run the code, the file "shape_predictor_68_face_landmarks.dat" is required. You can download it at: https://pan.baidu.com/s/17BDipqCLNzwFNsty4oc6Qg (password: 369e).

The RAF-DB dataset can be downloaded at: https://pan.baidu.com/s/13JMStyLRWxpzDE9vqorpGQ (password:ly2w).


## The structure of our E2-Capsnet
E2-Capsnet takes a facial image as input and extracts rich feature maps with enhancement module1. Then the feature maps are fed to the capsule layers to be encoded. The three fully connected layers decode the feature maps. Finally, we get the results of facial expression recognition by squashing function. Our E2-Capsnet is trained end-to-end.

![image](https://github.com/ShanCao18/E2-Capsnet/blob/master/structure.jpg)

## Attention map
![image](https://github.com/ShanCao18/E2-Capsnet/blob/master/Attention.jpg)


## Experimental Results
### Ablation experiment

![image](https://github.com/ShanCao18/E2-Capsnet/blob/master/Table1.jpg)

The classification results of VGG16, Capsnet, RCCnet and the proposed method on RAF-DB are visualized.
![image](https://github.com/ShanCao18/E2-Capsnet/blob/master/Visualization.jpg)

### Comparisons with others

![image](https://github.com/ShanCao18/E2-Capsnet/blob/master/Table2.jpg)

Our E2-Capsnet can achieve more discriminative and effective representations than the other methods.
