# aita-classifier
Using data from the AITA subreddit, we seek to answer: Who is the Asshole?

We pulled a database of 500 posts from the AITA (Am I the Asshole?) subreddit, where users tell personal stories and implore the audience to answer the age-old question of who is in the right, given the situation. Employing data annotation, we went through and developed an in-depth guideline of how to methodically determine whether the person is in the right or wrong (guidelines.pdf). 

With our 500 posts, we developed two models — a logistic regression model and a BERT model — that would classify whether posts fell into 5 categories: 
1. YTA (You are the Asshole)
2. TTA (They are the Asshole)
3. NAH (No Assholes Here)
4. ESH (Everyone Sucks Here)
5. Not Enough Information (INFO)

To improve our model, we would look into using a different, larger dataset to pretrain our BERT model, given our current one only uses the 500 posts we self-annotated. However, this project was a good way for us to dip our toes into ML classification methods and using BERT.

Contributors:
Chloe Kim
Angela Ma
Jenna Bustami
