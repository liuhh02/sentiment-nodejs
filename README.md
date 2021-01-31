# HackViolet Sentiment Analysis
A sentiment analysis app to detect the user's feelings through their journal entry. Created for [HackViolet 2021](https://devpost.com/software/beautifly). 
The sentiment analysis model automatically analyzes the user's feelings based on their journal entry to figure out how they are feeling that day and prompt users to reach out to their circle if they are feeling down. Coded with Node.js. 

## Preprocessing ##
1. Handling the negation of words
2. Tokenization
3. Correcting for spelling errors using Levenshtein distance
4. Removing stopwords 
5. Stemming the corpus

## Run the App ##
Enter `npm start` in the terminal and head over to http://localhost:3000/ to see the web app in action.
