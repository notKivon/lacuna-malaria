# Malaria Detection Using Computer Vision
My first computer vision project, this was made as a submission to a contest hosted on Zindi.  
  
The notebooks and files were provided by the organizers of the project, and the training was on Colab

The training process involved taking blood samples of Malaria, mapping bounding boxes onto them and then analyzing the images inside the boxes. A few sample images are shown below

![Malaria blood sample with bounding boxes](assets/sample_prediction_1.png)
![Malaria blood sample with bounding boxes](assets/sample_prediction_2.png)
![Malaria blood sample with bounding boxes](assets/sample_prediction_3.png)

After the training, I checked the accuracy of the data using the given test.csv file, resulting in the following scores
![Class/Images/Instances/P/R/mAP50/mAP50-95  all/515/5488/0.789/0.816/0.838/0.437 Trophozoite/507/3896/0.686/0.662/0.695/0.281 WBC/392/1592/0.891/0.969/0.982/0.593](assets/training_results.png)

Finally, the results were submitted successfully with a public score of 0.42 and private score of 0.39

This score could've been increased by training with more epochs and tuning the data more, although such actions may result in higher usage fees

Overall, this was a fun experience and an interesting start in computer vision. I look forward to doing other similar projects in the future
