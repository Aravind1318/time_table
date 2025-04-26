# Ex03 Time Table
# Date:
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
    <head>
       <title > <b> SLOT TIMETABLE - DEEPAK(24901065)</b></title>
        <style>
           
            table,tr,th,td{
                border:5px solid black;border-collapse: collapse;
                text-align: center;

            }
            table.center{
                margin-left: auto;
                margin-right: auto;
            }
            h1,h2,h3,p{
                text-align: center;
            }
            
            

        </style>
    </head>
    <body>
        <p style="text-align: center;">
        <img src="C:\Users\admin\Downloads\picture\image.jpeg" alt="Not found">
        </p>
        <h3> <b> SLOT TIMETABLE - ARAVIND P(24000784)</b></h1>
        
        <table  width = "70px" class ="center">
        <tr>
            <th bgcolor = "yellow">Day/Time</th>
            <th bgcolor = "yellow">Monday</th>
            <th bgcolor = "yellow">Tuesday</th>
            <th bgcolor = "yellow">Wednesday</th>
            <th bgcolor = "yellow">Thursday</th>
            <th bgcolor = "yellow">Friday</th>
            <th bgcolor = "yellow">Saturday</th>
        </tr>
        <tr>
            <th bgcolor = "yellow">8 - 10</th>
            <td  bgcolor="aqua"colspan = "2"> English</td>
            <td bgcolor="aqua"> Free</td>
            <td bgcolor="aqua">Machine Learning</td>
            <td bgcolor="aqua"> C-programming</td>
            <td bgcolor="aqua"> C-programming</td>
            <td bgcolor="aqua"> Free</td>
        </tr>
        <tr>
            <th bgcolor = "yellow"> 10 - 12</th>
            <td bgcolor="aqua">Reasoning Ability</td>
            <td bgcolor="aqua"> Web Development</td>
            <td bgcolor="aqua"> Maths for ai</td>
            <td bgcolor="aqua"> Probability</td>
            <td bgcolor="aqua">Game programmming</td>
            <td bgcolor="aqua"> Probability</td>

        </tr>
        <tr>
            <th bgcolor = "yellow"> 12 - 1</th>
            <td  bgcolor="aqua"colspan = "6"> Lunch</td>
        </tr>
        <tr>
             <th bgcolor = "yellow">1-3</th>
             <td bgcolor="aqua">Maths for AI</td>
             <td bgcolor="aqua"> Free</td>
             <td bgcolor="aqua"> Mentor meet</td>
             <td bgcolor="aqua"> Game programmming</td>
             <td bgcolor="aqua"> Maths for AI</td>
             <td bgcolor="aqua"> Web Development</td>
        </tr>
        <tr>
            <th bgcolor = "yellow">3-5</th>
            <td bgcolor="aqua">Machine Learning</td>
            <td bgcolor="aqua"> Free</td>
            <td bgcolor="aqua"> Free</td>
            <td bgcolor="aqua"> Free</td>
            <td bgcolor="aqua"> Free</td>
            <td bgcolor="aqua"> English</td>
        </tr>
        </table>
        <h2> Subject Name and Code</h2>
        <table class = "center">
            <tr>
            <th> S.No</th>
            <th> Subject Code</th>
            <th> Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td> 19AI414 </td>
                <td> Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EY709</td>
                <td> Reasoning Ability</td>
            </tr>
            <tr>
                <td> 3.</td>
                <td> 19AI410</td>
                <td> Machine Learning</td>
            </tr>
            <tr>
            <td> 4.</td>
            <td> 19MA220</td>
            <td> Probability</td>
            </tr>
            <tr>
                <td> 5.</td>
                <td>19AI200</td>
                <td> MAths for AI</td>
            </tr>
            <tr>
                <td> 6.</td>
                <td> 19en701</td>
                <td> English</td>
            </tr>
            <tr>
                <td> 7.</td>
                <td> 19ai510</td>
                <td> Game Programming</td>
            </tr>

        </table>
        </body>
        </html>
```
# OUTPUT

![image](https://github.com/user-attachments/assets/c2955468-dd32-4716-9f40-4ee647274787)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
