## Hand Gesture Recognition
It's a machine learning model that classifies the hand gesture into one of six digits (from 0 to 5)
<br>
<br>

## How to run project
1. Download the dataset from [here](https://drive.google.com/drive/folders/1o9wzwaJVfrbpCFJ0rIyed1QvARh0JAtn)
2. Run features_training.ipynb file that extracts features, train the model, and creates the model file
3. Run the test_images.ipynb file that tests the model (Note: Change the folder name that contains the test images)
4. After running test_images, it will create two file results.txt and time.txt which are the prediction result and the time that take to extract the feature and predicted label
5. Compare the actual labels and the predicted labels using matching.ipynb file and get the accuracy of the model