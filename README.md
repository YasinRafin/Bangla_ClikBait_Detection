# Bangla_Misleading_ClickBait_Detection
In this project I have collected different bangla news headlines with their contents and trained and tested different Machine Learning models, Deep Learning models and Transformer Models. After the test I have transformer models were performing better than other two types models as a result i decided to ensemble transfomer models which is my proposed model.

# Proposed Model:
I have proposed a model which is basically ensemble of three transformer models which are XLM-Roberta, Bangla BERT and Indic DistilBERT. I did weighted ensemble in those three models for that i have taken an array for weights and by trial and error method and i have fixed those weights for my final result. After performing weighted ensemble on those model i got an accuracy of 96% which is much more efficent than existing models. For my task i have collected almost 3350 dataset consisting of misleading clickbait and non-clickbait
