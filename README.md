# Project 4 - Meal Prepper

## Manage your meals throughout the week! 
 
 ### Goal: Create a full-stack, MERN App to create, edit and delete meals as well as which day they are to be made.

 #### Backend/API Technology used:
 - Swift
 - PostgreSQL, bit.io
 - CRUD functionality


 ### Daily Plan

| Week | Goal |
|-----|------|
| 1 | Learn Swift basics and play around software |
| 2 | Set up running repos and dive deeper into CRUD aspects for Swift |
| 3 | Rendering data to screen |
| 4 | Bug fixing, visual styling |
| 5 | Presentation |

#### Models
![model image](https://i.imgur.com/W1IOFam.png)

#### Wireframes

![wireframes](https://i.imgur.com/0FaQsVb.jpg)

#### Routes
##### Base route - https://music-list-backend.onrender.com/songs 
| Endpoint | Method | Description |
|----------|--------|-------------|
| router.get('/') | GET | returns all meals |
| router.get('/:id') | GET | returns a single meal|
| router.post('/')| POST | adds a new meal|
| router.put('/:id')| PUT | updates a specific meal |
| router.delete('/:id') | DELETE | deletes a specific meal |


 #### User Stories
 - As a user, I should be able to create, read, update, and delete meals to my meal list
 - As a user, I should be able to display information about each individual meal
 - Bonus: I should be able to create a user profile.
 - Bonus: As a user, I should be able to create a DJ profile to manage the song list provided.
 
