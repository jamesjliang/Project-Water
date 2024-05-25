# Project-Water

<Preface: To review the html output, please download all relevant supporting files>

Water is a scarce commodity in many parts of the world. Accurately predicting its availability while reducing the need to routinely check would enable lower costs in monitoring that might be better allocated to creating new water resources. **Therefore, the aim of this project is to create the best machine learning model for predicting the availability of water.**

This challenge is motivated by an analysis by Julia Silge “Predict availability in #TidyTuesday water sources with random forest models”. The data is downloaded from https://www.waterpointdata.org and represents a subset from a region in Africa. The data has been cleaned, with missing values (small number) imputed, and only reliable variables included.

As part of the kaggle competition, the files provided are:

- water-train.csv: the training set of data
- water-test.csv: the test set, with no labels, that you need to predict the response variable status_id.
- sample-submissions.csv: the format of the data that you need to use to make a submission to kaggle.

Note that for the purposes of this competition, the spatial coordinates have been manipulated, as to disguise the actual locations of water points from competitors.

## Results of Kaggle Competition
![image](https://github.com/jamesjliang/Project-Water/assets/161998923/d1bf7390-c9c9-4003-9e54-cc58972cae04)

The results of the fine-tuned Random Forest ends up placing 15th out of 174 contestants, ranking the balanced accuracy of the model in the top 10% of results.
