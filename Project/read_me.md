
# Unit 3 project
![Title picture](https://github.com/KaiFig/Unit_3/blob/main/Project/football_pic_project_3.webp)


# Criteria A: Planning

## Problem definition
My client is an ISAK student who enjoys watching and playing footabll a lot. However, after he watches the game, he has no way of keeping a track record of it and it is tedious to have to look up the scores online. Additionally, the sources online do not hold all of the football matches he watches as he watches local teams that are not found on the internet.  

## Rationale for Proposed Solution
My proposed solution is to create a mobile app that enables my client to record these details by themselves. As it is saved on the app, the client would not have to look the games up using the internet. Additonally, the client will be able to record all the games that he wants, even those that are not found on the internet. This will enable the client to upload their own scores, with no reliance on internet sources, to produce the record that he wants. 

I will be using python as the primary coding language for a variety of reasons. First of all, it is a very flexible coding language and I can reuse some code that we have already made as it is very versatile [^2]. Additionally, it has a wide range of libraries that can be used to fulfill the clients needs on the project[^6]. The final reason is that this is the only coding language that I am good at and it is very easy to learn as it has a very simple syntax[^7]. Using it will speed up the process much more compared to having to learn another language. 

For the GUI design, I will be using KivyMD. In the project I will be using it to act as the interface between the user and the actual software. The user will be able to send inputs through their keyboard and alter information on the actual application and the databases available to the user. KIVYMD is coded in python which is beneficial to this project as it is also in python and it is very simple to use [^3]. This is of utmost importance in this project as without it, the user will not be able to look at the football match log.

For the database, I will be using SQlite3. THe reason for this is that sqlite is very beginner-friendly not requiring any configuration or set up . This is of utmost improtance to both the developer and the client as we are both newly familiarized with this software and it enables to understand it easier[^5]. Additionally, it is compatible across a wide range of operating systems enabling the code to be used far and wide and by a number of different people[^4]. The final great thing about SQLite is that the resulting file is only one so it is very small and easy to share [^1]. 



**Design statement:**
I will design and make a mobile app for a client who is very invested in footbal. The mobile app will eneable the client to build a digital record of the games he has seen or played in. It will be constructed using the software python, kivy for the webpage, and sql to create a database. It will take around 3 weeks to make and will be evaluated according to the criteria A, B, C, and D.  

## Success criteria
1. The application has a secure login and registration
2. The application enables the user to record each match (final score, players, time of game, location, time of goals, time of substitutions and persons substitued) 
3. The application has a timeline of the game with the record that the user inputs explained in success criteria 2
4. For each match that the user records, there is a seperate page with the timeline and inputs
5. The application will have an overview screen that displays each game in chronolgical order 
6. The aapplication enables the user to record each goal and substitution in real-time


# Criteria B: 

## System diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Project3_system_diagram.jpg)
**Fig x** This shows the system diagram which shows the different applications used in creating the app and the input and output of it
##ER diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/ER_diagram.jpg)
**Fig x** This shows the ER diagram which showcases the projects databases and the relationships between the different tables of it 
##UML diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/UML_diagram.jpg)
**Fig x** This shows the UML diagram for the application. It shows each page and the functions that they have and how it inherits from the parent classes 
##Wireframe diagram 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/wireframe_diagram.jpg)
**Fig x** This shows the wireframe diagram for the application. It was a basic sketch at the beginnning of the project to show how each page was going to look to form a plan for the project 
##Flowcharts 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_1.jpg)
**Fig x** This is the first flowchart which shows the function for making sure the text inputs are not empty. This is important so that the user inputs all the data and doesn't forget about it
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_2.jpg)
**Fig x** This shows the login page in the application. It takes the user inputs and checks them with the database called "my_application", specifically the table "users". This enables me to check if the user is legitimate and it also allows me to check the password with the hash to improve security 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_3.jpg)
**Fig x** This shows the registration page in the application, specifically the function that is called when the button to submit the input is pressed. It saves the inputs to the database and it also makes sure that the password is more than the minimum length


## Record of tasks

