# Question-Answering-Bert  - assignment 4 (cont'd)

**Q1**  
About Q1 check the repository [Vaccine Sentiment Classifier](https://github.com/nikossrp/Vaccine-Sentiment-Classifier/tree/main/models/4\)%20Pre-trained%20Bert%20Vaccine%20Sentiment%20Classifier).

**Q2**  
In this jupyter notebook I have developed a model for question answering on the dataset [SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/).   
Fine-tuning DistilBert-base model and Bert-base model and comparison between them.  


**Q3**  
To understand what I have done in this task you have to go read the pdf with the title  [What do Models Learn from Question Answering Datasets?](https://arxiv.org/pdf/2004.03490.pdf), on page 3 you can see the table 3 in which there are F1 scores from datasets: [SQuAD 2.0](https://rajpurkar.github.io/SQuAD-explorer/), [TriviaQA](https://nlp.cs.washington.edu/triviaqa/), [NQ](https://github.com/google-research-datasets/natural-questions), [QuAC](https://quac.ai/), [NewsQA](https://github.com/Maluuba/newsqa). 
At first I attempted to compute the scores for datasets using the DistilBert-base model but I saw that the scores was worst than using Bert-base model that is quite resonable since the DistilBert model returns the approximate result. So, I used the Bert-base model with the relevant hyperparameters to compute the F1 scores and compare the 5 different datasets but unfortunately there wasn't enough time to reach the results on pdf as you can see on jupyter notebook, however I approached them. The project was developed on kaggle. Some of the datasets were quite difficult to download so I have uploaded them in my google drive as you can see in the notebook, if you want you can download them.
