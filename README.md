# ML2021_Project3
A simple chatbot using FLASK, PYTHON, JINJA2, HTML, CSS, JAVASCRIPT and JSON as mock data

# About Team
 - **Team Name** - Lilac Pasteur
 - **Team No** - 1161
 - **Team Members** 
    - Chinthalapudi Satya Rama Tulasi **(18pa1a0533)**
    - Chilakala Baby Navya **(18pa1a0426)**
    - Chilakala Bala Mahesh **(19pa1a0534)**
    
# About FLASK
- There are a number of frameworks for Python, including **Flask**, Tornado, Pyramid, and Django.
- A **framework** is a code library that makes a developer's life easier when building reliable, scalable, and maintainable web applications by providing reusable code or extensions for common operations.

# Block Diagram of the Chatbot
![](L8_chatbot_block_dig.png)

# Demo Video of how to use this chatbot
**Click on below picture to play the video**<br />
[![Demo_Video](https://img.youtube.com/vi/0rr1YXurPvA/0.jpg)](https://www.youtube.com/watch?v=0rr1YXurPvA)

# Flask app deployed on HEROKU

- Click on the below link to play with **PlantServo chatbot**
   - [PlantServo Chatbot](https://plantservobot.herokuapp.com/)
   
# How I made this Flask app 

- **Creating Virtual Environment**
  - Open VScode
    - **Step - 1** :- In terminal, type "python -m venv demoenv" click Enter
    - **Step - 2** :- In terminal, type "source demoenv/Scripts/activate" click Enter
    - **Step - 3** :- In terminal, type "pip install flask" click Enter  
    - **Step - 4** :- In terminal, type "pip install gunicorn" click Enter
    - **Step - 5** :- In terminal, type "git init" click Enter
    - **Step - 6** :- Outside the demoenv folder create ".gitignore" file
    - **Step - 7** :- Write "demoenv" in .gitignore
    - **Step - 8** :- Outside the demoenv folder create "Readme.md" file and write about your flask app
    
- **Coding Part**
  - Creating Flak Templates
  - Watch the below👇 video how I coded<br />
    [![Demo_Video](https://img.youtube.com/vi/tplSUg7bZhI/0.jpg)](https://www.youtube.com/watch?v=tplSUg7bZhI)
    
# How to Deploy a Flask app in HEROKU

 - Sign up into [heroku.com](https://herokuapp.com)
 - **Step - 1** :- In terminal type "pip freeze > requirements.txt" click Enter
 - **Step - 2(Optional)** :- In terminal type "pip install -r requirements.txt" click Enter
 - **Step - 3** :- Outside the demoenv folder create a "Procfie" file 
 - **Step - 4** :- type "web: gunicorn plantservoapp.main:app" in Procfile file
 - **Step - 5** :- In terminal, type "heroku login -i"
   - Enter email and password
 - **Step - 6** :- In source control type "initial commit" and click tick mark and goto three dots and click push
 - **Step - 7** :- Goto heroku.com and login and click on "new" and click "create new app" and put appname as "plantservobot" and click "create app"
 - **Step - 8** :- In terminal, type  "heroku git:remote -a plantservobot"
 - **Step - 9** :- In terminal type "git push heroku master" click Enter
 

     
   
