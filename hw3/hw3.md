# Homework 3

## Solution 1

https://colab.research.google.com/drive/1wTEOFzXmWQRdC_bgs19u-hIW3x_evvaE



Check out the GitHub repo: https://github.com/UgurUysal86/MLS4MIL/tree/master/Image%20Classification (Links to an external site.)

My former student Ugur Uysal created a synthetic dataset of military objects and fine-tuned a convnet to classify these objects.  This was one his projects for an independent study.

 

For this homework, you have to work with this synthetic dataset. Before you can train on colab, you have to carry out the steps below:

1. Download the zip file https://drive.google.com/file/d/1r-AZeKXd_SvSXwOcQuqX_w9q0F0nT-uW/view?usp=sharing (Links to an external site.) to your local computer and unzip it.

2. Look at the images of the different military objects to better understand the dataset.

3. Remove the civilian car folder.

4. Zip the folder (without civilian car) and upload it to your Google drive.

5. Start a new Colab notebook and mount your Google drive. Read the section "Mount Google drive locally" in https://colab.research.google.com/notebooks/io.ipynb (Links to an external site.)

6. Copy the dataset file to the Colab machine (you want to make sure that the data is locally available; you don't want to have to fetch the images over the network as you train)

7. Now you can access the dataset file.

 

Note that if you work for a company you may have to train machine learning models using instances in the cloud so you have to figure out how to get the dataset to the instance. The above steps mimic a little bit this process of getting data onto a remote instance.

 

Fine-tune a deep neural network to recognize the different military objects.

 

As the absolute minimum, you have to analyze Ugur's code and modify it so that the code doesn't expect the class "civilian cars".  

 

Try to get the best possible results, try to experiment with different pretrained convnets. It's your chance to put everything to use to solve a non-trivial computer vision problem.

Different pretrained convnets: https://keras.io/applications/ (Links to an external site.)

Try to see what happens as you crank up the batch size (when you got the powerful GPU).