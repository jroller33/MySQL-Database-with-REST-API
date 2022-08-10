# 🚧This app is under development🚧

build Rest API routes for creating, retrieving, and deleting movies from a MySQL database.

User Stories
* As a user, I want to create a new database.
* As a user, I want to store movie names and reviews in the database in two separate table.
* As a user, I want to see a list of all movies.
* As a user, I want to be able to create and delete a movie.
* As a user, I want to return a list of all the reviews and the associated movie name.

Acceptance Criteria
* It's done when `movie_db` is created and contains a `movies` and `reviews` table.
* It's done when `movie_db` has been seeded with data.
* It's done when the `/api/movies` route renders a list of all movies.
* It's done when the `/api/add-movie` route successfully adds a movie when tested using Insomnia.
* It's done when the `/api/update-review` route successfully updates a movie when tested using Insomnia.
* It's done when the `/api/movie/:id` route deletes a route when tested using Insomnia.
