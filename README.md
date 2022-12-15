# Spam_Classifier

#### Khuziama Rehman, Azwad Shameem, Tufayel Ahmed

![title](https://user-images.githubusercontent.com/69356399/207983824-43ea5e10-28fc-4693-a314-e90550c96930.png)

## Introduction

Everyone has a cell phone, and they text their friends and family numerous times per day. Many people have received SMS messages from unknown senders attempting to steal their personal and financial information. This is a serious issue that we are attempting to help solve because spam SMS messages obstruct users and have the potential to steal personal information. 

![estimated robo sms messages](https://user-images.githubusercontent.com/69356399/207984001-b3a1b460-6635-4896-9804-72bc050e73c4.png)

This is an intriguing issue because everyone has a cell phone and has been impacted by spam texts. To address a similar issue, tech companies have developed spam detection software. Spam filters detect and prevent unsolicited, unwanted, and virus-infected email from reaching inboxes. Spam filters are used by Internet service providers (ISPs) to ensure that they do not send spam to their customers. Why don't cell phone companies develop software to filter unwanted SMS text messages similar to spam detection software for emails? For our data science project, we developed a model that can classify text messages to determine whether they are spam. Phone companies can use this software to filter unwanted spam texts using our spam classification algorithm, preventing people from being scammed, interfering with people's conversations, and generally improving the user experience.

## Data

The primary dataset we used is called “SMS Spam Collection Data Set” and the link to it is “https://archive.ics.uci.edu/ml/datasets/sms+spam+collection”. We took the data from Kaggle, which cites the University as their source. The SMS Spam Collection data set extracted 425 SMS spam messages from the Grubletext Website. The majority of claims about SMS spam messages on this UK forum are made anonymously by cell phone users. Identifying the text of spam messages in claims was a difficult and time-consuming operation that required meticulously analyzing hundreds of web pages. The SMS Spam Collection Data set also extracted 3,375 SMS messages that were randomly selected from The NUS SMS Corpus (NSC) which is a dataset of approximately 10,000 genuine SMS messages gathered for research at the National University of Singapore's Department of Computer Science. The SMS Spam collection dataset has a total of 5574 instances and has 2 columns, type and sms. The type can be ham or spam. Ham denotes that the SMS message is not spam, whereas spam denotes that the SMS message is spam. We choose this dataset because it is basically a corpus of all the available SMS message datasets, unfortunately there is no other alternative because all of the available SMS messages are in this dataset.



