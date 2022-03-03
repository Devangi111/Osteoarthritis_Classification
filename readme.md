Intention behind this notebook is to explore use-case of using CNN classification in real-world example.

Here I have used classification to classify stages of Osteoarthiritis.

There is dataset available having 5 stages of Osteoarthiritis and corresponding images segregated by Certified Medical ecperts.
You can download the dataset through this below link.

"link to the dataset"

Once you have downloaded it you can extract and use train_test_split notebook to split it.

Now the dataset will be in following manner
Dataset
    Train
        0Normal
        1Doubtful
        2Mild
        3Moderate
        4Severe
    Test
        0Normal
        1Doubtful
        2Mild
        3Moderate
        4Severe

As you can clearly observe, it is the case of multi class classification having 5 classes.

Let's train it using simple convolutional neural network as I have declared in the test_nb notebook.

Please do note one thing that kindly go through the packages those are required to successfully run the notebook.

Once you train it for 10 epochs you will get to know the accuracy is quite promising.

Let's try to train it with transfer learning to get more accuracy.