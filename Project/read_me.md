
# Unit 3 project
![Title picture](https://github.com/KaiFig/Unit_3/blob/main/Project/football_pic_project_3.webp)
**Fig 1** This is the title picture and it is the main picture in my application


# Criteria A: Planning

## Problem definition
My client is an ISAK student who enjoys watching and playing footabll a lot. However, after he watches the game, he has no way of keeping a track record of it and it is tedious to have to look up the scores online. Additionally, the sources online do not hold all of the football matches he watches as he watches local teams that are not found on the internet.  

## Proposed solution
My proposed solution is to create a mobile app that enables my client to record these details by themselves. As it is saved on the app, the client would not have to look the games up using the internet. Additonally, the client will be able to record all the games that he wants, even those that are not found on the internet. This will enable the client to upload their own scores, with no reliance on internet sources, to produce the record that he wants. 

## Rationale for proposed solution
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


# Criteria B: Design

## System diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Project3_system_diagram.jpg)
**Fig 2** This shows the system diagram which shows the different applications used in creating the app and the input and output of it
##ER diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/ER_diagram.jpg)
**Fig 3** This shows the ER diagram which showcases the projects databases and the relationships between the different tables of it 
##UML diagram
![](https://github.com/KaiFig/Unit_3/blob/main/Project/UML_diagram.jpg)
**Fig 4** This shows the UML diagram for the application. It shows each page and the functions that they have and how it inherits from the parent classes 
##Wireframe diagram 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/wireframe_diagram.jpg)
**Fig 5** This shows the wireframe diagram for the application. It was a basic sketch at the beginnning of the project to show how each page was going to look to form a plan for the project 
##Flowcharts 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_1.jpg)
**Fig 6** This is the first flowchart which shows the function for making sure the text inputs are not empty. This is important so that the user inputs all the data and doesn't forget about it
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_2.jpg)
**Fig 7** This shows the login page in the application. It takes the user inputs and checks them with the database called "my_application", specifically the table "users". This enables me to check if the user is legitimate and it also allows me to check the password with the hash to improve security 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart_3.jpg)
**Fig 8** This shows the registration page in the application, specifically the function that is called when the button to submit the input is pressed. It saves the inputs to the database and it also makes sure that the password is more than the minimum length


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
**Fig 9** This shows the function for adding user inputs to the database. 

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
**Fig 10** To set up the file, I first inputed multiple libraries to help me with my project. sqlite3 is an SQL library which enables me to call the database. This enables me to get the data saved which is of utmost importance to fulfill the success critieria. The datetime library helps me order everything in chronological order which is one of my success criteria and is an example of pattern recognition. Before, I would've manually done the chronological ordering, however, with the datetime library, I am able to just use one thing across multiple places in my code. The kivymd libraries downloaded are for the main kivy file. They enable me to actually show the user interface with the tables displaying the database. Lastly, from another file, I call 2 functions which help me with the login and registration parts of the application. This shows decomposition, I was faced with a large problem and to solve it, I split into smaller actions, one of them being in the login and registration parts of the application where to simplify things I just called another function.

##Recording goals
```.py
def submit(self):
    teamname = self.ids.teamname.text
    x = self.id_game
    query = f"SELECT * from record WHERE game_id = '{x}'"
    db = database_worker("my_application.db")
    result = db.search(query=query)
    hometeamname, awayteamname, home_score, away_score, location, date1, user_id, game_id = result[0]
    print("result", result, "result2", result,"result1")
    if teamname == hometeamname or teamname == awayteamname:
        time = self.ids.time.text
        player = self.ids.player.text
        player2 = f"{player} scored"
        action = "Goal"
        db = database_worker("my_application.db")
        gamerecord = f"INSERT into timeline (action1, teamname, time1, player, game_id) values('{action}','{teamname}', '{time}', '{player2}','{x}')"
        db.run_save(gamerecord)
        db.close()
        self.parent.current = "DetailsScreen"
    else:
        self.ids.teamname.error = True
```
**Fig 11** This is the code for adding goals to the timeline database. First it gets the teamname from the user input by calling the kivy text box. Then from the record, it selects the hometeamname and awayteamname from the record database. After this, I check the teamname to make sure that it is either the away or the home team names and if it isn't the error shows up. IF it is then I get the rest of the user inputs from the kivy file and insert it into the database. All the tables in the database have the same user_id which makes sure that multiple users can use this application but only their data will show. 

