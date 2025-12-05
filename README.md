# Ex02 Time Table
## Date:30-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
slotexp3.html

<html>
    <head>
        <img src="logo.png" width="1000" height="150" align="center">
        <br><br>
    </head>
    <body align="center">
        <table border="3" align="center" cellspacing="3" cellpading="3" bgcolor="violet">
            <caption align="center"><h3>SLOT Timetable : R. Nithish Aaditiyaa (25011876)</h3></caption> 
            <tr align="center" bgcolor="lightgreen">
                <th>Time/Day</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="lightyellow">8 to 10</td>
               <td>Free Period </td>
                <td>Pyth</td>
                <td colspan="2">Free Period</td>
                <td>FWAD</td>
                <td>Free Period</td>

            </tr>
            <tr align="center">
               <td bgcolor="lightyellow">10 to 12</td>
                <td>Free Period</td>
                <td>CEng</td>
                <td>Pyth</td>
                <td>CEng</td>
                <td colspan="2">FWAD</td>
            </tr>
            <tr align="center">
                <td bgcolor="lightyellow">12 to 1</td>
                <td colspan ="6">LUNCH BREAK</td>
            </tr>
            <tr align="center">
                <td bgcolor="lightyellow">1 to 3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MentorMeet</td>
                <td>CEng</td>
                <td colspan="2">Free Period</td>
            </tr>
            <tr align="center">
               <td bgcolor="lightyellow">3 to 5</td>
                <td>Free Period</td>
                <td>Pyth</td>
                <td>Pyth</td>
                <td>Free Period</td>
                <td>Pyth</td>
                <td>CEng</td>
            </tr>
        </table>
        <table border="3" align="center" bgcolor="greenyellow">
            <captions align="center"><h3>Subject Names</h3></captions>
            <tr align="center">
                <th bgcolor="cyan">S.No</th>
                <th bgcolor="cyan">Subject Code</th>
                <th bgcolor="cyan">Subject Name</th>
            </tr>
            <tr align="center">
                <td bgcolor="red">1</td>
                <td>19AI301</td>
                <td>Python Programming (Pyth)</td>
            </tr>
            <tr align="center">
               <td bgcolor="red">2</td>
                <td>19EN101</td>
                <td>Communicative English (CEng)</td>
            <tr align="center">
                <td bgcolor="red">3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td> 
            <tr align="center">
                <td bgcolor="red">4</td>
                <td>ECA-M</td>
                <td>Mentor Meeting (MentorMeet)</td>
            </tr>    
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (151).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
