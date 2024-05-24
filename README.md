# Bangla Misleading Clickbait Detection Using Ensemble Learning Approach 
In this project I have collected different bangla news headlines with their contents and trained and tested different Machine Learning models, Deep Learning models and Transformer Models. After the test I have transformer models were performing better than other two types models as a result i decided to ensemble transfomer models which is my proposed model.

Author: Yasin Arfat, Sharmistha Chanda Tista

Venue: 6th International Conference on Electrical Engineering and Information & Communication Technology (ICEEICT)-2024,MIST

Paper Link: https://doi.org/10.1109/ICEEICT62016.2024.10534333


# Abstract:
In this paper, we have concentrated on identifying misleading clickbait headlines in Bangla news articles using an ensemble learning approach. Misleading clickbait headlines are designed to attract readers' attention and encourage them to click on a link, often leading to misleading or sensationalized content. Detecting misleading clickbait is crucial to ensure the credibility and reliability of news sources. The Bangla language, being widely spoken and written, has also seen an increase in misleading clickbait practices, necessitating an effective detection mechanism. Our proposed ensemble learning approach combines multiple transformer models to enhance the accuracy and robustness of misleading clickbait detection. We employ diverse features extracted from news headlines, such as linguistic patterns, sentiment analysis, and semantic embeddings. These features serve as input to the ensemble models, which aggregate their predictions to make a final decision. Our achieved final accuracy is 96%.

# Contribution:
-> Developed a specialized dataset for Bangla misleading clickbait detection
-> Compared the effectiveness of different Machine learning, Deep learning, and transformer models
-> Highlight the process of ensembling transformer models to improve misleading clickbait detection accuracy

# Datset Analysis:
Number of collected datas that i have used in my work

![data2](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/dab24b2d-95cc-478c-a404-bae4d8944735)
![hist1](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/30c4bdd0-e8bf-440e-8b08-6ba8f09beea2) ![stat1](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/7c02a8f3-41b5-43bd-adfe-286ce6601617)

# Proposed Model Overiew:
Figure presents the schematic diagram of my system which is ensemble of XLM-RoBERTa, Bangla BERT and Indic DistilBERT

![Method4](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/505a79f5-0e82-4e4f-b705-8d7b607e5bc4)

# Result Analysis:
Table-I:Results of Machine Learning, Deep Learning and Transformer Models

![image](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/2fd21672-4cc2-4844-bfee-e8c3db1cbc09)

Table-II: Best performing Models

![image](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/895779fa-7554-4676-a017-93fbbc0d5536)

Table-III: Comparison of Prposed and existing models

![image](https://github.com/YasinRafin/Bangla_Misleading_ClickBait_Detection/assets/44867848/22b3c8eb-2ecb-4cbc-a305-04c514ad10b3)

# Conclusion:
Using an ensemble learning strategy, we tackled the crucial job of identifying Bangla misleading clickbait in news headlines. In the digital age, when the dissemination of false or sensationalized content can affect information integrity and user experience, misleading clickbait detection has grown in importance. To effectively recognize misleading clickbait headlines in news stories written in Bangla, we set out to
create a model. We discovered the shortcomings of the current approaches in Bangla misleading clickbait identification and attempted to address these issues using ensemble learning techniques after a comprehensive exploration of the dataset and review of the literature. To improve performance and resilience, we merged the advantages of various classifiers into an ensemble model. Our results showed that the suggested ensemble learning approach performed better in terms of accuracy than individual classifiers and baseline models. The results of our study have broad ramifications because misleading clickbait identification is vital to raising the standard of online content and user experience. Our ensemble model can be used by news aggregators, social networking sites, and content recommendation programs to screen out false or unrelated headlines and give readers more reliable and pertinent information. The significance of this work is in the successful application of ensemble learning techniques to the relatively
untapped field of Bangla misleading clickbait detection. By proving the viability of our strategy, we have raised the bar for subsequent studies in this area. Despite the positive outcomes of our research, there are certain drawbacks to take into account. The generalizability of the model may be hampered by the use of a dataset that has inherent biases or a lack of variety. The performance of the model should be improved through the acquisition of larger and more varied datasets in the future. Furthermore, the ensemble model of XLM-RoBERTa+IndicBERT+Bangla BERT achieved an accuracy of 96% among all the models discussed in this study.






