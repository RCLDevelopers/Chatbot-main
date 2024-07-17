# Chatbot
Cloud based Student Information Chatbot system.:     Functionality which the chatbot should have in this project :     Here are some Details:     A Student bot project is built using artificial algorithms that analyzes user’s queries and understand user’s message. This System is a  web application which provides answer to the query of the student. Students just have to query through the bot which is used for chatting. Students can chat using any format there is no specific format the user has to follow. The System uses built in artificial intelligence to answer the query. The answers are appropriate what the user queries. If the answer is found to invalid, user just need to select the invalid answer button which will notify the  admin about the incorrect answer.     Admin can view invalid answer through portal via login. System allows admin to delete the invalid answer or to add a specific answer of that equivalent question.     The User can query any college related activities through the system. The user does not have to personally go to the college for enquiry. The System analyzes the question and then answers to the user. The system answers to the query as if it is answered by the person.     With the help of artificial intelligence, the system answers the query asked by the students. The system replies using an effective Graphical user interface which implies that as if a real person is talking to the user. The user can query about the college related activities through online with the help of this web application.This system helps the student to be updated about the college activities.     For making it cloud based, deploy your web application integrated with AI in cloud platform. You can use any cloud platform AWS, GCP, Heroku etc.


1. Login to AWS Account and then head to Management Console.
2. From Services, Click on EC2.
3. Click on 'Launch Instance'.
4. Select AMI(microsoft windows server 2019 base).
5. keep t2.micro as default and Click on Configure.
6. Do not make changes to Instance-details, click Next
7. Do not add any extra storage(30Gib already provided by default)>>Next
8. In Configure Security group,
a.Click on create new security group
b.rename Security group name(recommended)
c.Keep Rdp as it is and add two more roles as http and https.
d.Choose protocol as TCP.
9. Click on review and launch >>launch
10. choose a key pair(use existing recommended).
11. Click 'win+R' on keyboard or open Run terminal and write 'mstsc' , click ok.
12. Enter your Public IPV4 address ,click connect.
13. click on more choices and then use a different account.
14. Now go to the running instance dashboard and click on connect.
15. Browse your .pem file and decrypt the password.
16. your default username will be 'Administrator'.
17. Enter your username and password obtained in (step 13 field).
18. click on yes and wait until remote connection becomes available (Wait 4-6min Recommended)
"Inside Vm"
19. Now click on windows and search for a firewall on Remote desktop only.
20. Choose and click the windows defender firewall.
21. On left of what opens click 'Turn windows defender firewall on or off',Turn both of them off.
22. Install chrome and XAMPP on your Vm.
23. while installing Xampp have patience ,don't make any changes,let it get installed properly.
24. Now when you write 'localhost' on your vm browser you will get a xampp dashboard.(this means
you are on the right track).
25. Goto C>>XAMPP>>htdocs on your Remote desktop only.
26. delete index.php and paste all your files there which you'll copy from your original System.
27. Create your database using 'localhost/dashboard' (phpmyadmin), and refresh your localhost
tab.
28. Now you are done, when you will share your instance ip to anyone and if they browse it,they will get the
website which you hosted on a remote desktop.
29. Do not forget to stop your instance once your work is paused.
30. Delete the security group as soon as you terminate your instance.
You have successfully hosted a php web server using cloud(AWS).
Cheers !