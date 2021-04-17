# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix

### User Stories

#### REQUIRED (10pts)
- [x] (70pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] (10pts) Views should be responsive for both landscape/portrait mode.
   - [x] (5pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (5pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [x] (20pts) Improved the user interface by experimenting with styling and coloring.

### App Walkthough GIF

<img src= "https://github.com/Quentin-Ford/Homework_4/blob/master/HW4.gif" width=250><br>

### Notes
I did not encounter any technical difficulties when making this app, rather, I had some trouble trying to figure out what I should add to improve the UI. In the end,
I did some simple background and text color changes, but I also made it to that it displays the release date of the movies as well as their ratings. In addition, if the movie
being displayed does not have a poster or backdrop image associated with it, I decided to display a generic image as a placeholder.

Also, I was not able to produce a working GIF link from the instructions for Imgur, so I had to upload the GIF to my repository as suggested by one of my classmates and 
use the link to the repo as opposed to the recommended way as that always gave me a .mp4 link.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
