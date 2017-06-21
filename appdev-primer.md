# AppDev Primer
 
## firstdraft Ideas

 - [Sign up for a free GitHub account](https://github.com/join)
 
 - [Sign up for a free Heroku account](https://signup.heroku.com/) (if it asks for your preferred programming language, say Ruby)
 
 - Don't forget to verify your email address for both.
 
 - Use those two accounts to sign up at [https://ideas.firstdraft.com/](https://ideas.firstdraft.com/)
 
### IMDb ERD

Our first task:
 
Let's draw an Entity Relationship Diagram (ERD) together for [IMDb First Draft Target](https://appdev-primer-imdb.herokuapp.com/).

## Photogram Database

Given an existing database and data, pretend you're the _application logic_ for a Twitter-like (public, asymmetrical) social network by answering these questions: [Photogram Database Exercise](https://docs.google.com/spreadsheets/d/104IDD206ubqloGZbjtSUAYwfOsFpiC6bQ3C11Re57M4/edit#gid=0).

As you're answering them, think about: what's your process? If you had to explain the process for answering each question [to a five year old](https://vimeo.com/27060669), how would you do it?
 
### Very Best ERD

Now that you've had some practice navigating an existing database, it's time for you to design one yourself, given a set of features.
 
Explore this app: [Very Best Target](http://very-best-demo-pr-3.herokuapp.com/). It's aim is simple; it allows you to keep track of which restaurant in the city serves your favorite version of a particular dish. Your reigning champ for deep dish pizza, for example, could be [Pequod's](http://pequodspizza.com/); but you're always on the lookout for a better one.
 
You can sign in to Very Best with usernames `alice@example.com`, `bob@example.com`, `carol@example.com`, or `eve@example.com`. All of the passwords are "`password`". Click around and try to identify all of the features of the application.
 
See if you agree that these are the features of Very Best (phrased in a particular format known as **user stories**):
    
#### As a user, I should be able to...

##### On the Dishes page

 - See the bucket list of dishes
 - See which venue I have bookmarked for each dish, or choose one if I haven't
 - Filter dishes by cuisine
 - Search dishes by name
 - Click a link to add a venue if it doesn't already exist

##### On the Dish Details page

 - Bookmark a new venue for that dish
 - See the venues I've bookmarked for that dish in the past

##### On the new venue page

 - Add a new venue
   - Name
   - Address
   - Neighborhood (optional)

##### On the Venues page

 - See a list of all venues that I've bookmarked
 - Filter venues by neighborhood
 - Search venues by bookmarked dish

##### On the Venue Details page

 - See which dishes I've bookmarked at a venue
 - Add a new bookmarked dish to the venue
 - See what others have bookmarked at the venue.

##### Notes

 - Initially, users can't add dishes; we, the site admins, will set up the bucket list of dishes.
 - Initially, users will all use the same big list of venues. If and when the dropdown gets too big and unwieldy, we'll figure something else out.
  
#### Once you have a sense of it, your task:
 
Design what you think the database would have to look like in order to support the app. Draw an ERD in firstdraft.
 
### Photogram ERD

Finally: Draw an ERD for [Photogram First Draft Target](https://appdev-primer-photogram.herokuapp.com/users/sign_up).

A social network is just about the trickiest database design you're going to ever have (self-referential many-to-manies, oh  my!), but you've already [navigated it no sweat above](#photogram-database). Now we just have to draw the ERD of that same database.