| Task No | Planned Action                                                | Planned Outcome                                                                                                 | Time estimate | Target completion date | Criterion |
|---------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Meeting my client                         | To identify what my client wants for a database  | 15min         | Feb 10                | A         |
| 2       | Write the Problem defition                        | Expand our problem context and identify a customer and their specific problem so that we know what we need to acheive with our project  |  20min         | Feb 11          | A         |
|3       | Write the proposed solution and show to client   | My client is able to see what I am creating as a solution and input feedback so that he gets what he wants |20 min | Feb 12    | A     | 
|4       | Write the design statement | Able to proceed with a clear plan and goal now that the designb statement is written    | 10 min  | Feb 13  | A |
|5       | Write each success criteria  | Have a clear outline of what is needed to be acheived for my client so I am able to fulfill the clients needs   | 20 min | Feb 13 | A  |
|6      | Get approval of my success critieria from my client   | To confirm that what I am doing is what the client wants and it fulfills their needs  | 15 min  | Feb 20  | A   | 
|7    | Create the login page and registration page     | I am able to have a login page for my website and also a registration so that new users can also use the page   | 30 min  | Feb 21 | C 
|8    | Create the wireframe diagram of the whole application   | I am able to see what is needed in each page so that I have a clear idea of what I need to code | 45 min  | Feb 21 | B
| 9   | Create the UML diagram for the application    | Can see what my databases need to have    | 30 min    | Feb 22    | B |
|10   | Create the system diagram             | Can showcase what my whole system will look like  | 30 min    | Feb 22    | B   |
|11    | Create the ER diagram        | I can see my database and the connection between the different tables   | 30 min  | Feb 23 | B | 
|12    | Create the home screen of the application     | I am able to have a home screen for the user to be able to come back to and buttosn to access all parts of the application  | 1 hr  | Feb 24 | C
|13   | Create the record screen of the application   | The user is able to record basic information of each football match that he plays and it is saved on a database called record.db  | 1 hr  | Feb 26  | C
|14   | Fix the databases     | The database, instead of having multiple database, it is one database with multiple tables    | 30 min  | Feb 28  | C |
|15  | Create the details page  | The page has a greater detail of what the game is and only shows one game   | 45 min    | Mar 1   | C| 
|16  | Create pages to record goals and substitutions   | This enables the user to record goals and substitutions that happen in each football match that they have recorded  | 1 hr  | Mar 2 | C  | 
|17  | Create the timeline database   | This saves the inputs of the user from the goal and substitution pages  | 30 min  | Mar 2 | C|
|18   | Show the timeline on the details page | For each game, the user is able to see a timeline of the substitutions and the goals  | 30 min  | Mar 3   | C | 
|19   | Fix kivy layout on each page  | The website looks much cleaner before and the user is able to have a better experience  | 2 hrs     | Mar 4 | C| 
|20   | Create validation for each input       | The user will not be able to submit an empty input and there will also be other validation such as dates and times to make sure that all the inputs are valid  | 45 min    | Mar 4     | C | 
|21   | Fix the record goals and substitutions screens  | It validates the team names to make sure that the inputs that the user is entering are valid  | Mar 5     | C |
|22    | Go through my criteria A and B     | Make sure that it is thorough enough to submit the application and that all the charts and records are placed there | 1 hr    | Mar 8| A+B
|23   | Start my criteria C   | Go through each tool that I have used in the project and showcase examples of it from my project    | 1 hr 45 min    | Mar 9     | C | 
|24   | Finalize my criteria C  | Go through my criteria C and make sure that it is finalized so that I am able to make sure that all of the tools are showcased and all of my main functions are shown as well | 1 hr   | Mar 9     | C | 
|25   | Record video    | Showcase my application in a video going through all of my functions  | 30 min    | Mar 10    | D |
| 26   | Edit and upload video | The video is edited and uploaded and I am done with my project     | 30 min    | Mar 10       | D |




## Test plan 

| Instruction                        | Category     | Input example / code                               | Description                                                                                                        | Expected output                                                         | Success criteria |
|------------------------------------|--------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|------------------|
| Test registration system           | Unit testing | username, email, password, confirm password        | Save a new user to the database                                                                                    | Input is added to database "users", window is switched to main menu     | 1     |
| Test recording system              | Unit testing | Team name, score, date, location, player names  | It saves a match to a database  | Input is added to database "record", window is switched to the home screen  | 2, 3
| Test details screen               | Unit testing  | Click on the home screen checkboxes | It opens the details screen with more details  | The details screen is opened and the details of the game are all displayed with buttons to go back and forward   | 3 and 4
| Test the goal and substitution pages  | Integration testing   | Name, team, id, time | From the details screen the user is able to record goals and substitutions as they happen | The user is able to input without any problem and the inputs are saved in the database, then displayed, in a table, in chronological order on the details page of the match | 3, 4, 6| 
| Test all of the inputs to see if they can be empty    | System Testing    | All the inputs    | Test if the inputs are still able to be submitted when they are empty | This should bring an error on the User interface that informs the user that they have to put a valid input | 1, 2, 6 | 
| Test the home screen  | Unit testing  | None  | The user clicks on the checkboxes in the homescreen and is taken to the details screen for each game  | The user is taken to the details page with the specific information about the game  | 3,4 | 


# Criteria C: Development


## Existing Tools

| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    | ORM                             | KivyMD Library |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | OOP structures (classes)        | datetime       |
| Python                     | Encryption                      |                |
| KivyMD                     | if statements                   |                |


## Add game function

```.py
class RecordScreen(MDScreen):
    id_game = None
    def submit(self):
        name = self.ids.Teamname1.text
        name1 = self.ids.Teamname2.text
        score1 = self.ids.Score1.text
        score2 = self.ids.Score2.text
        location = self.ids.Location.text
        time = ""
        id = self.id_game
        if 2000<int(self.ids.year.text)<2024:
            time += self.ids.year.text
            if 0<int(self.ids.month.text) < 13:
                time += self.ids.month.text
                if int(self.ids.month.text) == 1 or 3 or 5 or 7 or 8 or 10 or 12:
                    if int(self.ids.day.text) > 31:
                        self.ids.day.error = True
                    else:
                        time += f"{self.ids.day.text}"
                        x = datetime.datetime(int(self.ids.year.text), int(self.ids.month.text), int(self.ids.day.text))
                        db = database_worker("my_application.db")
                        query = f"INSERT into record (hometeamname, awayteamname, home_score, away_score, location, date1, user_id) values('{name}','{name1}','{score1}','{score2}','{location}','{x}', '{id}')"
                        db.run_save(query)
                        db.close()
                        self.parent.current = "HomeScreen"
                elif int(self.ids.month.text) == 4 or 6 or 9 or 11:
                    if int(self.ids.day.text) > 30:
                        self.ids.day.error = True
                    else:
                        time += f"{self.ids.day.text}"
                        db = database_worker("my_application.db")
                        x = datetime.datetime(int(self.ids.year.text), int(self.ids.month.text), int(self.ids.day.text))
                        query = f"INSERT into record (hometeamname, awayteamname, home_score, away_score, location, date1, user_id) values('{name}','{name1}','{score1}','{score2}','{location}','{x}', '{id}')"
                        db.run_save(query)
                        db.close()
                        self.parent.current = "HomeScreen"
                elif int(self.ids.month.text) == 2:
                    if int(self.ids.day.text) > 28:
                        self.ids.day.error = True
                    else:
                        time += f"{self.ids.day.text}"
                        x = datetime.datetime(int(self.ids.year.text), int(self.ids.month.text), int(self.ids.day.text))
                        db = database_worker("my_application.db")
                        query = f"INSERT into record (hometeamname, awayteamname, home_score, away_score, location, date1, user_id) values('{name}','{name1}','{score1}','{score2}','{location}','{x}', '{id}')"
                        db.run_save(query)
                        db.close()
                        self.parent.current = "HomeScreen"
            else:
                self.ids.month.error = True
        else:
            self.ids.year.error = True
```
**Fig x** This shows the function for adding user inputs to the database. 

The user first inputs the information into different text boxes in the GUI then presses the submit button. When the submit button is pressed it calls this function. It first gets the user data through each text box, referencing their ids to get the information. Then the information is checked to make sure it is not empty (in another function). After this the date is validated. 

The date validation for this example unfortunately looks very messy and is not very well written. As I wasn't sure how to do it as I haven't researched enough about the datetime library to see if there were any ways of validating it there. Therefore, I just made the validation into a bunch of if statements that enable me to check. Unfortunately the byproduct of this it is very long as multiple if statememts are needed to validate it. 

## Setting up file
```.py
import sqlite3
import datetime
from kivymd.app import MDApp
from kivymd.uix.datatables import MDDataTable
from kivymd.uix.screen import MDScreen
from hash_password import encrpyt_password, check_password
```
**Fig x** To set up the file, I first inputed multiple libraries to help me with my project. sqlite3 

## Create table 
```.py
def on_pre_enter(self, *args):
# before the screen is created this code is run
self.data_table = MDDataTable(
    size_hint=(.8, .5),
    pos_hint={"center_x": .5, "center_y": .5},
    use_pagination=True,
    check=True,
    # title of the table
    column_data=[("Home team name ", 80),
            ("Away team name", 60),
            ("Home_score", 40),
            ("Away_score", 40),
            ("Location", 60),
            ("date1", 30),
            ("ID", 30),
            ("ID", 30)
            ]
        )
    # add the functions for events of the mouse
    #self.data_table.bind(on_row_press=self.row_pressed)
    self.data_table.bind(on_check_press=self.check_pressed)
    self.add_widget(self.data_table)
    self.update()
```


##  Decomposition
In this project, when I was presented with a big problem, I split it into multiple smaller and more manageable actions. An example of this was getting the page for the user inputs. I first created the GUI based on my wireframe diagram that enabled me to know what inputs were needed. Then I made the database for the record by adding a table to the existing database so that all of the data would stay in the same database for simplicity. After making the database, I made sure that the inputs were all aligned and were correct and creating the function to update the database with the new user inputs. Then, I made sure to validate all the inputs that the user was inputting. The final action was uploading it onto the application, putting it on the home screen in chronological order in the form of a table then I was finished with this problem.

## ORM
Object relational mappping enables the application to access the database and get information from it. This enables the data to be used in the OOP 
```.py
x = self.id_game
db = database_worker("my_application.db")
query = f"SELECT * from record WHERE game_id = '{x}'"
result = db.search(query=query)
hometeamname, awayteamname, home_score, away_score, location, date1, user_id, game_id = result[0]
```
**Fig x** The code above shows the code for my home sceen. On my home screen, there is a table, showcasing the record table in the "my_application.db" database. To get the data from the database, I use the query variable and the result which calls on a function in the class database worker in the main python file. The use of SQL commands enables me to get the data very easily from the database and showcase it, showing the user all the data they have saved in the record database. 

## OOP structures
OOP or object-orientated programing is when the code is structured around objects instead of regular coding practices. Each object represents an action or object with properties. It uses classes and each class has different functions to do different actions. Also it is possible to inherit from class to class, increasing simplicity and reducing redunancies in the code
```.py
class HomeScreen(MDScreen):
    data_table = None
    id_game = None
    def on_pre_enter(self, *args):
        # before the screen is created this code is run
        self.data_table = MDDataTable(
            size_hint=(.8, .5),
            pos_hint={"center_x": .5, "center_y": .5},
            use_pagination=True,
            check=True,
            # title of the table
            column_data=[("Home team name ", 80),
                         ("Away team name", 60),
                         ("Home_score", 40),
                         ("Away_score", 40),
                         ("Location", 60),
                         ("date1", 30),
                         ("ID", 30),
                         ("ID", 30)
                         ]
        )
        # add the functions for events of the mouse
        #self.data_table.bind(on_row_press=self.row_pressed)
        self.data_table.bind(on_check_press=self.check_pressed)
        self.add_widget(self.data_table)
        self.update()

    def check_pressed(self, table, row):
        print("here", row)
        DetailsScreen.id_game = row[7]
        RecordPScreen.id_game = row[7]
        RecordSubScreen.id_game = row[7]
        self.parent.current = "DetailsScreen"
        db.close()

    def update(self):
        x = self.id_game
        print(f" this is id {x}")
        print(int(x))
        db = database_worker("my_application.db")
        query = f"Select * from record where user_id={x} ORDER BY record.date1 DESC"
        data = db.search(query)
        print(data)
        db.close()
        self.data_table.update_row_data(None, data)

    def recordgame(self):
        self.parent.current = "RecordScreen"
```
**Fig x** This shows my home screen python code. For each screen in my project, each of them has their own class to help seperate them and organize the code. Additionally, in each class there are various functions connnected to buttons and inputs in the GUI. This enables the user to do the actions such as inputing data, going to the next page etc. 

