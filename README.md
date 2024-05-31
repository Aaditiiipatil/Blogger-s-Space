### Bloggers Space

This is a simple blog post application built with PHP and MySQL. The application allows users to create, read, update, and delete blog posts. Each post includes a title, content, and an optional image. This README provides extensive information about the setup, data structure, and usage of the application.

## Features

- Create, read, update, and delete blog posts
- Upload images for each blog post
- Display a list of all blog posts
- View individual blog post details

## Prerequisites

- PHP >= 7.4
- MySQL >= 5.7
- Web server (e.g., Apache, Nginx)
- Composer (for dependency management)

```
blog-using-php-mysql/
│
├── images/                    # Directory for uploaded images
├── css/                       # Directory for CSS files
│   └── styles.css             # Main stylesheet
├── db_config.php              # Database configuration file
├── index.php                  # Home page displaying all blog posts
├── create_post.php            # Page for creating a new blog post
├── blog_post_process.php      # Script for processing new blog posts
├── view_post.php              # Page for viewing a single blog post
├── edit_post.php              # Page for editing a blog post
└── delete_post.php            # Script for deleting a blog post

```

- To create client's database go to: <http://localhost/phpmyadmin>

- Start by creating a new database from the left sidebar named as 'blog_db' with the default server connection collation settings.

- After creating the database create a table named as 'blog_table' with 4 columns for id, topic_title, topic_date and topic_para.

- The first column is 'id' which is an integer. Check the Auto Increment checkbox which will also make this field the primary key.

- The next column will be for the 'Post Title' and we'll make this a text type field.

- The next column is for the 'Date of the Created Post' which we'll make a text type field.

- The next column will be of 'Post Paragraph' which we'll make a text type field.

- After creating the database table you may test it by visiting this link in your browser: <http://localhost/bloggers-space/>

- On the `index.php` page all the created posts will be displayed. There is also a `Write a New Post` button on the bottom of the page from where you will be redirected to post creation page `index.html`.

## Features

- On the home page `index.php` all the created posts are displayed.

- Current date and time will be automatically inserted into the post during the time of post creation.

- Major feature of user account creation and displaying dynamic content for each user is pending.

- More features like post deletion, editing existing post and more will be addded soon.

![Screenshot (556)](https://github.com/Aaditiiipatil/Website/assets/143029253/7deea20e-4fe3-48e8-a50b-3d350a65ddba)
![Screenshot (557)](https://github.com/Aaditiiipatil/Website/assets/143029253/41416c1d-358e-4674-b082-d0a5c276a9e1)
![Screenshot (558)](https://github.com/Aaditiiipatil/Website/assets/143029253/adea7073-521d-46b9-859d-8f1b5515af4b)



