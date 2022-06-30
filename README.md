# Project 2: Content Based Recommender

### Project description
The goal of this project is to prepare data from real world hotel dataset, and use the neural network model to train on this set so it gives the best HR@10 score in the final evaluation. The scores are tested on: NNRecommender, AmazonRecommender and NetflixRecommender.

The project constists of two jupyter notebooks:
- `project_1_data_preparation.ipynb` - showing how the data is prepared to be used later in the recommender
- `project_2_recommender_and_evaluation.ipynb` - preparing, tuning and testing the recommender


### Requirements to run the notebook
#### To run this project Python3 environment and following steps are required:

1.  Installing jupyter notebook environment:

		pip install notebook
2.  Installing all packages (at once) needed to run notebook succesfully:

		pip install numpy pandas seaborn matplotlib sklearn hyperopt IPython torch traceback
3.  Running jupyter notebook (from commandline in the project folder destination):

		jupyter notebook


