# Mod-3-Project

# Life After Covid

Life After Covifd is a (SPA) single-page web application that allows users to purchase PPE products
The inspiration of this app came to us while brainstorming for ideas on what problems we can attemp to resolve during this diffcult time. The products displayed in here have become neccessary items in our every day life.
Users can navigate through a list of PPE products and select the products they wish to purchase. Once they click on each product they will see a description, reviews about the selected products submitted by other users, and the option to submit their own review and to add it to a cart.
## Features
### Serializers
 * Building linear direction on the relationships and model association in the back end 
### CRUD Operation
 User can to:
  * log into the application
  * create an account
  * browse all the products as all, or by category
  * see an error if their account input is wrong
  * create a review
  * add items to their cart 
  * update their cart by removing items 
  * select a quantity between 1 - to and add products to the cart at once.
  * log out 
### Active Record Associations
 * There are 6 models that have the following associations ```has_many, belongs_to and has_many, through: ```
## Domain Model

<img src='FRONTEND/image/ERD.png'> </img>

## Wireframe

<img src='FRONTEND/image/wireframe1.png'> </img>

<img src='FRONTEND/image/wireframe4.png'> </img>

<img src='FRONTEND/image/wireframe2.png'> </img>

<img src='FRONTEND/image/wireframe3.png'> </img>


## Tech Stack
 * Ruby on Rails
 * Rails as an API
 * PostgreSQL
 * HTML/CSS
 * Active Record
## Tools
 * Bootstrap
## Gems 
 * rack-cors
 * active_model_serializers
## Build Status
 Work in Progress!
## Next Steps
 * Improve design elements (look of buttons, background image, text manipulation)
 * Create a chekout Function
 * Add review average on each product
 * Update user information
 * Allow users to upload a profile picture
## Contributors
 * [Anna Kim](https://github.com/iannakim)
 * [Franklin Bado](https://github.com/fbado66)
## Acknowledgements
 We would like to thank:
  * Eric Kim
  * Sylwia Vargas
  * Annie Zheng
  * Isabel K. Lee
  * the Code Bender Cohort
