# COVER PAGE DESIGN USING HTML AND CSS
## AIM:
To design a website to create a webpage displaying the cover page of the book .

## DESIGN STEPS:
### Step 1:
Create a new Django project using "django-admin startproject",get into the project terminal and use "python3 manage.py startapp" command.

### Step 2:
Define urls.py and views.py for the website .Allow host access and add the app name under installed apps in settings.py

### Step 3:
Create a templates folder under the app folder followed by a folder under templates with the app name followed by html file named bookdesign.html

### Step 4:
Write HTML and CSS code in the file save it and run the app using python manage.py makemigrations and python manage.py migrate commands .Run the Server using "python3 manage.py runserver 0:80" command.

### STEP 5:-
The Website is published.We created a webpage displaying the cover page of the book .

## Code:

<!DOCTYPE html>
<html>
    <head>
        <title>BOOK COVER</title>
        <style>
        h1{
            color:#e36f2f;
        }
         .bookpage{
             width: 450px;
             height: 750px;

             margin-left : auto ;
             margin-right : auto ;
             padding: 20px ;
             background-image : url('/static/images/edited.jpg');
             background-size: cover;
             background-repeat: no-repeat;
         }
         .toptext {
             color:rgb(236, 207, 186);
             padding-left : 5px;
             font-size :14px;
             font-family : Arial, Helvetica, sans-serif;
         }
         .tophr{
             color: azure;
             width:180px;
         }
         hr{
             color:bisque;
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 10px 10px;
             display: flex;
             align-items: center;
             justify-content: center;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 30px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
              font-size: 24px;
              
             
         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
              display: flex;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 20px;
              }
  
         .footer {
  
              padding-top: 10px;
              padding-bottom: 90px;
            }
        .image {
              color:white;
              font-family: Arial, Helvetica, sans-serif;
              font-size: 22px;
              margin-right: 20px;
            }
         .bottomhr { 
              color:#f8ede7;
              width: 450px;
              height:20px;

            }
        img {
            width: 190px;
             height: 190px;
             margin-right: 50px;
             vertical-align: bottom;
            }
         .edition {
             color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
             font-size: 22px;
            line-height: 20px;
            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">BEST SELLER</div>
            <div class="tophr"><hr></div>
     

        <div class="booktitle">
            <h1>SHINGEKI NO KYOJIN</h1>
        </div>

        <h3 class="sub-text">THE DAY ..</h3>
        <h3 class="sub-text">WHEN HUMANITY RECEIVED... </h3>
        <h3 class="sub-text">A GRIM REMAINDER ...</h3>

        <div class ="footer">
            <h2 class="edition">THIRD EDITION&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="/static/images/isayama.jfif"  alt="author img"></h2>
            <div class="bottomhr"><hr></div>
            <div class="author"><h3>HAJIME ISAYAMA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;packt></h3></div>
        </div>
       </div>
    </body>
</html>


## Output:
### Book Cover :
![Screenshot (26)](https://user-images.githubusercontent.com/119288183/213932530-c46e9b37-3dd2-48ad-8e9e-194bcd89a6c4.png)



## Result:
Successfully designed a website to display the cover page of the book .
