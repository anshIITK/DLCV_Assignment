
# Deep Learning for Computer Vision (CS776A): Assignment I
Submitted By: Anshul Sharma (22111009) ,Lt Cdr Vijay Singh Sisodiya (22111089)
email-anshulsh22@iitk.ac.in, vijayss22@iitk.ac.in

==================================================================

Libraries used: 

    pytorch
    torchvision 
    opencv
    numpy
    matplotlib
    pickle
    sklearn
    random 
    math
    CV2
    exists

==================================================================

Code Files are stored in : Jupyter Notebook (.ipynb) and python files (.py).

1. cifar10dataset : Store the extracted train dataset and test dataset.
				  Dataset is not loaded with this assignment if you wanted to run the complete assignment please download it from the site given below 
				  and after extraction put all the datasets in cifar10dataset folder.

2. codefiles : This folder stores all the models weights, extracted features and code files for MLP.

        -> 22111009_22111089.ipynb  :  This file stores all the codes of assignment.

	    -> train_feature_vector.pkl :  This file stores the extracted features of both original train and augmented train as a single dataset.

        -> train_labels.pkl : This file stores the labels of both original train and augmented train as a single dataset.

        -> test_feature_vector.pkl : This file stores the extracted features of both original test and augmented test as a single dataset.

        -> test_labels.pkl : This file stores the labels of both original test and augmented test as a single dataset.

	    -> feature extractor :  This file stores the code to extract features from the BBResNet18 Model.
    
Download all the above pickled files from this link https://drive.google.com/drive/folders/1ylEi3OypcLbjq8DgYorzmL5l5tc0MN-3?usp=sharing 

3. Report : Report of the Assignment.
Every Code and Jupyter Notebook is properly commented for better understanding.


=====================================================================

Procedure to run the code : 

1. Download the dataset from the site : https://www.cs.toronto.edu/~kriz/cifar.html.
2. Extract the above downloded file and save all the train_batch[1:5] and test_batch in the folder cifar10dataset->cifar-10-batches-py.
3. Run "22111009_22111089.ipynb" file to train the model and checking the results.
4. If you don't wanted to train the model from the start then skip the training part and Import all the libraries required and go to the last section and download all the pickled files from the above link and run the model from there onwards.




