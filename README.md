# Popcorn Club



A redesigned and refactored movie library built with React JS using [The Movie Database API](https://www.themoviedb.org/documentation/api). For an older version, take a look [here](https://github.com/yumietzk/popcorn-club-old).  
Users can search movies and TV shows and get data by different genres and categories. Users can also see a movie and TV show’s details, movie trailer, and official webpage.  
I implemented Google OAuth 2.0 for user authentication. When users sign in, they can save their favorite movies and TV shows. I created a REST API with JSON Server run on Heroku to save and fetch data stored in favorite.  
I also wrote unit tests with [Jest](https://jestjs.io/) and [Testing Library](https://testing-library.com/).

## Features

### Search and sort data by categories  
Users can search data by changing genres and sort data by title name, release date and rating. Users can also decide how many data they want to get.  


### See detail  
Users can see the detail of movies and TV shows such as movie trailer, website, casts, reviews and related shows. Users can also jump to a detail page of casts. For TV shows, users can see all seasons and episodes' details. And more to explore!  


### Search  
Users can search both movies and TV shows related to a term submitted in a search input.  


### Sign In & Sign Out  
After users sign in, they can save their favorite movies or TV shows by clicking a favorite heart button in each movie and TV show's detail page, and can see the saved data in a favorite page. Without signing in, the favorite button doesn't show up and they can't save data.  


## Built With

- React JS
- Redux
- React Router
- Redux Thunk
- CSS Modules



