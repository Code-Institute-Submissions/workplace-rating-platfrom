# Workplace Rating Platform

This platoform allows users adding and viewing reviews about workplaces. The goal is to help users avoid bad companies and learn about which companies are worth working for thorough accessing the reviews of other users.
 
## UX

The UX process is designed with different personas in mind. 

Persona 1: User who would like like to share a review. They can do that using the "add review" functionality

Persona 2: User who would like to view the reviews of others. These can be accessed via the home screen. 

Link to project outline, designed prior to building:

https://drive.google.com/file/d/1ku5ClMFWG5RzOI2qUwImWR3YJ6WO39uf/view?usp=sharing
 

## Features

- Viewing existing reviews from the home page
- Accessing company profile page from the review card 
- Editing an existing review
- Removing an exsiting review
- Adding a new review
- Adding a new company
- Accessing the list of worplaces
- Accessing company profile by clicking "see more" in the list of workplaces
 
### Existing Features

- Viewing existing reviews from the home page (reviews.html)
- Accessing company profile page from the review card (companyprofile.html, "see more" button)
- Editing an existing review (editreview.html)
- Removing an exsiting review (reviews.html)
- Adding a new review (addreview.html)
- Adding a new company (addcompany.html)
- Accessing the list of worplaces (companylist.html)

### Features Left to Implement

- Accessing company profile by clicking "see more" in the list of workplaces
- showing total number of positive and negative reviews about a specific workplace

## Technologies Used

- HTML 
- CSS 
- Materialize - https://materializecss.com/
- JavaScript
- Google Fonts
- Python
- Flask
- MongoDB



## Testing

During the development of the project, regular tests have been conducted. Simplicty of the project did not require test automations, therefore, a manual aproach has been chosen. The tests consisted of:

- adding new reviews and filling in different lenghts of text in the input fields
- editing the reviews
- removing the reviews
- adding new companies
- editing the company info
- removing the companies
- clicking through all of the buttons on the page

## Deployment

The code has been written locally using Visual Studio Code IDE. The project has been regularly pushed to Github. Github has been sunchronized with Heroku allowing for automatic deployment of the app on the Heroku hosting platfrom. The project environment variables are stored in the env.py file which has been hidden in the gitignore file for safety purposes.

### Media
- The photos used in this site were obtained from freepik.com

### Acknowledgements

- I received inspiration for this project from the Code Institute course materials