# Moodle-Installation-and-Cofiguration
In this I will be sharing step by step procedure to install Learning Management System Platform "Moodle", further we will see how to configure site administration settings in moodle. 

What is Learning Management System?
>>A learning management system (LMS) is a software application for the administration, documentation, tracking, reporting, automation and delivery of educational courses, training programs, or learning and development programs.

What is Moodle?
>>Moodle is a free and open-source learning management system (LMS) written in PHP and distributed under the GNU General Public License. Developed on pedagogical principles, Moodle is used for blended learning, distance education, flipped classroom and other e-learning projects in schools, universities, workplaces and other sectors.

Why Moodle?
>>With customizable management features, it is used to create private websites with online courses for educators and trainers to achieve learning goals.Moodle allows for extending and tailoring learning environments using community-sourced plugins.

MOODLE stands for Modular Object Oriented Dynamic Learning Environment

Here are the steps to install moodle for the system with following specifications:

Ubuntu 16.04
Moodle Version: 3.7
MySQL Version: 5.6
PHP Version: 7.1
Apache2

Steps for installing Moodle:-

=> STEP 0 : Identify matching versions of PHP, Mysql 
    we have already mentioned the versions that we used, one can refer to following link for further updates 
    https://docs.moodle.org/dev/Moodle_3.7_release_notes

=> STEP 1 : Ubuntu setup
    Linux setup on any cloud or local platform

=> STEP 2 : Install Apache, MySQL,PHP

    For Apache2:
    >>$sudo apt install apache2
    
    For PHP:
    >>$sudo apt-get install software-properties-common
    >>$sudo add-apt-repository ppa:ondrej/php
    >>$sudo apt-get update
    >>$sudo apt-get install php7.1

    For Mysql:
    >>$ sudo add-apt-repository 'deb http://archive.ubuntu.com/ubuntu trusty universe' 
    >>$sudo apt-get update
    >>$sudo apt install mysql-server-5.6 mysql-client-5.6
    

