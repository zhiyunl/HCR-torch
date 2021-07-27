# project-01-dl-hcr
project-01-dl-hcr is the course project for EEL5840 19Fall Class at UF

Team Member:
- Wanyu Dong :girl: [:email:](mailto:wanyudong@ufl.edu)    [:octocat:wanyudong](https://github.com/wanyudong)
- Zhiyun Ling :boy: [:email:](mailto:zhiyunling@ufl.edu)   [:octocat:zhiyunl](https://github.com/zhiyunl)

## Files
#### Dataset
- train_data.pkl - This is our train dataset, which is 6400 handwritten character images, including
 [a, b, c, d, h, i, j, k]. The size of these images around 50X50, but not fixed. 
- finalLabelsTrain.npy - This is correspondent labels of train_data.plk.[1, 2, 3, 4, 5, 6, 7, 8]
#### Utils
- MyLoader.py - Functions to help loading dataset. Preprocess function included.
#### Model 1 : CNN Classifier, aiming to classify [a, b, c, d, h, i, j, k]. 
- train.py - Core file. Including the function of train_cnn. Main function is how to train 
the cnn model with train_data and train_labels, and important parameters set.
- test.py - Main function, test_cnn function and example of how to test your data.
- net_8_final.pth - Our trained cnn parameter set for both 2-class and 9-class, you can use this to test directly without training. 

## How to run
Use train.py to train, and test.py to test
- In train.py - the main function can run the training and no need for configuration.
- In test.py - the main function shows how to use test_cnn.
    Just modify pkl file names to load your test data, and get prediction on return of test_cnn.

#Have fun !