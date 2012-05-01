Winning Code for the EMC Data Science Global Hackathon (Air Quality Prediction)
-------------------------------------------------------------------------------

**Competition page:** https://www.kaggle.com/c/dsg-hackathon

**Blog post on methodology:** http://blog.kaggle.com/2012/05/01/chucking-everything-into-a-random-forest-ben-hamner-on-winning-the-air-quality-prediction-hackathon/

To train and recreate the winning submission (may be slightly different, as the random number generator didn't have a static seed),

1. Download TrainingData.csv from https://www.kaggle.com/c/dsg-hackathon/data and put it in this folder
2. Run make_predictions.m from the Matlab command prompt
3. Copy the resulting predictions from predictions.csv to the appropriate spreadsheet in SubmissionConversion.xls
4. Save the submission worksheet as a new CSV file