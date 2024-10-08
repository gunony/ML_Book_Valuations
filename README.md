## Book_Valuations : Find the right ML model that predicts book rating.


### Table of Contents

1. [Project Purpose](#projet)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Authors and motivations](#authors)



### What is the project ? <a name="projet"></a>

The purpose of this project is to train the right ML model that predicts the possible rating of a new book. The underlying aim of the project is to answer the question that every reader asks: "Which of all these published books is the best one to choose? 

The dataset provided is an extract from Goodreads (https://www.goodreads.com/).

### Installation <a name="install"></a>

The project is made in two parts. The first part is the constitution of the dataset. The second part focuses on the choice of the models, their training, their performance and the final solution chosen.

I deliberately choose to separate the project into two Jupyter Notebook files corresponding to each part of the project. For the part 1, open the file 'Book_Valuation_Dataset.ipynb', and for the part 2 open the file 'Book_Valuation_MachineLearning.ipynb'.

All dependencies to install are listed in 'requirements.txt' file. 

### Files Descriptions <a name="files"></a>

Books_Final.csv :
- "bookID" A unique identification number for each book.
- "title" The name under which the book was published.
- "authors" The unique name of an author
- "average_rating" The average rating of the book received in total
- "isbn" Another unique number to identify the book, known as the International Standard Book Number.
- "isbn13" A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
- "language_code" Indicates the primary language of the book. For instance, “eng” is standard for English."isbn" 
- "num_pages" The number of pages the book contains.
- "ratings_count" The total number of ratings the book received
- "text_reviews_count" The total number of written text reviews the book received.
- "publication_date" The date the book was published
- "publisher" The name of the book publisher.
- 10 book's genre with the rating given by the readers
- "main_genre" the name of the genre with the major rating
- "Months_Until_Today" Nb of month from the publication until sept. 2023
- "co-authors" The authors name which contributed to the book (illustrator, translator,...)
- "authors_rating"  the rating of the author for all its books
- "book_format" audio book or paper book
- "audio 0 book 1" audio = 0 / book = 1

Book_Valuation_Dataset.ipynb : This notebook, relating to the first part of the project, creates the data used for machine learning (part 2).

Book_Valuation_MachineLearning.ipynb : This notebook is the Machine learning part of the project. IN PROGRESS !!!

### Authors & Motivations <a name="authors"></a>

This project was carried out as part of the preparation for an MSC in Data Science at the DSTI.
