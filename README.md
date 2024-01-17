## Book_Valuations : Find the right ML model that predicts book rating.


### Table of Contents

1. [Project Purpose](#projet)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Authors and motivations](#authors)



### What is the project ? <a name="projet"></a>

The purpose of this project is to train the right ML model that predicts the possible rating of a new book.

The dataset provided is an extract from Goodreads (https://www.goodreads.com/)

### Installation <a name="install"></a>

This project is composed of the following files :
 - Book_Genre.ipynb => create a csv file with the genre of each books - file created : 'Genre.csv'
 - Book_Authors+List.ipynb => create two specific files about authors and details about the books - files created : 'df_BooksList
 - Book_Rating => create the file with all the information for each book. This file will be used for Machine Learning - file created : 'Book_Rating.

To explore this project download the 

Open the file 

All dependencies to install are listed in requirements.txt file. 


### Files Descriptions <a name="files"></a>

 * books.csv : 
        "bookID" A unique identification number for each book.
        "title" The name under which the book was published.
        "authors" The names of the authors of the book. Multiple authors are delimited by “/”.
        "average_rating" The average rating of the book received in total.
        "isbn" Another unique number to identify the book, known as the International Standard Book Number.
        "isbn13" A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
        "language_code" Indicates the primary language of the book. For instance, “eng” is standard for English.
        "num_pages" The number of pages the book contains.
        "ratings_count" The total number of ratings the book received.
        "text_reviews_count" The total number of written text reviews the book received.
        "publication_date" The date the book was published
        "publisher" The name of the book publisher.
    
 * Books_Final.csv :
       "bookID" A unique identification number for each book.
       "title" The name under which the book was published.
       "authors" The unique name of an author
       "average_rating" The average rating of the book received in total
       "isbn" Another unique number to identify the book, known as the International Standard Book Number.
       "isbn13" A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.
       "language_code" Indicates the primary language of the book. For instance, “eng” is standard for English."isbn" 
       "num_pages" The number of pages the book contains.
       "ratings_count" The total number of ratings the book received
       "text_reviews_count" The total number of written text reviews the book received.
       "publication_date" The date the book was published
       "publisher" The name of the book publisher.
       "book_genre" Each book has its main category of writing splitted per column with 1 as identifier
       "genres.children / genres.comics, graphic / genres.fantasy, paranormal / genres.fiction /
       genres.history, historical fiction, biography / genres.mystery, thriller, crime /
       genres.non-fiction / genres.poetry / genres.romance / genres.young-adult"
       "Months_Until_Today" Nb of month from the publication until sept. 2023
       "co-authors" The authors name which contributed to the book (illustrator, translator,...)
       "authors_rating"  the rating of the author for all its books
       "book_format" audio book or paper book
       "audio 0 book 1" audio = 0 / book = 1

 * .ipynb : 
        This notebook conducts 

### Authors & Motivations <a name="authors"></a>

This project was carried out as part of the preparation for an MSC in Data Science at the DSTI.
