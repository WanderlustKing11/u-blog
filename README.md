# u-blog
Node/Express multi-page blog website on local server with MongoDB database

Go to the compose page, create a title and a blog post, and you will be taken back to the home page
where you will see the list of created blog post, their titles, and a small snippet of the post.
Feel free to check out the About and Contact page as well. Each snippet will have a link that will 
take you to a dedicated page with the full blog post using dynamic routing parameters.

To run this program you will need Node. Follow these directions:

1. Download these files and put them into your work folder.
2. In your command line, cd into your working folder.
3. Run: npm init
4. Press enter to accept all the default options.
5. Run: npm i express ejs mongoose
6. Run: node app.js
7. Open your browser (if it did not open automatically), and type in the URL localhost:3000
8. You should be taken to the home page which will have default objects with some loren ipsum.

Future tasks for this project:
I would like to add authentication and authorization for multiple profiles so that users can have
their own posts and choose if they want to share it with other users, but otherwise keep them
private.

I have other versions of this program that I have modified for personal use and have running on a
public server (Heroku) with a database (MongoDB Atlas).
