
# Unit 3 project
![Title picture](https://github.com/KaiFig/Unit_3/blob/main/Project/football_pic_project_3.webp)


# Criteria A: Planning

## Problem definition
My client is an ISAK student who enjoys watching and playing footabll a lot. However, after he watches the game, he has no way of keeping a track record of it and it is tedious to have to look up the scores online. Additionally, the sources online do not hold all of the football matches he watches as he watches local teams that are not found on the internet.  

## Rationale for Proposed Solution
My proposed solution is to create a mobile app that enables my client to record these details by themselves. As it is saved on the app, the client would not have to look the games up using the internet. Additonally, the client will be able to record all the games that he wants, even those that are not found on the internet. This will enable the client to upload their own scores, with no reliance on internet sources, to produce the record that he wants. 

I will be using python as the primary coding language for a variety of reasons. First of all, it is a very flexible coding language and I can reuse some code that we have already made. Additionally, it is compatible with both KivyMD and SQLite, enabling me to meet the clients needs on the application. The final reason is that this is the only coding language that I am good at and using it will speed up the process much more compared to having to learn another language. 

For the GUI design, I will be using KivyMD. In the project I will be using it to act as the interface between the user and the actual software. The user will be able to send inputs through their keyboard and alter information on the actual application and the databases available to the user. This is of utmost importance in this project as without it, the user will not be able to look at the football match log.



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
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart1.jpg)
**Fig x** This is the first flowchart which shows the function for making sure the text inputs are not empty. This is important so that the user inputs all the data and doesn't forget about it
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart%202.jpg)
**Fig x** This shows the login page in the application. It takes the user inputs and checks them with the database called "my_application", specifically the table "users". This enables me to check if the user is legitimate and it also allows me to check the password with the hash to improve security 
![](https://github.com/KaiFig/Unit_3/blob/main/Project/Flowchart%203.jpg)
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
|17  | Create the timeline database   | This saves the inputs of the suer from the goal and substitution pages  | 30 min  | Mar 2 | C|
|18   | Show the timeline on the details page | For each game, the user is able to see a timeline of the substitutions and the goals  | 30 min  | Mar 3   | C | 
|19   | Fix kivy layout on each page  | The website looks much cleaner before and the user is able to have a better experience  | 2 hrs     | Mar 7 | C| 




| Instruction                        | Category     | Input example / code                               | Description                                                                                                        | Expected output                                                         | Success criteria |
|------------------------------------|--------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|------------------|
| Test registration system           | Unit testing | username, email, password, confirm password        | Save a new user to the database                                                                                    | Input is added to database "users", window is switched to main menu     | 1     |
| Test recording system              | Unit testing | Team name, score, date, location, player names  | It saves a match to a database  | Input is added to database "record", window is switched to the home screen  | 2, 3
| Test details screen               | Unit testing  | Click on the home screen checkboxes | It opens the details screen with more details  | The details screen is opened and the details of the game are all displayed with buttons to go back and forward   | 3 and 4


# Criteria C: Development


## Existing Tools

| Software/Development Tools | Coding Structure Tools          | Libraries      |
|----------------------------|---------------------------------|----------------|
| PyCharm                    | ORM                             | KivyMD Library |
| Relational databases       | Objects, attributes and methods | sqlite3        |
| SQLite                     | OOP structures (classes)        | datetime       |
| Python                     | Encryption                      |                |
| KivyMD                     | if statements                   |                |

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


