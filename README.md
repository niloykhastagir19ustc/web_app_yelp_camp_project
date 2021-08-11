# web_app_yelp_camp_project

> A Node.js web application project from the Udemy course - [The Web Developer Bootcamp by Colt Steele](https://www.udemy.com/the-web-developer-bootcamp/)

web_app_yelp_camp_project is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account.

## Live Demo
>To see the app in action, go to [https://infinite-sands-39239.herokuapp.com/](https://infinite-sands-39239.herokuapp.com/)
>This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

## Features

* Authentication:
  
  * User login with username and password

  * Admin sign-up with admin code

* Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

  * Admin can manage all posts and comments

* Manage campground posts with basic functionalities:

  * Create, edit and delete posts and comments

  * Upload campground photos

  * Display campground location on Google Maps
  
  * Search existing campgrounds

* Manage user account with basic functionalities:
  * Profile page setup with sign-up

  * Flash messages responding to users' interaction with the app

  * Responsive web design

### Custom Enhancements

* Update campground photos when editing campgrounds

* Update personal information on profile page

* Improve image load time on the landing page using Cloudinary

* Use Helmet to strengthen security
 
## Getting Started

> This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.
