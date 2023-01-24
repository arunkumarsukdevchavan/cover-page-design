# Book CoverPage Design

## AIM:

To design a static web site for a book cover page.

## DESIGN STEPS:

### Step 1:
<<<<<<< HEAD Create a new Django project using "django-admin startproject",get into the project terminal and use "python3 manage.py startapp" command.


### Step 2:
Define urls.py and views.py for the website .Allow host access and add the app name under installed apps in settings.py

### Step 3:
Create a templates folder under the app folder followed by a folder under templates with the app name followed by html file named bookdesign.html


### Step 4:
Write HTML and CSS code in the file save it and run the app using python manage.py makemigrations and python manage.py migrate commands .Run the Server using "python3 manage.py runserver 0:80" command.


### Step 5:
The Website is published.We created a webpage displaying the cover page of the book "Responsive Web Design with HTML5 and CSS".



## PROGRAM :
```python
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(https://i.pinimg.com/564x/f4/83/42/f4834227774b57dea6c70c68b71cb9ae.jpg);
            background-size:600px;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: goldenrod;
            display: inline;
            position: relative;
            color:lightgoldenrodyellow;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: large;
            position: relative;
            top:40px;
            color:whitesmoke;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: orange;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof  responsive  websites  using  the  latest  HTML5  and  CSS  Techniques
            </div>
            <div>
        
            <div class="photo">
                <img src="https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/d8b1ae77-d6d7-4ea4-b1c7-3610213b57ea/ben-frain-200x200.jpg" width="130" height="145" alt="ben">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>ARUN KUMAR SUKDEV CHAVAN</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>THIRD EDITION</b>
            </div>
            
        </div>
    </body>
</html>
```

## OUTPUT:
![output](/coverpage.png)

## HTML VALIDATOR:
![output](/htmlv.png)

## Result:
Successfully designed a website to display the cover page of the book "Responsive Web Design with HTML5 and CSS".
