# Personality through Big Five from Selfies

## Portrait Personality dataset
In folder "dataset" you can find the Portrait Personality dataset of selfies based on the ChaLearn dataset First Impressions. This dataset consists of 30,935 selfies labeled with apparent personality. Each selfie file was named with the prefix of the original video following by the frame's number, so in the file "bigfive_labels.csv" are stored all the labels where you can find the values of each trait of the Big Five model using the prefix (name of the original video).

## Proposed Models
The main models are located in folder "models", per each model there are some files:
- Python notebook with the complete definition and process of the model.
- Preprocessed data (pickle files) for training and test into the folder "data_for_training&test".
- Best model got (model definition and trained weights) in folder "trained_model".
