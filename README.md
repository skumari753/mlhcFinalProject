# MLHC Final Project 
Reinforcement Learning for optimal sepsis treatment policies with various remard functions

# data 
Contains raw original data files we got from Aniruddh. The folder is stored on drive link 
https://drive.google.com/file/d/1b_c9VZ5dj2wJuxvo30uIiNTKdFqjum0z/view

# scaled_sets 
Contains processed data files split by train, validation and test datasets. The folder is stored on drive link 
https://drive.google.com/drive/folders/1kkPJYNhHgUa3i23hDKy7VWmCgUrbpXzD?usp=sharing

1. Unzip all files and place them in the data folder
2. Run preprocessing/process_interventions.ipynb
3. Run preprocessing/sampleandhold.ipynb
4. Run preprocessing/preprocess_data.ipynb; preprocessing/preprocess_data_both.ipynb; preprocessing/preprocess_data_kidney.ipynb; preprocessing/preprocess_data_lung.ipynb
5. Run continuous/q_network.ipynb with appropriate scaled csv that was generated from step 4
6. Run visualization/plots.ipynb
7. View all our final visualizations in plots folder
