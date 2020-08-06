<b>Flask chatapp</b>

It is basically a chat app for the college students where they can chat on the specific room .

<b>Features:</b>
1. Students need to create the their own account with username ,email and password.
    Password are secured using hash function.
    Users with the same name is prohibited.
    The database is stored in mongodb of the creator.
2. Students can access their own chatrooms.
3. Notification is given when somebody enters or leaves the room to the other people present in the room
4. The conversation are not stored in database which helps the students to talk freely.


<b>Steps to run the project:</b>

1.create a new virtual environment for django.Use Python 3.6 and keep the virtual environment name as you prefer 

    conda create -n env_name python=3.6

2.Activate the environment 
  
    activate env_name

3.Set you intial directory as the root folder and install the requirements. 

     pip install -r requirements.txt

4.Run the below code in command prompt and use the url to access the website 

     python app.py
