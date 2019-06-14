Description:

"Blog App," while unimpressive in name, is a cool mobile blog platform.  It was built with react native, along with a backend featuring MongoDB, Node, and Express.  


Technologies Used:
React Native, MongoDB, Mongoose, Express, Axios, Node, Git, Postman, and Heroku.


Description of Screens and Functionality:

HomeScreen
The app features a home screen which loads all blog posts in order by date.  Each article comes with an image and a title, neatly placed into a Scrolling container, (known as a View or ScrollView in React Native).  The images and titles are clickable and will navigate to that blog's page.  At the bottom of the screen is a tab bar with three routes:  Home, Categories, and About Us).  

DetailsScreen (Individual Blog Post)
Each element of this page pulls from the database, aside from the "Return Home" icon link at the bottom.  The tab bar still appears at the bottom, which works to navigate to any of the three main pages.

CategoriesScreen
This screen returns a list of all unique categories of blog posts found in the database.  When you click on one, it will take you to a screen that looks similar to the homescreen.  It will render whichever blog posts are tagged with that category you select.  From there, you can either click on an article or click back.  Once you click into an article, you are taken back to the detailsScreen for that particular blog post where you will find the same navigation options you would find if you went to a blog post from the home screen.

AboutUsScreen
This screen was a last minute tacked on feature that was intended to be a store page where you could buy merchandise.  However, I ran out of time to implement that feature at this time.  Instead, you get to see a picture of my face.


