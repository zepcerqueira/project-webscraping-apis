<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Pages&Screens - Where Movies & Books Go on Awkward First Dates

*[José Cerqueira]*

*[Data Analytics - AG 2023]*

## Content
- [Project Description](#project-description)


- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description

Welcome to our project - Pages&Screens - where we combine user interface, web scraping and API to allow people their fair share of procrastination.

Our main objective in creating this application is to allow the user the option of choosing how to spend their free time. By choosing either a movie or a book option, the user has the possibility of writing his wildest desires of what that movie or book should be about. After that mind wandering, the app takes that information and gives the best results possible, taking on key words and also based on ranking.

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions

A usable tool that combines the user interface with dataframes search, got from web scraping and API tools.

<a name="dataset"></a>

## Dataset
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

[Dataset]() 

<a name="workflow"></a>

## Workflow

In our project, we followed a well-structured workflow that allowed us to efficiently achieve our objectives. Here are the key steps we went through:

- Project Planning: We initiated the project by defining its objectives, scope, and requirements. This crucial step helped us establish a clear roadmap.

- Team Formation: Our team was divided into two specialized sub-teams, each focusing on a specific aspect of the project. One team was dedicated to web scraping, while the other focused on working with APIs.

- Web Scraping Team Workflow:

    - Data Collection: The web scraping team's primary responsibility was to collect data from 2 websites. This involved identifying target websites, determining the data to scrape, and developing the necessary scraping scripts or tools.
    - Data Cleaning: We ensured that the scraped data was clean and consistent by addressing issues such as duplicates and missing values.
    - Data Integration: The web scraping team prepared the scraped data for integration with the data obtained through APIs, structuring it in a standardized format.

- API Team Workflow:

    - API Integration: The API team worked on integrating data from 1 APIs, which included tasks like API authentication, making API requests, and handling responses.
    - Data Processing: We processed the API data to extract relevant information and ensure consistency.
    - Data Validation: Data retrieved from APIs underwent thorough validation to maintain quality and consistency standards.

- Combining Results: After the completion of both web scraping and API data retrieval tasks, we merged the results. This involved matching and merging data based on common identifiers or keys.

- Main Code Development: Our main code development team then took the combined data and worked on building the core functionality of our project. This included visualization, and other processing as required to meet our project's objectives.

- Testing and Validation: Before deploying the project, we conducted extensive testing and validation to identify and resolve any issues or bugs in our code.

- Deployment: Once the project was thoroughly tested, we deployed it to our intended environment, ensuring that it ran smoothly.

<a name="organization"></a>

## Organization

- In organizing ourselves for the project, we employed a combination of project management tools and regular Zoom meetings to ensure effective collaboration and task management. 

<a name="links"></a>

## Links


[Repository](https://github.com/zepcerqueira/project-webscraping-apis.git)  
[Slides](https://github.com/zepcerqueira/project-webscraping-apis.git)  
[Trello](https://trello.com/en)  