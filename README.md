# Fake News Detector on Social Media

This is README file for fake news detector model made by team eleven. Documentation of each file is as follow.

## How To Use
1. Save train.csv and test.csv file in your google drive.
2. Download each code file and open it using colab.
3. Connect google drive in colab using “from google ~ “ snippet. Then, set path where dataset file(train.csv, test.csv) exists.
4. Run the code and check the result.

## Model Description and Notes
### fake_news_on_social_media_LR.ipynb
+ This file includes fake news detector model using logistic regression.

### fake_news_on_social_media_RF.ipynb
+ This file includes fake news detector model using random forest.

### fake_news_on_social_media_RF_comparison.ipynb
+ This file includes comparison between Random Forest, PCA+Random Forest, PCA+SVM, PCA+KNN, and SVM.
+ As runtime of SVM and KNN are high without GPU, PCA was implemented to try to reduce the run time.
