# cfb_2025_model
A relatively simple model that predicts scoring outcomes of FBS games based on 2025 season data. I pull 2025 regular season data from college collegefootballdata.com and filter for only FBS games. I then build a hierarchical Bayesian model using PyMC that estimates each team's latent offensive and defensive strengths, taking into account stadium (if at home), conference strength, within conference games, and FBS-FCS matchups. I use the estimated model to simulate the remaining three games of the 2025 college football playoffs. 

The file with the model and outcomes is "predictor.ipynb." The file with data preparation is "prepare_data.ipynb." Please note that to run the data notebook, you will need to provide your own API key. 
