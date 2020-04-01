# project-report
**29 March**
--

I'm very glad to do project with my teachers and my mates. Firstly what I have to do as told by my mentor is to do installation of **Moodle**. So for that I downloaded the **XAMPP** by which I can setup the php and mysql platform for the moodle app. And after that with help of xampp application I'm able to start moodle app. Our team took much time for installation because at time of execution there was timeout error while installing moodle application. I setup all the required things but when I load the webpage the starting steps was going very smoothly but when it reaches its last step to install all the database then the error comes that the setion was timeout I found that there was some site error but i was wrong. I set up the error by going to config in apache in xampp control panel, there I edited the time limit and extends it by which I was able to load the installation page. After that I used the bitnami moodle to create login and stated the app. And when the installation process was completed the happiness was ultimate for team and mentors. After installation the work assigned was to read the database for moodle application from php. And started understanding the database. The database having about 200+ table. The table I started was the course table. By which I able to understand how to add courses to my application.
***The main motive for our project is to get the attainment of each course outcome and then the attainment of final course, by which we can calculate the course attainment by the individual student.***

**30 March**
--

We are assigned to a task in which we have to check that if we make changes in our moodle app the what changes are made add the backend in phpmyadmin moodle tables <http://localhost/phpmyadmin/db_structure.php?server=1&db=bitnami_moodle> this link has moodle database in which we can see the changes. Firstly I created the user and assign myself as role of teacher. When users are enrolled then the I saw changes in table ***mdl_user*** at backend in this table 3 user are shown i.e student,teacher and guest user. And after that I created the course and enrolled teacher and student in the course. And the changes are shown in table ***mdl_course*** at backend. After course enrollment I firstly created the quiz in topic 1 and assigned to student. Then changes are shown in table ***mdl_quiz*** at backend. After assigning quiz when student attempt the quiz and changes are shown in table ***mdl_quiz_attempts*** at backend in which it shows the number of attempts. The quiz is automatically graded and that grades are shown in table ***mdl_quiz_grades*** at backend. I also created an assignment in my course and at backend the changes are shown in table ***mdl_assign***. After the submission from student side then change in table ***mdl_assign_submission*** was seen. And after that grades are awarded by teacher and changes are seen in table ***mdl_assign_grades*** in which grades are shown. 

**31 March**
--

No work done today.

**1 April**
--

Today our group has a dicussion session, in which our mentor Er.Satinder Sir guided us about the plugins. With ***plugins*** we can attach additional features to moodle application. With these plugins moodle application can be upgraded. So sir said us to plugin the ***game*** to our created course. So first we went to official site of moodle i.e <http://moodle.org>. Then from there I opened ***plugin***, there are numbers of plugins. From there I downloaded the ***game zip file***. Then went to my moodle and attached that plugin. After that when I clicked on add activity in my course, then there was column of game. So from that I can add the games like crossword,sudoku etc. After that I went to <http://localhost/phpmyadmin/db_structure.php?server=1&db=bitnami_moodle>, there I checked that a new database for the game was created. There was table named ***mdl_game***, which has the list of games and also there was database for game attempts,game grades etc.
