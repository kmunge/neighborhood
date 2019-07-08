# Neighbourhood Watch

#### Neighbourhood helps neighbors interactions easier, by letting them know of business around them and can also interact to share info ,news, events et al

#### By **Munge Kevin**


## Description
Neighbours can create posts, list their businesses, see their neighbours posts and businesses and even search for businesses in other neighbourhoods.

## BDD Specifications
| User Requirements                                | Input                                                                                                                         | Output                                                                                      |
|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| Sign up/Login                                    | To create a new account click the sign up link and fill the form details To login click the login button and fill the details | If login is successful user is navigated to the home page and prompted to create a profile. |
| To create a profile                              | Click the profile tab and create a new profile adding your neighborhood.                                                      | New profile for the user will be created.                                                   |
| To see all posts in your neighborhood            | Navigate to the home page and all posts from your neighborhood will be displayed.                                             | All posts from a user's neighborhood will be displayed.                                     |
| To add a new post                                | click the create post tab on the navbar and submit your new post details.                                                     | Your new post will be displayed on the home page.                                           |
| To add a business                                | Click the businesses tab on the navbar and fill in the form to list a business                                                | Your new business will be listed depending on which neighborhood it is located.             |
| To edit profile/ change your neighborhood        | On the profile page click the edit profile button, make the changes and submit                                                | Profile and neighborhood will be edited.                                                    |
| To view the posts you have created so far        | Navigate to your profile page and all your posts will be listed there.                                                        | All your posts are visible in the profile page                                              |
| To view all the businesses in your neighborhood  | Click the businesses tab on the navbar and then click the neighborhood businesses                                             | All the businesses in your neighborhood will be displayed.                                  |
| To search for a business in other neighborhoods  | Click the search bar and enter the business name                                                                              | All businesses that match that name will be displayed with their details.                   |
| To log out                                       | click the profile icon and then the logout link                                                                               | You will be logged out                                                                      |

## Setup/Installation Requirements
* Ensure you have Installed Python3.6
* Clone the Neighbourhoods Repository
* Create and Activate your virtual environment - `python3.6 -m venv --without-pip virtual` && `source virtual/bin/activate`
* Install dependencies - `pip install -r requirements.txt`
* Create a Database - `psql` then `CREATE DATABASE database name`
* Run Migrations - `python3.6 manage.py makemigrations database name` then `python3.6 manage.py migrate`
* Run the App - `python3.6 manage.py runserver`
* Application should open on `localhost:8000` 

## Known Bugs
There are currently no known bugs.

## Technologies Used
* Python 3.6
* Bootstrap
* Heroku
* HTML
* CSS
* Django

## Support and contact details
For more information, questions, or help using the program, get in touch with me on +254 707 280118 or email: orokomunge@gmail.com.

### License
MIT
Copyright (c) 2019 **Munge Kevin **
  