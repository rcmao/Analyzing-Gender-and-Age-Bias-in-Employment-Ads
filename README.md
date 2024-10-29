

# Bias Detection in Australian Job Ads

This repository accompanies the paper: *[Developing a Large-Scale Language Model to Unveil and Alleviate Gender and Age Biases in Australian Job Ads](https://www.computer.org/csdl/proceedings-article/bigdata/2023/10386083/1TUPtwCGNCU)*. It includes comprehensive datasets for model training, model checkpoints, and results from a user study.

## File Descriptions
- **seek_job_scraper.ipynb**: A notebook for scraping job advertisements.

## Code Overview
This repository contains code for training and deploying GPT-based models specifically designed to identify and mitigate biases in job advertisements. Below are the key model components:

- **roberta_young**: A model trained to address biases against younger individuals.
- **roberta_old**: A model trained to address biases against older individuals.
- **roberta_male**: A model trained to address biases against males.

### Model Checkpoints
As demonstrated in the paper, the *RoBERTa* model exhibited the best performance. Checkpoints are available for download below:

- **Gender Bias Checkpoints**: [Google Drive](https://drive.google.com/drive/folders/17mJHu0f9IfcS5LDdb8RnYKdihxq9f1Nn?usp=sharing)
- **Age Bias Checkpoints**: [Google Drive](https://drive.google.com/drive/folders/1-50yqVpcpmZLeopn-havQGuOD5aNy6dj?usp=drive_link)

### Dataset and Data Analysis
The dataset and associated data analysis can be found on Kaggle: [Gender Bias Dataset](https://www.kaggle.com/datasets/ruochenmao/gender-bias-dataset).

