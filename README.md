# Natural Language Processing-Spam/Ham-Classification

Highlight: The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research.

Data Set Information:

Dataset can be found at UCI Machine Learning Repository:
https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

Attribute Information:

The collection is composed by just one text file, where each line has the correct class followed by the raw message. 
0 ham What you doing?how are you? 
1 ham Ok lar... Joking wif u oni... 
2 ham dun say so early hor... U c already then say... 
3 ham MY NO. IN LUTON 0125698789 RING ME IF UR AROUND! H* 
4 ham Siva is in hostel aha:-. 
5 ham Cos i was out shopping wif darren jus now n i called him 2 ask wat present he wan lor. Then he started guessing who i was wifn he finally guessed darren lor. 
6 spam FreeMsg: Txt: CALL to No: 86888 & claim your reward of 3 hours talk time to use from your phone now! ubscribe6GBP/ mnth inc 3hrs 16 stop?txtStop 
7 spam Sunshine Quiz! Win a super Sony DVD recorder if you canname the capital of Australia? Text MQUIZ to 82277. B 
8 spam URGENT! Your Mobile No 07808726822 was awarded a L2,000 Bonus Caller Prize on 02/09/03! This is our 2nd attempt to contact YOU! Call 0871-872-9758 BOX95QU 

Natural Language Data Pre-Processing and Cleaning:
1. Removed Puntuations
2. Removed most common Stopwords 

Classification Model Used:
1. Naive Bayes Classification
2. Random Forest
3. Logistics Regression

Conclusion: Naive Bayes and Random Forest performed extremly well in classification.
For more information, please go through the Jupyter Notebook
