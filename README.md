# Data-preprocessing-for-NLP

![1*pzjECYWP8WOWhwfCjebZVw](https://user-images.githubusercontent.com/64656686/210159499-92bdc2b4-d5f3-4ad4-98c5-7c398647663f.png)

# Tokenization

It is used to covert the string in to a list based on the words or the items in the considered string. 
<img width="909" alt="Screenshot 2023-01-01 at 11 45 35" src="https://user-images.githubusercontent.com/64656686/210162563-0ee1fed5-0afa-428b-9d4f-48c8c3d3a138.png">

First needs to import the RegexpTokenizer from the nltk.tokenize
Then needs to create a instance from the RegexpTokenizer() method. Here it specially mentioned to consider only the numbers and words from the string by using the RegexpTokenizer(r'/w+'). 

To Tokenize the real dataset using the data frames, it can use lambda function with the custome function to perform the tokenization. 
<img width="913" alt="Screenshot 2023-01-01 at 11 49 46" src="https://user-images.githubusercontent.com/64656686/210162614-7c4aaf79-ef52-47ab-b42f-c22751f140d1.png">
