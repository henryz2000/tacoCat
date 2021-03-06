# TacoCat
#### Gordon Lei, Henry Zheng, Angelica Zverovich<br>SoftDev1 pd8<br>Project0 -- Tell me a story... or write about it

A collaborative storytelling game/website.

## Dependencies
* `from flask: Flask, render_template, request, session, redirect, url_for, flash`
* `os`
* `sqlite3`
* `hashlib`
* `python2.7`

## File Structure
```
static/
  images/
   |  tacoCat.png
   |  tacoCatCursor.png
  styles/
   |  style.css
templates/
 |  base.html
 |  create_story.html
 |  display.html
 |  edit_story.html
 |  list.html
 |  login.html
 |  register.html
 |  welcome.html
README.md
changes.txt
db_builder.py
design.pdf
devlog.txt
log.sh
login.py
```

## Launch Instructions
    
1. Enter your terminal and go into the directory that you want to have this game in
2. Enter this command to clone our repo
```
git clone https://github.com/henryz2000/tacoCat.git
```
3. Run your virtualenv from whereever you have it
```
. <PATH_TO_VIRTUALENV>/bin/activate
```
4. Go into the tacoCat folder using this command
```
cd tacoCat/
```
5. Run the program
```
python login.py
```
6. Go to localhost:5000 in your web browser and enjoy the site!
