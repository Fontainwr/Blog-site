Ruby on Rails Blog with Comments
This project is a basic blog site with comments, built using Ruby on Rails. It serves as a foundational exercise to learn and understand the framework. By working with Ruby and Rails together, we can create a simple Model-View-Controller (MVC) pattern on top of a CRUD (Create, Read, Update, Delete) approach for handling dynamic data.

Getting Started
To get started with this project, follow the steps below:

Download the source code from the repository.
Install the required gems by running bundle install in your terminal.
Start the Rails server by running rails server in your terminal.
Open your web browser and navigate to http://localhost:3000 to access the blog site.
Features
This blog site demonstrates the fundamental principles of working with Ruby on Rails. It provides the following features:

Creation, reading, updating, and deletion of blog posts.
Ability to associate comments with individual blog posts.
Creation and deletion of comments.
Gems Used
The project makes use of the following gems to enhance development and improve the user experience:

Better Errors: Provides a more visually appealing and user-friendly error page.
Bulma: A CSS framework used for styling the blog site. It simplifies the process of creating visually appealing designs.
Guard: A command-line tool that handles events related to file system modifications. It provides live reloading capabilities for SCSS, JS, CSS, and ERB files.
Guard LiveReload: A gem that works in conjunction with Guard to automatically reload the browser whenever changes are detected in the code base.
To add these gems to your project, include the following code within the development group in your Gemfile:
