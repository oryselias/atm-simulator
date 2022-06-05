# java-project





SETTING UP DATABASE
1.The user needs to have a MySQL environment set up. The database changes that our project makes are reflected on a table which is present in a Mysql Database.

2. In the workbench the user needs to create a schema named - grp_project. The schema should have a table named -cards.

3.To effectively run the code the user needs to have a table like this one:-

Note that the column names should be identical, else the code will definitely throw an error.

4. Once you have the table set up change the password of the JDBC connection statements in the code ( search for the password in your code ),to your own sql environment’s password. If this is not done you will encounter and SQL exception.

5.Once you make these changes and set up your table like this you can run the code effectively from the Main.java file. Make sure you make at least ONE entry before you run our code.  This is because our code needs a card number to begin with.


NOTE: PLEASE REFER TO 'project description.pdf' FILE TO UNDERSTAND THINGS BETTER.




RUNNING THE CODE:

6.Download the zippedCodeFiles.zip

7.To run the code, you must run the 'main.java' file which is in the IIITLBank/main.java
You will be given a couple of choices for login(card login, cardless login).

8.You need to run the client.java on a second terminal to get the otp if you chose cardless login in the previous step. You also need to enter the PIN number of your card. (2 factor authentication)

9.If you successfully enter the correct information, you’ll be logged in and given a list of transactions to choose from.

10.Now carry out the transactions peacefully :)
You need to enter the pin everytime to carry out a transaction.
NOTE:
You need to be careful while entering the PIN as three incorrect pin entries will result in the blockage of card for the next 24 hours.

11. Once the transaction is complete you will receive an email to your registered email account saying the transaction was a success!!

12.You can logout of your account by selecting ‘log out’ option and terminate the program.
