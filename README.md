# DataMining_Project


## Overview
This project aims to identify unwanted spam messages in SMS (text messages). By analyzing the content of text messages, we classify them into two categories:

- **Spam:** Unwanted or promotional messages  
- **Ham:** Normal, legitimate messages

## Why It Matters
Spam messages are not only annoying but can also be dangerous—many include scams, phishing links, or fraud attempts. Automatically identifying spam helps:

- Protect users from scams and malicious content  
- Reduce distractions caused by unwanted messages  
- Improve mobile communication by keeping inboxes clean  

## What This Project Does
We used real SMS message data and built a system that:

- Reads and cleans text messages  
- Learns patterns in spam vs normal messages  
- Predicts whether a new message is spam or not  

The system was trained and tested using real-world examples to ensure reliable performance.

## How Accurate Is It?
We tested three different methods  to see how well they detect spam:

- All models correctly classified over 90% of messages  
- One model SVM performed the best and is recommended for real use  
- A simple model Naive Bayes is very fast and can work well even on basic devices  

## What You’ll Find in This Project
The notebook includes:

- An introduction to the problem  
- Visual insights from the dataset  
- Step-by-step explanation of how messages are processed  
- A clear comparison of different models  
- Final analysis and practical recommendations  


## Summary
This spam detection tool demonstrates how data science can help protect users in a digital world. By combining smart algorithms with language understanding, we can automatically block harmful or irrelevant content from reaching users.
