# -Cricket-World-Cup-Management-System
A database management system using MYSQL for cricket world cup with GUI( Graphical user interface developed using Python and Qt designer) to store, retrieve, update and delete the data of respective teams and their matches played.
PREREQUISITES :
1.	DB BROWSER(SQLITE) AND CREATE TABLES .
https://download.sqlitebrowser.org/DB.Browser.for.SQLite-3.12.2-win64.msi
2.	INSTALLED  PYTHON
3.	INSTALLED VSCODE EDITOR
4.	SQLITE PACKAGES CONNECTING VISUAL STUDIO (MY CASE)
https://www.sqlite.org/2021/sqlite-tools-win32-x86-3350500.zip
5.	QT5 DESIGNER (FOR DESIGNING GUI )	
https://build-system.fman.io/qt-designer-download


## STEPS TO BE FOLLOWED:
Step 1: Extract the given zip folder.<br />
Step 2 : Open Visual Studio.<br />
Step 3: Click on Open folder.<br />

![image](https://user-images.githubusercontent.com/59958361/176100438-b3fde2ee-0f4b-44ac-b192-4a0b1a1d44e1.png)

Step 4: Select the GUI folder inside the folder that you got after extracting given zip file.

![image](https://user-images.githubusercontent.com/59958361/176103982-88dc4339-2345-4556-862d-69a0457e0b11.png)

Step 5: Search final2.py file and open it.

![image](https://user-images.githubusercontent.com/59958361/176104021-a37faab2-a89f-42ed-b541-6db06fcf6256.png)

Step 6: Run the code (as shown below).

![image](https://user-images.githubusercontent.com/59958361/176104065-119b3647-d218-41e1-a1b6-d9b0945560f4.png)

Step 7 : The following window will open. Icons may or may not be displayed.

![image](https://user-images.githubusercontent.com/59958361/176104107-dc45d8bf-7e30-4176-9c9a-a1b22c89623e.png)

1.USER (Get information about World cup teams, players, matches etc)
1.1 : To get Teams information go to Teams tab<br />
•	If you are a normal user you can get all details about Worldcup in the USER tab. 

![image](https://user-images.githubusercontent.com/59958361/176104150-3c788ac6-2be8-47c2-8d6f-292d796cd9e9.png)

•	You can click on each team icon to get that particular team details.

![image](https://user-images.githubusercontent.com/59958361/176104312-ba335eb7-c1ec-4291-a4d6-305c05413e58.png)

•	You can click on All teams to get info of all teams.

![image](https://user-images.githubusercontent.com/59958361/176104361-748db21b-3d52-41d4-b6e7-d99de3fd835f.png)

1.2 : To get player info open Player tab<br />
•	In player tab you can enter team Id and get all players by clicking All players,
Batsmen and Bowlers of a particular team.

![image](https://user-images.githubusercontent.com/59958361/176104441-10525cf0-5e14-44a6-a60f-1ef6a6d6f735.png)
![image](https://user-images.githubusercontent.com/59958361/176104458-38604c07-acb8-4737-ae5f-6d8628524f30.png)
![image](https://user-images.githubusercontent.com/59958361/176104481-6b55045d-500f-4170-839b-87fdb6a28294.png)

•	Get details of your favourite player by searching his name.

![image](https://user-images.githubusercontent.com/59958361/176104536-785fdb4b-0977-48ab-9476-ea5c47e4a56f.png)

•	Get Top 10 batsmen of the tournament by clicking top 10 batsmen button.

![image](https://user-images.githubusercontent.com/59958361/176104565-697eeab9-895e-4f3f-b971-65cb031a37b0.png)

•	Top 10 bowlers of the tournament by clicking top 10 batsmen button.

![image](https://user-images.githubusercontent.com/59958361/176104612-ab68c610-4620-44cb-b67b-52b20d3e840c.png)

1.3 : To get info about matches open Matches tab<br />
•	Get info of all matches by clicking display all matches.

![image](https://user-images.githubusercontent.com/59958361/176104658-24683a25-3e5f-4b14-a091-f29b3fdcb65a.png)

•	Search your favorite team to check the information of matches and its result.

![image](https://user-images.githubusercontent.com/59958361/176104691-b9ccfe0e-796b-4a03-b276-3979e929b4fc.png)

•	Get match details of a specific date.

![image](https://user-images.githubusercontent.com/59958361/176104722-d0f766d9-be3c-495a-890b-0a708bbfbc1f.png)

1.4 :  To get captain, stadiums, coaches, umpires info open Other Info tab<br />

•	click Display all captains  to get info of captains of all teams.

![image](https://user-images.githubusercontent.com/59958361/176104765-a92c949a-5374-4643-bf74-ee466d958e08.png)

•	Click Display all coaches to get all coaches info.
 ![image](https://user-images.githubusercontent.com/59958361/176105034-49e91a21-15ea-4802-8438-009baf71b6b1.png)


•	Click Display umpire mapping to matches to get umpires allocated to all matches.

![image](https://user-images.githubusercontent.com/59958361/176105071-bb67b94e-74c7-43e1-9547-df173dfec520.png)

•	Click Display all umpires to get all umpire’s info.

![image](https://user-images.githubusercontent.com/59958361/176105085-a520aea0-eaa5-4cf3-be5b-09a7f2ddda40.png)

•	Click Display all Stadiums to get all stadiums info where worldcup matches are going to occur.
 
![image](https://user-images.githubusercontent.com/59958361/176105115-a42a7a69-b956-4465-89b4-ecfa91b68df9.png)


2.ADMIN<br />
•	If you are admin enter your username(vikram) and password( vikky625 ) and click Login. <br />
•	Another window will open where all the admin activities can be done.
 
 ![image](https://user-images.githubusercontent.com/59958361/176105143-1f07c3a1-0c3f-42a9-b081-9c5d4ff5204e.png)


2.1 :  To schedule matches and update result go to SCHEDULE MATCHES tab<br />
•	To schedule a match enter Team ids of both teams ,the date and time of match ,it’s venue(stadium) and 3 umpires who will umpire the matches<br />
•	Then click schedule. A confirmation message is displayed with match number<br />
Click ok.

![image](https://user-images.githubusercontent.com/59958361/176105239-f7ded274-81cd-43e8-ba9c-6583bb314d16.png)

•	To reschedule a match enter Match ID and date and time and click reschedule.
 ![image](https://user-images.githubusercontent.com/59958361/176105263-d54fc04f-866d-483b-83ea-dbcdb762d156.png)

•	To cancel the match enter Match ID and click cancel. 
![image](https://user-images.githubusercontent.com/59958361/176105340-34f3bbac-3c75-4640-a8f0-3771278d8223.png)

•	To update the result of a match enter it’s match ID if it is draw click on update match draw button. Otherwise enter winner team ID . Select whether they won match by wickets or runs select respective button.<br />
•	Enter number of wickets or runs in Won by wickets or runs.<br />
•	Click update. The result will be updated.
![image](https://user-images.githubusercontent.com/59958361/176105403-cc1bb6db-0ad2-4e0b-aa1b-d02164a6ab3d.png)
 
2.2 : To disqualify a player or a team go to Go to DISQUALIFY tab<br />
•	Enter Player ID and click Go (that player will be disqualified).
 ![image](https://user-images.githubusercontent.com/59958361/176105436-b3184169-66d2-40fc-948a-9d641c35355f.png)

•	Enter Team ID and click Go (that team will be disqualified).

![image](https://user-images.githubusercontent.com/59958361/176105455-21581c37-16d8-46d2-8a92-7360c8f2a7db.png)

2.3 : To add, update or delete  teams or players go to MODIFYDATA1 tab<br />

•	To add to, update or delete data from database.<br />
•	Enter the new values of new record to be added and click insert.<br />
•	A message box will be displayerd and your data will be saved.<br />

![image](https://user-images.githubusercontent.com/59958361/176105497-1c80b606-6cb5-46fe-8752-6ecb695f24b6.png)

•	You can also update any table data by entering updated values and click update.
![image](https://user-images.githubusercontent.com/59958361/176105516-768c906b-5c25-42fa-977c-4292e328ea7e.png)

•	To delete a team Enter a TeamID and click delete.<br />
•	A message box will be displayed and your data will be deleted.
 
![image](https://user-images.githubusercontent.com/59958361/176105539-aa76a7d5-71aa-4630-abe8-25655978fc42.png)

Like this batsmen,  bowlers data can also be added modified or deleted.<br />

2.4 : To add, update or delete captains, coaches, umpire, stadium go to MODIFYDAT2 tab<br />
•	Here captains, stadiums, coaches, umpire data can be added modified or deleted like same way you have done while adding, deleting, updating Team data in previous tab.
