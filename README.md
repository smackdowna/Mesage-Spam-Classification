# Mesage-Spam-Classification

DESCRIPTION
--------------

The Message Spam Collection  (also known as corpus in the code) is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 

Format
-----------

The files contain one message per line. Each line is composed by two columns: one with label (ham or spam) and other with the raw text. Here are some examples:

ham   What you doing?how are you?
ham   Ok lar... Joking wif u oni...
ham   dun say so early hor... U c already then say...
ham   MY NO. IN LUTON 0125698789 RING ME IF UR AROUND! H*
ham   Siva is in hostel aha:-.


I used  stemming and stop words to clean the data
used the Naive Baise Classifeier because it works on probabilty
used Confusssion matrix to fid the accuracy result it is array of 2 cross 2 matrix
    
   At last we sace the model in joblib
   
   Code is very simple and you can easily understand
