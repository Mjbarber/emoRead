# emoRecSys
Jupyter notebooks written in Python, with the different parts of the code written for the project 'A hybrid readings recommendation system based on emotions'.

The logical order to check them out is:

1. scraper. The corpus retriever. It gets the raw info about reviews and sinopsys using the Goodreads API and it store it on a mongoDB collection.

2. metadata. It gets the emotion analysis from the two corpuses, user's reviews and synopsis of the books, and it store it on mongoDB collections.

3. datasetAnalysyis. General analysis of the emotions of the texts of the two corpuses considered in the study.

4. recSysI. Recommendations system. First steps. Study of solutions to skip decieving texts.

5. recSysII. Recommendations system. Definition of metrics. It gets recommendations from user's reviews and from synpsis of books using different metrics and analyzing results.

6. validation. Validation of the recommendation system. Testing and setting of metrics and parameters for the specific corpus. 

Every notebook includes every needed function from previous ones, so that it can work independently of the rest of notebooks.
