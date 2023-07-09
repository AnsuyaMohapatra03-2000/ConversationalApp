### Project Name
-----------------
Cipher - Conversational Apps Integration with the core products using any technologies.

### Project Overview
----------------------------------

This project involves building an end-to-end user flexible conversational app pertaining to a business domain which includes tasks such as fetching details from database, doing some specific actions based on input queries and also creating some user friendly interface with the app. To fulfill the requirements, the proposed code uses various packages, modules etc. Not only the functions but also the design of the algorithm is based on how to deal with the inputs in producing required outputs in efficient way possible.


### Solution Description
----------------------------------

The solution we proposed is based on the Manager-Employee domain that assists managers in performing the day-to-day activities effortlessly using a voice assistant that helps him/her in fetching any necessary information about the employees. Our voice assistant also provides the facility of obtaining information online as well as sending emails to the target email id with ease. We also designed another conversation assistant in Voiceflow that gets integrated into a person's Google Account and lets him/her fetch and update details of the employees that are stored in the Airtable database.

#### Architecture Diagram

Affix an image of the flow diagram/architecture diagram of the solution


#### Technical Description

Tech-Stack -- HTML,CSS,Bootstrap,JS,Ajax,Django,Python,Postgresql
Setup Required -- python,psycopg2,postgresql,pgadmin4,django
Instructions --  <br />
1.Download the project  <br />
2.Install python  <br />
3.Install pip  <br />
4.Install postgresql & pgAdmin4  <br />
5.Run the following commands in prompt-  <br />
    pip install django  <br />
    pip install psycopg2  <br />
    python manage.py collectstatic  <br />
    python manage.py makemigrations  <br />
    python manage.py migrate  <br />
    python manage.py sqlmigrate home 0001  <br />
    python manage.py sqlmigrate chat 0001  <br />
    python manage.py runserver  <br />
    pip install word2number
    pip install spacy
    pip install re
    python -m spacy download en_core_web_sm
    pip install chatterbot