## Encryption
Encryption is when a string of characters is converted to a code to make it more secure and prevent unathorized access to it. This is very important to protect the security of the application and to make sure that the users passwords are not compromised 
```.py
from passlib.hash import sha256_crypt

#create an object of the class CryptoConrtext
hasher = sha256_crypt.using(rounds=30000)

# this function receives the unsafe password and returns hashed
def encrpyt_password(user_password):
    return hasher.encrypt(user_password)
def check_password(hashed_password, user_password):
    return hasher.verify(user_password, hashed_password)

```
**Fig x** This is a seperate file that hashes the password and also verifies it
```.py
from hash_password import encrpyt_password, check_password

hash = encrpyt_password(passwd)
db = database_worker("my_application.db")
query = f"INSERT into users (email, password, username) values('{email}','{hash}','{uname}')"
db.run_save(query)
db.close()
```
**Fig x** This is from my main python file, during the signup, the user inputs their new password and verifies it, then it calls the function which was imported at the top of the file. This enables the users passwords to be encrypted and protected

## Kivy MD
KivyMD ws the software tool that we used to create the GUI that the user will interact with. This is important as the user therefore doesn't see all of the code and instead only sees the interface.
```.kv
<LoginScreen>:
    size: 500,500
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .5, .9
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y":.5}
        padding: dp(50)
        opacity: .7

        MDLabel:
            text: "Login"
            font_size: 50
            size_hint: 1, .2
            halign: "center"
            pos_hint: {"center_x": .5, "center_y":.5}
        MDTextField:
            id: uname
            hint_text: "Enter your username or email"
            icon_left: "email"
            helper_text_mode: "on_error"
            helper_text: "Login incorrect"
            on_text: root.userid_empty()
            required: False

        MDTextField:
            id: passwd
            hint_text: "Enter password"
            icon_left: "key"
            password: True
            helper_text_mode: "on_error"
            helper_text: "Passswords does not match"
            on_text: root.passwd_empty()
            required: False
        MDBoxLayout:
            size_hint: 1, .1

            MDRaisedButton:
                id: login
                text: "Login"
                on_press: root.try_login()
                size_hint: .3, 1
                md_bg_color: "#fcbf49"
            MDLabel:
                size_hint: .3, 1
            MDRaisedButton:
                id: signup
                text: "Signup"
                on_press: root.try_register()
                size_hint: .3, 1
                md_bg_color: "#e63946"
        Widget:
            size_hint_y: None
            height: 100
```
**Fig x**This is an example of my kivymd file. 
```.py
class DetailsScreen(MDScreen):
    id_game=None
    data_table = None
    def on_pre_enter(self):
        print("here2", self.id_game)
        x = self.id_game
        db = database_worker("my_application.db")
        query = f"SELECT * from record WHERE game_id = '{x}'"
        result = db.search(query=query)
        hometeamname, awayteamname, home_score, away_score, location, date1, user_id, game_id = result[0]
        self.ids.teams.text = f"{hometeamname} vs {awayteamname}"
        self.ids.location.text = location
        self.ids.date.text = date1
        self.data_table = MDDataTable(
            size_hint=(.8, .5),
            pos_hint={"center_x": .5, "center_y": .5},
            use_pagination=True,
            # title of the table
            column_data=[("Action", 45),
                         ("Teamname", 40),
                         ("Time", 20),
                         ("Player", 100),
                         ("game_id", 30)
                         ]
        )
        # add the functions for events of the mouse
        # self.data_table.bind(on_row_press=self.row_pressed)
        self.add_widget(self.data_table)
        self.update()
```
**Fig x** This is an example of a function in my main python file which sends commands to the kivy file to change the interface.
KivyMD enables the developer to create the interface that the user interacts. This interface enables the user to write certain inputs and also maneuver around the app to access other functions of the app. The use of python expands the potential to change and adapt the GUI. For example, the above python code enables the user to have a new table that is updated every time they go to that page. If we were only limited to hte kivy file, we would not be able to adapt the interface that the user interacts with.

##MDTextField
Text fields allow the user to input data to save on the application

```.kv
MDTextField:
id: uname
hint_text: "Enter your username or email"
icon_left: "email"
helper_text_mode: "on_error"
helper_text: "Login incorrect"
on_text: root.userid_empty()
required: False
```
**Fig x** This specific text input allows the user to enter their username or their email to login into the application. There is also a function attached to it with the "on_text" piece of code. This enables the kivy file to be connected to the python file and run functions which enable the GUI to be adapted and edited.

