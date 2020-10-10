# autoSendEmail
Upload a csv file and it will read the all the email id and it will send email automatically. And it will send email to admin after 30 minute. 

Step to run the project. 
1. download the project
2. open the terminal and go to the directory where you downloaded the file. 
3. after going to ara folder(where you will see only venv and emailproject) run the following command to run the project
 a. source venv/bin/activate
 b if you are able to see (venv) prefix in the terminal then you are on the right path to run the project. You have successfully activated the virtual environment. 
4. Run the following command to install all the requirement for this project. 
4.a. $pip3 install -r requirements.txt. # it will download all the requirements from requirement.txt file
5. Start the server by following command. 
 a. Pyhton3 manage.py runserver. 
6. copy the url paste it in the browser. 
7. You will seeing the website is loading then you can give the emailID, CCEmailId, BCCEMailID, subject, email body and you can upload the csv file. 
8. It will trigger mail to your given email id. After that it will read the email from csv file and send the mail one by one.
9. You will get the email by sumit testing. 
10. after 30 min it will auto trigger the mail to admin. 
Steps to run the background task. 
Follow the same steps upto 3.b then run the below command
python3 manage.py run background_tasks

