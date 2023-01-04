ACADEMIC MANAGEMENT SYSTEM (AMS): A SCHOOL MANAGEMENT SYSTEM

Most schools especially universities manage their daily operations using old versions of

software that enable the members of staff, lecturers as well as students. Out of experience

with our school management system, we realized that most school management software

does not meet the quality required by most private or public institutions that are supposed to

offer higher learning. By analyzing the current versions of the school management system,

we were able to develop a system that takes the interactions of the members of the school

much easier. We believe that the system we have developed can improve the efficacy of the

normal running of the school operations.

FRAMEWORK/ TECHNOLOGIES USED

\1. Laravel version 8. X (PHP)

\2. Bootstrap version 5. X (CSS)

\3. HTML 5

\4. Docker version 4. X

\5. XAMPP Control Panel version 3. X

WHAT’S NEW

The new school management system user interface/ user experience is improved significantly.

Both the User Interface and internal workflow of the software system integrate a much better

process and interface design making it more user-friendly.

FEATURES YET TO BE ADDED TO FUTURE DEVELOPMENTS

\1. Direct messaging

\2. Introducing financial integration to manage income and expenses.





\3. Supporting other languages such as Spanish, Chinese ….

\4. Integrating a more adaptable database

INSTALLATION GUIDE

REQUIREMENTS

\1. Laptop or desktop with equal to or more than 4GB RAM and 2.5 Megahertz

Microprocessor.

\2. Stable Internet connection.

HOW TO START THE SYSTEM(OFFLINE)

To begin with, ensure that you run Docker.

If you don’t have docker, [download](https://docs.docker.com/desktop/install/windows-install/)[ ](https://docs.docker.com/desktop/install/windows-install/)[and](https://docs.docker.com/desktop/install/windows-install/)[ ](https://docs.docker.com/desktop/install/windows-install/)[install](https://docs.docker.com/desktop/install/windows-install/)[ ](https://docs.docker.com/desktop/install/windows-install/)docker from the main distributor.

If you have docker installed correctly, you’ll get:

\1. Nginx

\2. PHP v7.X

\3. MYSQL v5.X

STEPS TO INSTALL

\1. Clone or downloa[d](https://github.com/George-Stephen/AMS_project)[ ](https://github.com/George-Stephen/AMS_project)[the](https://github.com/George-Stephen/AMS_project)[ ](https://github.com/George-Stephen/AMS_project)[repository](https://github.com/George-Stephen/AMS_project)

\2. Create a *purify* folder in storage/app/ directory.

\3. Run docker-compose up -d

\4. Afterward, docker exec -it db sh

\5. Inside the shell, run

a. MySQL -u root -p





b. The password is *your\_mysql\_root\_password* in the docker-composer. yaml

file

\6. Then run the following commands:

\7. Finally, exit the container by running the command *exit* on the container shell.

\8. Run docker exec -it app sh

\9. Install composer: *composer install*

\10. Generate a new application key: *php artisan key: generate*

\11. Create a configuration cache file enhancing the efficiency: *php artisan config: cache*


CONTRIBUTORS

\1. 138521 George Stephen Wangui

\2. 138930 Kiconco Cynthia

\3. 134196 Erastus Wachiuri

\4. 141710 Ronit Mepani

