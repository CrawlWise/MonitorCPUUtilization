# MonitorCPUUtilization
This project monitor CPU utilization running on your computer and send a mail to you 

this code makes use of the following module
- psutil: This is responsible for getting access to the cpu count
- platform: This fetches information about my computer and output it to the console.
- Email.message: This is used to send a message to the receiver.

# Setting up the gmail smtp
1. Login to https://myaccount.google.com/apppasswords. Note: For this to work, you must make sure your 2 steps-verifcation is turn on.
2. Create a password that the python script will use to send the mail. See image below
![image](https://github.com/CrawlWise/MonitorCPUUtilization/assets/126500329/cafbaf29-6a96-459d-a207-fad955f111c3)
3. Once the password is created, you can use it in your script to send message.
Note: This password have the same privileges with your normal gmail account. 

