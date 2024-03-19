# Ex03 Time Table
## Date:14/03/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```<html>
    <head>
        <title> MY Time Tables</title>
        <body>
            <center><img src="logo.png"height="200" width="1200"</center>
            <h1>
                <center>SLOT TIMETABLE - Aaron (23008897)</center>
            </h1>    
            <table border="2" cellspacing="5" cellspacing="5" width="1200" height="70">
                
                <tr>
                    <th bgcolor="green">Day/Time</th>
                    <th bgcolor="green">Monday</th>
                    <th bgcolor="green">Tuesday</th>
                    <th bgcolor="green">Wednesday</th>
                    <th bgcolor="green">Thursday</th>
                    <th bgcolor="green">Friday</th>
                    <th bgcolor="green">Saturday</th>
                </tr>
                <tr>
                    <th bgcolor="red">8-10</th>
                    <th bgcolor="yellow">Phy</th>
                    <th bgcolor="yellow">web</th>
                    <th bgcolor="yellow">Data Science</th>
                    <th bgcolor="yellow">math</th>
                    <th bgcolor="yellow">Creative skill</th>
                    <th bgcolor="yellow">Digital</th>
                    
                </tr>
                <tr>
                    <th bgcolor="red">10-12</th>
                    <th bgcolor="yellow">crestive skill</th>
                    <th bgcolor="yellow">DIgital</th>
                    <th bgcolor="yellow">phy</th>
                    <th bgcolor="yellow">OS</th>
                    <th bgcolor="yellow">web</th>
                    <th bgcolor="yellow">math</th>
                </tr>
                <tr>
                    <th bgcolor="red">12-1</th>
                    <th bgcolor="yellow">Lunch</th>
                    <th bgcolor="yellow">Lunch</th>
                    <th bgcolor="yellow">Lunch</th>
                    <th bgcolor="yellow">Lunch</th>
                    <th bgcolor="yellow">Lunch</th>
                    <th bgcolor="yellow">Lunch</th>
                </tr>
                <tr>
                    <th bgcolor="red">1-3</th>
                    <th bgcolor="yellow">Math</th>
                    <th bgcolor="yellow">Web</th>
                    <th bgcolor="yellow">OS</th>
                    <th bgcolor="yellow">Phy</th>
                    <th bgcolor="yellow">Digital</th>
                    <th bgcolor="yellow">Creative skill</th>
                </tr>
                <tr>
                    <th bgcolor="red">3-5</th>
                    <th bgcolor="yellow">Free slot</th>
                    <th bgcolor="yellow">OS</th>
                    <th bgcolor="yellow">Math</th>
                    <th bgcolor="yellow">Creative skill</th>
                    <th bgcolor="yellow">Free slot</th>
                    <th bgcolor="yellow">Free slot</th>
                </tr>
            </table>
        </body>
    </head>
</html>
</table>
<hr>
<table border="10" cellspacing="20" height="100" width="500">
    <tr>
        <th>S:No</th>
        <th>Sub Code</th>
        <th>Sun Name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI403</td>
        <td>Introduction to Data Science</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19CS405</td>
        <td>Operating System</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19EE404</td>
        <td>Digital Electronics</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19EY702</td>
        <td>Creative Skills for Communication</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19PH214</td>
        <td>Physics for Quantum Computing</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19MA211</td>
        <td>Statistics and Numerical Methods</td>
    </tr>
</table>
<hr>
</center>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-19 140722](https://github.com/Aaron-0111/slot/assets/149347631/a79307e4-3b02-4b5d-881f-8e6261d4044e)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