For this piece of code, I have used the computational thinking skill algorithim design to create a function to receive user inputs and validate them. I have also used decomposition in this scenario. I first got the inputs, then thought about inserting them into the database. After that was working I worked on the validation which shows how I broke this down into two smaller steps. 

## Database worker
```.py
class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()
```
**Fig 11** This class was created so I could form an SQL query to access the database of my application. The use of this class enables me to easily create an SQL query as the only hting I need to put is the name of the application. Then, with the functions in the class, I am able to search, save and close the connection. This is an example of pattern recognition. Querying the database is something that I have to do over and over again and the use of the database worker class enables me to create a general function that I can use every time, greatly simplifying the code. Additionally, this class takes the database name and uses a cursor to interact with the database. Therefore, this is an example of abstraction as the only thing that the developer has to do is just list the name and this class will do the work connecting to the database. 

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
**Fig 11** This function creates the table for the home screen. This connects to the kivy MD file as it displays a table on the user interface with the data from the database. Additionally, it has checkboxes which when pressed are taken to another function which opens up the detail screen for each game. This fulfills multiple success critieria as it also is able to be listed in chronological order when the data is queryed from the database. 


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
**Fig 12** The code above shows the code for my home sceen. On my home screen, there is a table, showcasing the record table in the "my_application.db" database. To get the data from the database, I use the query variable and the result which calls on a function in the class database worker in the main python file. The use of SQL commands enables me to get the data very easily from the database and showcase it, showing the user all the data they have saved in the record database. 

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
**Fig 13** This shows my home screen python code. For each screen in my project, each of them has their own class to help seperate them and organize the code. Additionally, in each class there are various functions connnected to buttons and inputs in the GUI. This enables the user to do the actions such as inputing data, going to the next page etc. 

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
**Fig 14** This is a seperate file that hashes the password and also verifies it
```.py
from hash_password import encrpyt_password, check_password

hash = encrpyt_password(passwd)
db = database_worker("my_application.db")
query = f"INSERT into users (email, password, username) values('{email}','{hash}','{uname}')"
db.run_save(query)
db.close()
```
**Fig 15** This is from my main python file, during the signup, the user inputs their new password and verifies it, then it calls the function which was imported at the top of the file. This enables the users passwords to be encrypted and protected

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
**Fig 16**This is an example of my kivymd file. 
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
**Fig 17** This is an example of a function in my main python file which sends commands to the kivy file to change the interface.
KivyMD enables the developer to create the interface that the user interacts. This interface enables the user to write certain inputs and also maneuver around the app to access other functions of the app. The use of python expands the potential to change and adapt the GUI. For example, the above python code enables the user to have a new table that is updated every time they go to that page. If we were only limited to hte kivy file, we would not be able to adapt the interface that the user interacts with.

## MDTextField
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
**Fig 18** This specific text input allows the user to enter their username or their email to login into the application. There is also a function attached to it with the "on_text" piece of code. This enables the kivy file to be connected to the python file and run functions which enable the GUI to be adapted and edited.

## MDRaisedButton
These allow functions to be called and actions to be done
```.kv
MDRaisedButton:
id: signup
text: "Signup"
on_press: root.try_register()
size_hint: .3, 1
md_bg_color: "#e63946"
```
**Fig 19** This specific button is in my main kivy file. It enables the user to press it and move to a different page by calling a function in the main python file

## Datetime library 
The Datetime library enables the developer to format all the data that the user inputs into one form and able to call it in chronological order which is one of the success critieria
```.py
x = datetime.datetime(int(self.ids.year.text), int(self.ids.month.text), int(self.ids.day.text))
db = database_worker("my_application.db")
query = f"INSERT into record (hometeamname, awayteamname, home_score, away_score, location, date1, user_id) values('{name}','{name1}','{score1}','{score2}','{location}','{x}', '{id}')"
db.run_save(query)
db.close()
```
**Fig 20** This is part of the main python code which enables the user to input the date for each game that they watch. The dates are made into datetime format by the datetime.datetime command
```.py
x = self.id_game
db = database_worker("my_application.db")
query = f"Select * from record where user_id={x} ORDER BY record.date1 DESC"
data = db.search(query)
db.close()
self.data_table.update_row_data(None, data)
```
**Fig 21** This is part of the main python code for the home screen which enables the user to see all the games that the user has recorded in chronological order. The use of the datetime library makes it much easier and simpler to display the games in chronological order which is good coding practice

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
**Fig 22** This shows part of my main python file that creates the databases and tables. Having this code in the main python enables the distribituion of the code. When it is distributed, the databases are still able to be created. 

