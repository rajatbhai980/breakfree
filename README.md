<div align="center">

# BreakFree
This is a Habit Tracker website where you can add friends, make room and count days for anything you like. I am building this project because the leaderboard system with your friends who have similars goals can increase everyones determination and make it more videogame like sense of satisfaction. 
</div>

<div style="text-align: center;">
    <p>Profile</p>
    <img src="Rimages/profile.png" style="width: 80%; height: auto; display: block; margin: 0 auto;">
</div>

<div style="text-align: center;">
    <p>Add Friend</p>
    <img src="Rimages/add_friend.png" style="width: 80%; height: auto; display: block; margin: 0 auto;">
</div>

<div style="text-align: center;">
    <p>Create Room</p>
    <img src="Rimages/create_room.png" style="width: 80%; height: auto; display: block; margin: 0 auto;">
</div>

<div style="text-align: center;">
    <p>Room</p>
    <img src="Rimages/room.png" style="width: 80%; height: auto; display: block; margin: 0 auto;">
</div>

<p>
This is a django full stack app with no seperate frontend and now it's deployed on https://breakfree-production-c468.up.railway.app/ 
The base folder has the enter app in it. it's the only app in this project. 
Its dockerized and and has no additional containers, I have used the default sqlite as database.
It uses gunicorn for webserver but i used whitenoise to serve static files instead of nginx to reduce complexity and quick deployment 
</p>

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/rajatbhai980/breakfree.git

```

--> Move into the directory where we have the project files : 
```bash
cd breakfree

```

--> Activate the virtual environment(You need to activate the virtual environment each time you restart the IDE) :
```bash
env\scripts\activate

```
 

#

### Running the App

--> To run the App, we use :
```bash
python manage.py runserver

```

> ⚠ Then, the development server will be started at http://127.0.0.1:8000/

#
