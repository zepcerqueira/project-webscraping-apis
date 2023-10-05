

# Pages&Screens - Where Movies & Books Go on Awkward First Dates

Welcome to our project - Pages&Screens - where we combine user interface, web scraping and API to allow people their fair share of procrastination.

Our main objective in creating this application is to allow the user the option of choosing how to spend their free time. By choosing either a movie or a book option, the user has the possibility of writing his wildest desires of what that movie or book should be about. After that mind wandering, the app takes that information and gives the best results possible, taking on key words and also based on ranking.

<a name="Structure"></a>
### Files Avaiable:

Our project is divided between three main files. The web scrapping file of GoodReads, the API themoviedb request file and the pages&screens main code, responsible for the interaction of the previous two.

- readdy_to_prod_books.ipynb
    Web scrapping tool responsible for the creation of a dataframe of books titles, description and rating from the GoodReads website. 

- movies_ready.ipynb
    API interaction tool, responsible for the creation of a usable dataframe of movies, with titles, description and rating. 

- pages&screens.ipynb
    Main code with user interface. Gets the necessary information from the user in order to search for key words in the description columns of movies or books dataframes, depending on the user choice. 
    Presents the results based on ratings from the API and GoodReads and creates a clickable Amazon link to search for the desirable movie or book option.

- wordery_readdy.ipynb
    Secondary code responsible for retrieving a usable dataframe of books, similar to GoodReads, in case Goodreads failure .

<a name="Other Files"></a>
### Web Scrapping - GoodReads:

- books_df_with_description.csv
    File created after running readdy_to_prod_books.ipynb

    As a dataframe:
<img src="https://ibb.co/FVw6bML" alt="Books DF" width="500"/>

  - top_250_movies_by_genre.csv
    File created after running movies_ready.ipynb

    As a dataframe:
<img src="https://ibb.co/2Ypk2qD" alt="Movies DF" width="500"/>  

<a name="Resources"></a>
## Web Scrapping - GoodReads:

https://www.goodreads.com/list/show/1.Best_Books_Ever

Best Books Ever
The best books ever, as voted on by the general Goodreads community. 

A list by rating or over 100.000 books.

## API Interaction - themoviedb:

https://developer.themoviedb.org/docs

The Movie Database (TMDB) is a community built movie and TV database. Every piece of data has been added by their community dating back to 2008. TMDB's strong international focus and breadth of data are largely unmatched.

________________________________________

<a name="FAQ"></a>
### Why the code separation?

- Our web scrapping tool was getting allot of time retrieving the book info, around 9 to 10 hours. We assume that the servers don't process request like ours as first priority. We also had difficulties getting the full dataframe on the book list. We also assume that the servers may have a time limit and we were being constantly shut down. In order to overcome this obstacle, we separate the codes in order for the app to run only one code to get the user what he needs, and the API and web scrapping tools could run separately and in times of the day with less user interaction.

<a name="FAQ"></a>
### Why another webscrapping tool?

- For the same reason we separate the code. We want a backup in case we got constant errors on Goodreads and could not get a usable CSV file.

________________________________________