# Criteria D: Functionality 

## Demonstration video 
https://drive.google.com/drive/folders/1Aa-nwUP6wcilUtq9B-dB70pj9rHy01Uv?usp=sharing

This is the link to my google drive file with the video.


# Appendix 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/1st_meeting.jpg)
**Fig 23** This is the notes that I had from my first meeting with my client where I was able to figure out what he wanted

![](https://github.com/KaiFig/Unit_3/blob/main/Project/contract_1.jpg)
**Fig 24** This is the original contract for my project 3 that was signed by me and my client

![](https://github.com/KaiFig/Unit_3/blob/main/Project/contract_2.jpg)
**Fig 25** This is the revised contract for my project 3 signed by me and my client 

## Citations
[^1]: Appropriate Uses for SQLite, https://www.sqlite.org/whentouse.html#:~:text=The%20advantage%20of%20SQLite%20is,or%20emailed%20to%20a%20colleague.&amp;text=Many%20applications%20use%20SQLite%20as,content%20from%20an%20enterprise%20RDBMS. 
[^2]:Jalli, Artturi. “9 Reasons Why Python Is so Popular in 2023.” Codingem.com, 13 Dec. 2022, https://www.codingem.com/why-is-python-so-popular/. 
[^3]:“Kivy vs Flutter: Learn the Key Differences between Kivy and Flutter.” EDUCBA, 13 June 2022, https://www.educba.com/kivy-vs-flutter/. 
[^4]:S, Ravikiran A. “What Is Sqlite? and When to Use It?” Simplilearn.com, Simplilearn, 16 Feb. 2023, https://www.simplilearn.com/tutorials/sql-tutorial/what-is-sqlite. 
[^5]: “SQLITE3 - DB-API 2.0 Interface for SQLite Databases.” Python Documentation, https://docs.python.org/3/library/sqlite3.html. 
[^6]: “Top 10 Reasons Why Python Is so Popular with Developers in 2023.” UpGrad Blog, 23 Nov. 2022, https://www.upgrad.com/blog/reasons-why-python-popular-with-developers/#:~:text=The%20python%20language%20is%20one,faster%20than%20other%20programming%20languages. 
[^7]: “Why Is Python so Popular?” Pulumi, https://www.pulumi.com/why-is-python-so-popular/. 


```.py
import sqlite3
import datetime
from kivymd.app import MDApp
from kivymd.uix.datatables import MDDataTable
from kivymd.uix.screen import MDScreen
from hash_password import encrpyt_password, check_password



class database_worker:
    def __init__(self, name):
        self.connection = sqlite3.connect(name)
        self.cursor = self.connection.cursor()

    def search(self, query):
        result = self.cursor.execute(query).fetchall()
        return result

    def run_save(self, query):
        self.cursor.execute(query)
        self.connection.commit()

    def close(self):
        self.connection.close()

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

"""Select * from record JOIN users ON record.user_id=users.id where user.id=2"""
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
        db = database_worker("my_application.db")
        query = f"Select * from record where user_id={x} ORDER BY record.date1 DESC"
        data = db.search(query)
        db.close()
        self.data_table.update_row_data(None, data)

    def recordgame(self):
        self.parent.current = "RecordScreen"


class LoginScreen(MDScreen):
    def userid_empty(self):
        input1 = self.ids.uname.text
        if input1 == "":
            self.ids.uname.helper_text_mode = "on_error"
            self.ids.uname.helper_text = "Username is required"
            self.ids.uname.required = True
    def passwd_empty(self):
        input1 = self.ids.passwd.text
        if input1 == "":
            self.ids.passwd.helper_text_mode = "on_error"
            self.ids.passwd.required = True
            self.ids.passwd.helper_text = "Password is required"

    def try_login(self):
        uname = self.ids.uname.text
        passwd = self.ids.passwd.text
        query = f"SELECT * from users WHERE username = '{uname}'"
        db = database_worker("my_application.db")
        result = db.search(query=query)
        db.close()
        if len(result) == 1:
            id, email, hashed, uname = result[0]
            if check_password(user_password=passwd, hashed_password=hashed):
                HomeScreen.id_game = id
                RecordScreen.id_game = id
                self.parent.current = "HomeScreen"
            else:
                self.ids.passwd.error = True
                self.ids.passwd.helper_text = "Password is incorrect"
        else:
            self.ids.uname.error = True
            self.ids.uname.helper_text = "Username is incorrect"
            self.ids.passwd.error = True
            self.ids.passwd.helper_text = "Password is incorrect"

    def try_register(self):
        print("User trying to register")
        self.ids.uname.text = ""
        self.ids.passwd.text = ""
        self.ids.passwd.error = False
        self.ids.uname.error = False
        self.ids.uname.required = False
        self.ids.passwd.required = False
        self.parent.current = "SignupScreen"

class SignupScreen(MDScreen):
    def userid_empty(self):
        input1 = self.ids.uname.text
        if input1 == "":
            self.ids.uname.helper_text_mode = "on_error"
            self.ids.uname.helper_text = "Username is required"
            self.ids.uname.required = True
    def email_empty(self):
        input1 = self.ids.emails.text
        if input1 == "":
            self.ids.emails.helper_text_mode = "on_error"
            self.ids.emails.helper_text = "Email is required"
            self.ids.emails.required = True
    def passwd_empty(self):
        input1 = self.ids.passwd.text
        if input1 == "":
            self.ids.passwd.helper_text_mode = "on_error"
            self.ids.passwd.helper_text = "Passwd is required"
            self.ids.passwd.required = True
    def passwd2_empty(self):
        input1 = self.ids.passwd2.text
        if input1 == "":
            self.ids.passwd2.helper_text_mode = "on_error"
            self.ids.passwd2.helper_text = "Passwd confirmation is required"
            self.ids.passwd2.required = True
    def try_register(self):
        uname = self.ids.uname.text
        email = self.ids.emails.text
        passwd = self.ids.passwd.text
        passwd2 = self.ids.passwd2.text
        if len(passwd) > 10:
            if passwd != passwd2:
                self.ids.passwd.error = True
                self.ids.passwd.helper_text = "Password does not match"
                self.ids.passwd2.helper_text = "Password does not match"
                self.ids.passwd2.error = True
            else:
                hash = encrpyt_password(passwd)
                db = database_worker("my_application.db")
                query = f"INSERT into users (email, password, username) values('{email}','{hash}','{uname}')"
                db.run_save(query)
                db.close()
                print("Registration complete")
                self.ids.passwd.text = ""
                self.ids.uname.text = ""
                self.ids.emails.text = ""
                self.ids.passwd2.text = ""
                self.parent.current = "LoginScreen"
                self.ids.passwd.error = False
                self.ids.passwd2.error = False
                self.ids.uname.required = False
                self.ids.emails.required = False
                self.ids.passwd.required = False
                self.ids.passwd.required = False

        else:
            self.ids.passwd.error = True
            self.ids.passwd.helper_text = "Password needs to be more than 10 characters"
            self.ids.passwd2.error = True
            self.ids.passwd2.helper_text = "Password needs to be more than 10 characters"

    def cancel(self):
        self.ids.passwd.text = ""
        self.ids.passwd2.text = ""
        self.ids.uname.text = ""
        self.ids.emails.text = ""
        self.parent.current = "LoginScreen"
        self.ids.passwd.error = False
        self.ids.passwd2.error = False
        self.ids.uname.required = False
        self.ids.emails.required = False
        self.ids.passwd.required = False
        self.ids.passwd.required = False


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
                        self.ids.month.text = ""
                        self.ids.day.text = ""
                        self.ids.year.text = ""
                        self.ids.Location.text = ""
                        self.ids.Score2.text = ""
                        self.ids.Score1.text = ""
                        self.ids.Teamname2.text = ""
                        self.ids.Teamname1.text = ""
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
                        self.ids.month.text = ""
                        self.ids.day.text = ""
                        self.ids.year.text = ""
                        self.ids.Location.text = ""
                        self.ids.Score2.text = ""
                        self.ids.Score1.text = ""
                        self.ids.Teamname2.text = ""
                        self.ids.Teamname1.text = ""

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
                        self.ids.month.text = ""
                        self.ids.day.text = ""
                        self.ids.year.text = ""
                        self.ids.Location.text = ""
                        self.ids.Score2.text = ""
                        self.ids.Score1.text = ""
                        self.ids.Teamname2.text = ""
                        self.ids.Teamname1.text = ""

            else:
                self.ids.month.error = True
        else:
            self.ids.year.error = True
    def teamname1_empty(self):
        input1 = self.ids.Teamname1.text
        if input1 == "":
            self.ids.Teamname1.helper_text_mode = "on_error"
            self.ids.Teamname1.helper_text = "Team name is required"
            self.ids.Teamname1.required = True
    def teamname2_empty(self):
        input1 = self.ids.Teamname2.text
        if input1 == "":
            self.ids.Teamname2.helper_text_mode = "on_error"
            self.ids.Teamname2.helper_text = "Team name is required"
            self.ids.Teamname2.required = True
    def score1_empty(self):
        input1 = self.ids.Score1.text
        if input1 == "":
            self.ids.Score1.helper_text_mode = "on_error"
            self.ids.Score1.helper_text = "Score is required"
            self.ids.Score1.required = True
    def score2_empty(self):
        input1 = self.ids.Score2.text
        if input1 == "":
            self.ids.Score2.helper_text_mode = "on_error"
            self.ids.Score2.helper_text = "Score is required"
            self.ids.Score2.required = True
    def location_empty(self):
        input1 = self.ids.Location.text
        if input1 == "":
            self.ids.Location.helper_text_mode = "on_error"
            self.ids.Location.helper_text = "Location is required"
            self.ids.Location.required = True
    def day_empty(self):
        input1 = self.ids.day.text
        if input1 == "":
            self.ids.day.helper_text_mode = "on_error"
            self.ids.day.helper_text = "Day is required"
            self.ids.day.required = True
    def month_empty(self):
        input1 = self.ids.month.text
        if input1 == "":
            self.ids.month.helper_text_mode = "on_error"
            self.ids.month.helper_text = "Month is required"
            self.ids.month.required = True
    def year_empty(self):
        input1 = self.ids.year.text
        if input1 == "":
            self.ids.year.helper_text_mode = "on_error"
            self.ids.year.helper_text = "Year is required"
            self.ids.year.required = True
    def cancel(self):
        self.parent.current = "HomeScreen"
        self.ids.day.required = False
        self.ids.year.required = False
        self.Teamname1.required = False
        self.Teamname2.required = False
        self.Score1.required = False
        self.Score2.required = False
        self.Location.required = False
        self.ids.month.text = ""
        self.ids.day.text = ""
        self.ids.year.text = ""
        self.ids.Location.text = ""
        self.ids.Score2.text = ""
        self.ids.Score1.text = ""
        self.ids.Teamname2.text = ""
        self.ids.Teamname1.text = ""
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


    def back(self):
        self.ids.teams.text = ""
        self.ids.location.text = ""
        self.ids.date.text = ""
        self.parent.current = "HomeScreen"

    def update(self):
        x = self.id_game
        print(f" this is id {x}")
        db = database_worker("my_application.db")
        query = f"Select * from timeline where game_id={x} ORDER BY time1 ASC"
        data = db.search(query)
        print(data)
        db.close()
        self.data_table.update_row_data(None, data)
class RecordPScreen(MDScreen):
    id_game = None
    def teamname5_empty(self):
        input1 = self.ids.teamname.text
        if input1 == "":
            self.ids.teamname.helper_text_mode = "on_error"
            self.ids.teamname.helper_text = "Team name is required"
            self.ids.teamname.required = True
    def time_empty(self):
        input1 = self.ids.time.text
        if input1 == "":
            self.ids.time.helper_text_mode = "on_error"
            self.ids.time.helper_text = "Time is required"
            self.ids.time.required = True
    def player_empty(self):
        input1 = self.ids.player.text
        if input1 == "":
            self.ids.player.helper_text_mode = "on_error"
            self.ids.player.helper_text = "Player is required"
            self.ids.player.required = True
    def cancel(self):
        self.ids.teamname.text = ""
        self.ids.time.text = ""
        self.ids.player.text = ""
        self.parent.current = "DetailsScreen"

    def submit(self):
        teamname = self.ids.teamname.text
        x = self.id_game
        query = f"SELECT * from record WHERE game_id = '{x}'"
        db = database_worker("my_application.db")
        result = db.search(query=query)
        hometeamname, awayteamname, home_score, away_score, location, date1, user_id, game_id = result[0]
        print("result", result, "result2", result,"result1")
        if teamname == hometeamname or teamname == awayteamname:
            time = self.ids.time.text
            player = self.ids.player.text
            player2 = f"{player} scored"
            action = "Goal"
            db = database_worker("my_application.db")
            gamerecord = f"INSERT into timeline (action1, teamname, time1, player, game_id) values('{action}','{teamname}', '{time}', '{player2}','{x}')"
            db.run_save(gamerecord)
            db.close()
            self.parent.current = "DetailsScreen"
            self.ids.teamname.required = False
            self.ids.player.required = False
            self.ids.time.required = False
            self.ids.time.text = ""
            self.ids.teamname.text = ""
            self.ids.player.text = ""
        else:
            self.ids.teamname.error = True

class RecordSubScreen(MDScreen):
    id_game = None
    def submit(self):
        teamname = self.ids.teamname.text
        x = self.id_game
        query = f"SELECT * from record WHERE game_id = '{x}'"
        db = database_worker("my_application.db")
        result = db.search(query=query)
        hometeamname, awayteamname, home_score, away_score, location, date1, user_id, game_id = result[0]
        print("result", result, "result2", result,"result1")
        if teamname == hometeamname or teamname == awayteamname:
            time = self.ids.time.text
            player1 = self.ids.player1.text
            player2 = self.ids.player2.text
            action = "Substitution"
            substitute = f"{player2} was substituted out {player1} substituted in"
            db = database_worker("my_application.db")
            gamerecord = f"INSERT into timeline (action1, teamname, time1, player, game_id) values('{action}','{teamname}', '{time}', '{substitute}','{x}')"
            db.run_save(gamerecord)
            db.close()
            self.parent.current = "DetailsScreen"
            self.ids.teamname.required = False
            self.ids.player1.required = False
            self.ids.time.required = False
            self.ids.player2.required = False
            self.ids.time.text = ""
            self.ids.teamname.text = ""
            self.ids.player1.text = ""
            self.ids.player2.text = ""
        else:
            self.ids.teamname.error = True
    def teamname5_empty(self):
        input1 = self.ids.teamname.text
        if input1 == "":
            self.ids.teamname.helper_text_mode = "on_error"
            self.ids.teamname.helper_text = "Team name is required"
            self.ids.teamname.required = True
    def time_empty(self):
        input1 = self.ids.time.text
        if input1 == "":
            self.ids.time.helper_text_mode = "on_error"
            self.ids.time.helper_text = "Time is required"
            self.ids.time.required = True
    def player_empty(self):
        input1 = self.ids.player1.text
        if input1 == "":
            self.ids.player1.helper_text_mode = "on_error"
            self.ids.player1.helper_text = "Player is required"
            self.ids.player1.required = True

    def player2_empty(self):
        input1 = self.ids.player2.text
        if input1 == "":
            self.ids.player2.helper_text_mode = "on_error"
            self.ids.player2.helper_text = "Player is required"
            self.ids.player2.required = True

    def cancel(self):
        self.ids.teamname.text = ""
        self.ids.time.text = ""
        self.ids.player1.text = ""
        self.ids.player2.text = ""
        self.parent.current = "DetailsScreen"
        self.ids.teamname.required = False
        self.ids.player1.required = False
        self.ids.time.required = False
        self.ids.player2.required = False


class Project(MDApp):
    def build(self):
        return


test = Project()

test.run()
```
**Fig 26** This is the whole python file for my project 

```.kv
ScreenManager:
    LoginScreen:
        name: "LoginScreen"
    SignupScreen:
        name: "SignupScreen"
    HomeScreen:
        name: "HomeScreen"
    RecordScreen:
        name: "RecordScreen"
    RecordPScreen:
        name: "RecordPScreen"
    RecordSubScreen:
        name: "RecordSubScreen"
    DetailsScreen:
        name: "DetailsScreen"
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

<SignupScreen>:
    size: 500,500
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .8, .9
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y":.5}
        padding: dp(50)

        MDLabel:
            text: "Register"
            font_style: "H3"
            font_size: 20
            size_hint: 1, .1
            halign: "center"
            pos_hint: {"center_x": .5, "center_y":.5}

        MDTextField:
            id: uname
            hint_text: "Enter username"
            helper_text_mode: "on_error"
            helper_text: "Username is required"
            on_text: root.userid_empty()
            required: False


        MDTextField:
            id: emails
            hint_text: "Enter email"
            icon_left: "email"
            helper_text_mode: "on_error"
            on_text: root.email_empty()
            required: False

        MDTextField:
            id: passwd
            hint_text: "Enter password (more than 10 characters)"
            icon_left: "key"
            password: True
            helper_text_mode: "on_error"
            on_text: root.passwd_empty()
            required: False
        MDTextField:
            id: passwd2
            hint_text: "confirm password"
            icon_left: "key"
            password: True
            helper_text_mode: "on_error"
            helper_text: "Passsword does not match"
            on_text: root.passwd2_empty()
            required: False

        MDBoxLayout:
            size_hint: 1, .1

            MDRaisedButton:
                id: login
                text: "Submit"
                on_press: root.try_register()
                size_hint: .3, 1
                md_bg_color: "#fcbf49"
            MDLabel:
                size_hint: .3, 1
            MDRaisedButton:
                id: cancel
                text: "Cancel"
                on_press: root.cancel()
                size_hint: .3, 1
                md_bg_color: "#e63946"
        Widget:
            size_hint_y: None
            height: 100
<HomeScreen>:
    size: 700, 700
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDLabel:
        text: "Football record"
        font_size: 50
        size_hint: .2, .1
        halign: "center"
        pos_hint: {"center_x": .5, "center_y":.8}

    MDRaisedButton:
        text: "Record game?"
        size_hint: 0.2, .1
        halign: "center"
        pos_hint: {"center_x": .5, "center_y":.1}
        on_press: root.recordgame()

<RecordScreen>:
    size: 5000, 5000
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .8, 1
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y":.5}
        padding: dp(50)
        MDLabel:
            text: "Record game"
            size_hint: 1, .1
            halign: "center"
            pos_hint: {"center_x": .5, "center_y":.5}
        MDBoxLayout:
            orientation: "horizontal"
            size_hint: 1, .1
            MDTextField:
                id: Teamname1
                hint_text: "Enter Team 1 name"
                helper_text_mode: "on_error"
                on_text: root.teamname1_empty()
                required: False
            MDTextField:
                id: Teamname2
                hint_text: "Enter Team 2 name"
                helper_text_mode: "on_error"
                on_text: root.teamname2_empty()
                required: False
        MDBoxLayout:
            orientation: "horizontal"
            size_hint: 1, .1
            MDTextField:
                id: Score1
                hint_text: "Enter team 1 score"
                input_filter: "int"
                helper_text_mode: "on_error"
                on_text: root.score1_empty()
                required: False

            MDTextField:
                id: Score2
                hint_text: "Enter team 2 score"
                input_filter: "int"
                helper_text_mode: "on_error"
                on_text: root.score2_empty()
                required: False

        MDTextField:
            id: Location
            hint_text: "Location"
            size_hint: 1, .1
            helper_text_mode: "on_error"
            on_text: root.location_empty()
            required: False
        MDBoxLayout:
            orientation: "horizontal"
            size_hint: 1, .1
            MDTextField:
                id: day
                hint_text: "Day"
                input_filter: "int"
                max_text_length: 2
                helper_text_mode: "on_error"
                helper_text: "Day is not valid"
                on_text: root.day_empty()
                required: False
            MDTextField:
                id: month
                hint_text: "Month"
                input_filter: "int"
                max_text_length: 2
                helper_text_mode: "on_error"
                helper_text: "Month is not valid"
                required: False
                on_text: root.month_empty
            MDTextField:
                id: year
                hint_text: "Year"
                input_filter: "int"
                max_text_length: 4
                helper_text: "Year is not valid"
                on_text: root.year_empty
                required: False



        MDBoxLayout:
            orientation: "horizontal"
            size_hint: 1, .2
            MDRaisedButton:
                text: "Record game?"
                size_hint: 0.2, .7
                pos_hint: {"center_x": .25, "center_y":.75}
                on_press: root.submit()
            MDRaisedButton:
                text: "Cancel"
                size_hint: 0.2, .7
                pos_hint: {"center_x": .75, "center_y":.75}
                on_press: root.cancel()


<RecordPScreen>
    size: 500, 500
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .8, 1
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y":.5}
        padding: dp(50)
        MDTextField:
            id: teamname
            hint_text: "What team was it"
            helper_text_mode: "on_error"
            on_text: root.teamname5_empty()
            required: False
        MDTextField:
            id: time
            hint_text: "What time was the goal in minutes"
            input_filter: "int"
            max_text_length: 3
            helper_text_mode: "on_error"
            on_text: root.time_empty()
            required: False
        MDTextField:
            id: player
            hint_text: "Who scored the goal"
            helper_text_mode: "on_error"
            on_text: root.player_empty()
            required: False
        MDBoxLayout:
            orientation: "horizontal"
            halign: "center"
            pos_hint: {"center_x": .5, "center_y":.2}
            MDRaisedButton:
                id: cancel
                text: "Cancel"
                on_press: root.cancel()
            MDRaisedButton:
                id: record
                text: "Record"
                on_press: root.submit()

<RecordSubScreen>
    size: 500, 500
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .8, 1
        elevation: 2
        orientation: "vertical"
        pos_hint: {"center_x": .5, "center_y":.5}
        padding: dp(50)
        MDTextField:
            id: teamname
            hint_text: "What team was it"
            required: True
            helper_text_mode: "on_error"
            helper_text: "Team name is not valid"
            on_text: root.teamname5_empty()
            required: False

        MDTextField:
            id: time
            hint_text: "What time was the substitution in minutes"
            input_filter: "int"
            max_text_length: 3
            required: True
            helper_text_mode: "on_error"
            on_text: root.time_empty()
            required: False
        MDTextField:
            id: player1
            hint_text: "Player substituted in"
            required: True
            helper_text_mode: "on_error"
            on_text: root.player_empty()
            required: False
        MDTextField:
            id: player2
            hint_text: "Player substituted out"
            required: True
            helper_text_mode: "on_error"
            on_text: root.player2_empty()
            required: False
        MDBoxLayout:
            orientation: "horizontal"
            MDRaisedButton:
                id: cancel
                text: "Cancel"
                on_press: root.cancel()
            MDRaisedButton:
                id: record
                text: "Record"
                on_press: root.submit()

<DetailsScreen>
    size: 500, 500
    FitImage:
        source: "football_pic_project_3.jpeg"
    MDCard:
        size_hint: .8, .9
        pos_hint: {"center_x":.5, "center_y": .5}
        radius: 30, 0, 30, 0 #top left, top_right, bottom
        orientation: "vertical"
        MDBoxLayout:
            size_hint: 1, .2
            orientation: "vertical"
            MDLabel:
                id: teams
                text: "teams"
                size_hint: 1,.3
                halign: "center"
            MDLabel:
                id: location
                text: "Location"
                size_hint: 1, .3
                halign: "center"
            MDLabel:
                id: date
                text: "Date"
                size_hint: 1, .3
                halign: "center"
        MDLabel:
            size_hint: 1, .4
            halign: "center"
        MDBoxLayout:
            size_hint: .5, .2
            orientation: "vertical"
            halign: "center"
            pos_hint: {"center_x": .5, "center_y": .2}

            MDBoxLayout:
                orientation: "horizontal"

                MDRaisedButton:
                    id: "goals"
                    text: "Record goal?"
                    on_press: root.parent.current = "RecordPScreen"
                MDRaisedButton:
                    id: "substitutions"
                    text: "Record substitutions"
                    on_press: root.parent.current = "RecordSubScreen"

            MDRaisedButton:
                id: "back"
                text: "Back to home screen"
                halign: "center"
                on_press: root.back()
```
**Fig 27** This is my whole kivy file for my project
