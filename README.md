# Freego_Interview
Freego Passport is employment platform where a test conducted to measure candidates ability and based on results of test and qualifications a grade is evaluated. Candidates with passing grade their resume with grade are sent to recruitment drive. It is implemented with AI features
<br /> An AI based chat-bot with multiple choice quiz for interview. Model is implemented with AI feature in the sense that a question is asked and based on the answer choice the user opted question reguarding the selected answer choice is asked next and so on. Model is trained using deep learning technique. Chat-bot is created using tkinder module.
<br>
## DataBase.
Database consist of collection of questions and their respective choices. Questions are divided into different category and question are grouped together based on their categories. Then the database is converted in JSON formatt which has four attribute and they are:-
<br /> 1. Tag.
<br /> 2. Pattern.
<br /> 3. Response.
<br /> 4. Options.
<br /> 5. Answer.
<br /> Categories that are devided in the database are mentioned in Tag and Pattern. Questions based on categories are mentioned in response. Choice of question are mentioned in Choice. Correct answer of the question is mentioned in Answer.
<br>
## Data Pre-Processing.
Pre-Processing technique used on data is Natural Language Processing (NLP). The NLP technique that are used are:-
<br /> 1. Stopword Elimination.
<br /> 2. Lemmatization.
<br /> 3. BagOfWords.
<br /> 4. Tokenization.
<br>
## Input Variable & Response Variable.
Input is pattern and Output is Response ie. Input is categories and output is Questions. Input is  pre-processed using bag of word representation where each row length is length of dictionary. Position in which category Occur is appended as 1 and rest as 0. A Classes list is created which consist of collection of all Question. Output is question where row length is lenght of classes and initialy every value is 0 then position which question occur in classes that position in output is append as 1.
<br>
## Model.
Model is trained using deep learning techinque and model used is Sequencial model with dense, dropout and activation layer. Optimizer used is SGD optimizer and optimizer method is nestedrov.
## ChatBot
Quiz platform is created with chatbot and it is implemented using tkinder module
