# Credit Risk Classification
## Summary
In this challenge, I will use various techniques to train and evaluate a model based on loan risk. I will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Logistical Regression Model
#### Balanced Accuracy Score: 0.9520479254722232
![Screenshot 2023-05-16 at 11 01 44 AM](https://github.com/treysl/credit-risk-classification/assets/96922295/6b0733c1-6065-40b4-84aa-44293067312d)

According to the model's predictions, it can accurately identify loans with a label of 0 (considered healthy) with a 99% accuracy rate, while loans labeled as 1 (high-risk) are identified with a 91% accuracy rate. The model demonstrates stronger performance in predicting the 0 label than the 1 label.


## Random Oversampling Model
#### Balanced Accuracy Score: 0.9936781215845847
![Screenshot 2023-05-16 at 11 02 02 AM](https://github.com/treysl/credit-risk-classification/assets/96922295/e9e4ee12-1d3d-4b79-85ba-0473091812b4)

This model achieved 100% precision in predicting a healthy, low-risk loan, indicating that all predicted low-risk loans were actually low-risk. However, for high-risk loans, the precision was lower at 84%, indicating that some predicted high-risk loans were actually low-risk. 

Despite the varying precision for low and high-risk loans, the model achieved a balanced accuracy of 100%, which suggests that the overall performance of the model was excellent in correctly identifying both low and high-risk loans.
