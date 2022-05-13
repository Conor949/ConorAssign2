# react-movieapp
# Assignment 1 - ReactJS app.

Name: [Conor Carty]

## Overview.

[A brief statement on the content of this repository.
The following repository contains Assignment 1 for Web App Development 2. The Assignment is a continuation of the movie app labs. For the assignment i added , I added routing to these veiws and 3 new TMDB endpoints.]

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]

+ 3 new views to the app
+ Added routing
+ 3 new TMDB endpoints
+ Changed colour of header and cards.

## Setup requirements.

[ There was no non-standard setup steps necessary to run my app locally after cloning the repository. All the steps that I needed to follow where all availble in the react labs app. ]

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.
+ Used the now playing link to create the now plaing veiw - movies/nowplaying
+ Used the popular link to craete the popular veiw - movies/popular
+ Used the top rated link to create the top rated veiw - movies/toprated] 


## Routing.

[ List the __new routes__ supported by your app and state the associated page.
I craeted route paths for each veiw in the src index page]
/movies/toprated" element={< TopratedMoviesPage />} />
/movies/nowplaying" element={< NowplayingMoviesPage />} />
/movies/popular" element={< PopularMoviesPage />} /> 

[If relevant, state what aspects of your app are protected (i.e. require authentication) and what is public.]

## Independent learning (If relevant).

Itemize the technologies/techniques you researched independently and adopted in your project, 
i.e. aspects not covered in the lectures/labs. Include the source code filenames that illustrate these 
(we do not require code excerpts) and provide references to the online resources that helped you (articles/blogs).