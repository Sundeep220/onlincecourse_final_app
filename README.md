
**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.


- Before running this project: 

  -> Create a virtual environment, in Windows command is as follows: \
    `pythom -m venv env` \
   -> To activate: \
     `env/Scripts/activate`

- To run this project do the following:

    Pre-requisites: Python, pip and django should be installed in your system. All the coding is done using VScode.
    1. To install the dependencies: \
       `pip install -r requirements.txt` 
    2. Make the migrations:\
        `python manage.py makemigrations` 
    3. Migrate the tables: \
        `python manage.py migrate` 
    4. Create a superuser for your project: \
        `python manage.py createsuperuser`   
        This will prompt you to enter username, email and password for the superuser.  
    5. Run the server using: \
        `python manage.py runserver`



**ER Diagram**

For your reference, here is a E-R diagram of the application.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)



**Home Page**


![home](https://user-images.githubusercontent.com/93663329/206862514-d09b2abf-a1a9-4e24-9db6-c00e6e5ee16d.png)



**About US**


![aboutus](https://user-images.githubusercontent.com/93663329/206862531-cab0cc92-edab-4f03-a360-9e619f9f95f8.png)


**Course Details Page**


![coursedetails](https://user-images.githubusercontent.com/93663329/206862592-af7af30f-530a-472f-aea4-d66815a165ed.png)





