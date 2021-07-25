Herre I created a RESTful API which can be used to create and delete user records. 

Responses to the questions asked are shown in my E-portfolio and below. 

Question 1: Run the API.py code. Take a screenshot of the terminal output. What command did you use to compile and run the code?
When running the code through pycharm and following the command prompt within the terminal I received the following error messages, that the URL was not found, with an error status of 404.  When using pylint to look at the code further I realised that there is an error within the coding which is causing issues the coding needs to be fixed , the coding below shows the fixed coding. The user needed to be defined as a string. 

Question 2:Run the following command at the terminal prompt: w3m http://127.0.0.1:5000/user/Ann
What happens when this command is run, and why?
The user information for Ann is returned as this command has the get function returning Ann’s information from the list. This is the get function. 

Question 3: Run the following command at the terminal prompt: w3m http://127.0.0.1:5000/user/Adam
What happens when this command is run, and why?
There is no user listed as Adam so the result is user not found as they have not been put into the list. This is that the put function has not been used to place the users details into the database therefore when this command is run the response is null as there is no user found. 


Question 4: What capability is achieved by the flask library?
