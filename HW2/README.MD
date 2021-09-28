
# HW2 for CSCI_4120

### Description:
This Jupyter Notebook is used to try and predict the best K for K-Means. KElbowVisualizer from Yellowbrick is used to help determine the best K and Confusion Matrix is drawn to visualize and evaluate the accuracy.

### Team member: 
Henry Santacruz (Email: santacruze21@students.ecu.edu)

### Quick Start:
Jupyter Notebook is required to view this file. 
You also need to install the following into Jupyter Notebook:
- pandas
- numpy
- matplotlib
- seaborn
- yellowbrick
- sklearn
- scipy

### Which K works the best:
![image](https://user-images.githubusercontent.com/25361469/135007925-bffa1095-ea5c-44a8-9383-13c0a3db6324.png)
* We can see 4 clusters from the initial plot so we can predict that 4 will be our best k.
  
### KElbowVisualizer:
![image](https://user-images.githubusercontent.com/25361469/135007978-cf847810-bb63-4956-9632-fe63a66de043.png)
* Elbow confirms that 4 would be the best k.

### The Best K Accuracy:
![image](https://user-images.githubusercontent.com/25361469/135009201-c4cdf7b1-ff9c-4335-b11c-1ca4c9fcc05e.png)
* We can see that with 4 as our k we get 1.0 accuracy result which mean 100% accuracy.


### Confusion Matrix:
![image](https://user-images.githubusercontent.com/25361469/135008010-dccd0898-5af9-4bea-934d-d7c3a79e8a5d.png)
* Confusion matrix shows great results.
