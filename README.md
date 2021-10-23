# Django-Live-Project 

Django live project that consisted of two one-week sprints with daily standups and a code retrospective each Friday.  In the Django live project there was Python, HTML, CSS (bootstrap styling) coding. 

  

### 10276 Story #1 Build the basic app 

- Created an app using the manage.py startapp in an ongoing project. 

- Registered the app from within the MainProject\settings.py 

- Created home and base HTML template including Django linking block tags. 

  

- Added a function to views.py to render the home page. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(3).png?raw=true) 

  

- Base HTML: Nav Bar, Background image and color.  Nav bar is styled with Bootstrap coding (most of the page styling is with Bootstrap) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(4).png?raw=true) 

  

- Base HTML: Footer 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(5).png?raw=true) 

  

- Home HTML: Just to display the home page image centered in a div container. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(25).png?raw=true) 

  

- Linked the app's home page to the project's home page by adding an image link of the Appbuilder9000(name of the project) 

- Registered URLS with the mainapp and created urls.py for the app and homepage. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(19).png?raw=true) 

  

- As shown above added minimal content and some basic styling to the base and home: Navbar, Background, Title and Footer. 

  

### 10301 Story #2 Create your model 

- Created a model and added migrations from a planned database to keep track for the object.  Included an objects manager for accessing the database. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(21).png?raw=true) 

  

- Created a model form that will include any inputs the user needs to make. 

- Added the template to the app folder for creating a new item, also added to the views.py a function that renders the create page and utilizes the model form to save the collection item to the database. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(7).png?raw=true) 

- HTML to display the form. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(8).png?raw=true) 

- HTML page displaying success for submitting the form.  All fields had to be filled in. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(9).png?raw=true) 

  

### 10302 Story #3 Display all items from database 

- Created a new HTML page, link it from the home page(NavBar) 

- Add in a function that gets all the items from the database and send them to the template. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(10).png?raw=true) 

  

- Display a list of items from the database with some or all of the fields for that item displayed with labels/headers.  Utilized Django template filters. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(15).png?raw=true) 

- (continued) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(16).png?raw=true) 

  

### 10303 Story #4 Details page 

- Added a details template to the template folder, registered in the URL pattern. 

- Created a views.py function that will find a single item from the database and send it to the template. 

- Added a link for each item on the display all items page that will direct to the details page for that item. (the Name of the object is a clickable link to the details page) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(24).png?raw=true) 

  

- Display all the details of the item on the details page. (views.py function on left screen) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(11).png?raw=true) 

  

### 10336 Story #5 Edit and Delete Functions 

- Add and edit page to the templates as well as another pattern URL 

- Use the Model forms and instances to display the content of a single item from the database. (the blue edit button to the right side of each row) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(12).png?raw=true) 

  

- The views.py function will send the information for the single item and save any changes to the database when submitted. 

- Included the option to delete an item with a confirmation that the user wants to delete. (red button next to the blue edit button) 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(13).png?raw=true) 

  

### 10388 Story 6 Setup Beautiful Soup 

- Create a new template for displaying the content of the Web Scrape. 

- Use Beautiful Soup to get the html data form the selected site as a navigable object. 

- Utilizing lxml as the parser to get the section of data needed to scrape from the site. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(18).png?raw=true) 

  

### 10408 Story #7 Parse through html 

- Get elements out of the Beautiful Soup Object to send just the values needed as a relevant dictionary object to the template. 

- Displayed all objects within the data scrape template.  Made a link from the Homepage NavBar to the Web Scraped info page with CSS styling in Bootstrap Cards. 

![photo](https://github.com/Kelinz74/Django-Live-Project/blob/main/Screenshot%20(17).png?raw=true) 

That concludes the projects.
