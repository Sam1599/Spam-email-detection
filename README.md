# Spam-email-detection-with-feedback-loop
Hi! This project focuses on the detection of spam emails through the development of various machine learning models. 
With the increasing issue of inbox clutter caused by unwanted emails, the goal is to efficiently classify these spam emails automatically.

The project involves a comprehensive analysis of various machine learning algorithms, with SVM model achieving the highest accuracy among them.

Furthermore, the project's scope extends to the implementation of real-time email classification within a personal Gmail account by using the 'imapclient' library to connect to a Gmail IMAP server and retrieve email data from the Gmail account. 

Often, valid emails are erroneously marked as spam and end up in the junk folder, causing communication issues. I have observed instances where individuals miss critical deadlines, important event dates, or essential links due to this.

This integration allows the model to continuously receive user feedback and correctly categorize legitimate emails, moving them to the inbox folder. Users manually provide feedback by identifying important emails within the junk folder as valid. The model iteratively learns from these real-time feedback loops, with the goal of consistently making accurate predictions.