##MDRaisedButton
These allow functions to be called and actions to be done
```.kv
MDRaisedButton:
id: signup
text: "Signup"
on_press: root.try_register()
size_hint: .3, 1
md_bg_color: "#e63946"
```
**Fig x** This specific button is in my main kivy file. It enables the user to press it and move to a different page by calling a function in the main python file

##Datetime library 
The Datetime library enables the developer to format all the data that the user inputs into one form and able to call it in chronological order which is one of the success critieria
```.py
x = datetime.datetime(int(self.ids.year.text), int(self.ids.month.text), int(self.ids.day.text))
db = database_worker("my_application.db")
query = f"INSERT into record (hometeamname, awayteamname, home_score, away_score, location, date1, user_id) values('{name}','{name1}','{score1}','{score2}','{location}','{x}', '{id}')"
db.run_save(query)
db.close()
```
**Fig x** This is part of the main python code which enables the user to input the date for each game that they watch. The dates are made into datetime format by the datetime.datetime command
```.py
x = self.id_game
db = database_worker("my_application.db")
query = f"Select * from record where user_id={x} ORDER BY record.date1 DESC"
data = db.search(query)
db.close()
self.data_table.update_row_data(None, data)
```
**Fig x** This is part of the main python code for the home screen which enables the user to see all the games that the user has recorded in chronological order. The use of the datetime library makes it much easier and simpler to display the games in chronological order which is good coding practice

## Relational databases
Databases enable the user to save data and inputs that they have.
```.py
query = f""" CREATE Table if not exists users(
    id INTEGER PRIMARY KEY,
    email text NOT NULL unique,
    password text NOT NULL,
    username text not null
)
"""
db = database_worker("my_application.db")
db.run_save(query)

create = """CREATE TABLE if not exists record(
    hometeamname text NOT NULL,
    awayteamname text NOT NULL,
    home_score INTEGER NOT NULL,
    away_score INTEGER not null,
    location text NOT NULL,
    date1 text NOT NULL,
    user_id INTEGER,
    game_id INTEGER Primary key
   )"""

db.run_save(create)


query = f""" CREATE TABLE if not exists timeline(
    action1 text NOT NULL,
    teamname text NOT NULL,
    time1 INTEGER,
    player text NOT NULL,
    game_id INTEGER
    )"""

db.run_save(query)

db.close()
```
**Fig x** This shows part of my main python file that creates the databases and tables. Having this code in the main python enables the distribituion of the code. When it is distributed, the databases are still able to be created. 




# Appendix 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/1st_meeting.jpg)
**Fig x** This is the notes that I had from my first meeting with my client where I was able to figure out what he wanted

![](https://github.com/KaiFig/Unit_3/blob/main/Project/contract_1.jpg)
**Fig x** This is the original contract for my project 3 that was signed by me and my client

## Citations
[^1]: Appropriate Uses for SQLite, https://www.sqlite.org/whentouse.html#:~:text=The%20advantage%20of%20SQLite%20is,or%20emailed%20to%20a%20colleague.&amp;text=Many%20applications%20use%20SQLite%20as,content%20from%20an%20enterprise%20RDBMS. 
[^2]:Jalli, Artturi. “9 Reasons Why Python Is so Popular in 2023.” Codingem.com, 13 Dec. 2022, https://www.codingem.com/why-is-python-so-popular/. 
[^3]:“Kivy vs Flutter: Learn the Key Differences between Kivy and Flutter.” EDUCBA, 13 June 2022, https://www.educba.com/kivy-vs-flutter/. 
[^4]:S, Ravikiran A. “What Is Sqlite? and When to Use It?” Simplilearn.com, Simplilearn, 16 Feb. 2023, https://www.simplilearn.com/tutorials/sql-tutorial/what-is-sqlite. 
[^5]: “SQLITE3 - DB-API 2.0 Interface for SQLite Databases.” Python Documentation, https://docs.python.org/3/library/sqlite3.html. 
[^6]: “Top 10 Reasons Why Python Is so Popular with Developers in 2023.” UpGrad Blog, 23 Nov. 2022, https://www.upgrad.com/blog/reasons-why-python-popular-with-developers/#:~:text=The%20python%20language%20is%20one,faster%20than%20other%20programming%20languages. 
[^7]: “Why Is Python so Popular?” Pulumi, https://www.pulumi.com/why-is-python-so-popular/. 
[^7]: 
[^8]:
