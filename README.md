# Ex03 Time Table
## Date:

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

## PROGRAM:

```
<html>
    <head>

    </head>
    <body>
        <center>
            <img src="/static/logo.png" width="500">
        </center>
        <table border="2" cellpadding="10" align="center" bgcolor="ice blue">
            <caption><h2>Slot Time-Table - 212224230095</h2></caption>
            <tr><th>Day/Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th></tr>
            <tr><th>8-10</th><td bgcolor="ice blue">Web</td><td>Computer Network</td><td>DBMS</td><td>OS</td><td>Compiler Design</td><td>Probability</td></tr>
            <tr><th>10-12</th><td>Web</td><td>Computer Network</td><td>DBMS</td><td>OS</td><td>Compiler Design</td><td>Probability</td></tr>
            <tr align="center"><th>12-1</th><td colspan="4">Lunch</td></tr>
            <tr><th>1-3</th><td>Web</td><td>Computer Network</td><td>DBMS</td><td>OS</td><td>Compiler Design</td><td>Probability</td></tr>
            <tr><th>3-5</th><td>Web</td><td>Computer Network</td><td>DBMS</td><td>OS</td><td>Compiler Design</td><td>Probability</td></tr>
            <table border="2" cellpadding="10" align="center" bgcolor="white">
                <tr align="center">
                    <th>S.No</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr><td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Web</td>
                </tr>
                <tr>
                    <td align="center">2.</td>
                    <td align="center">19CS406</td>
                    <td>Computer Network</td>
                </tr>
                <tr>
                    <td align="center">3.</td>
                    <td align="center">19CS404</td>
                    <td>DBMS</td>
                </tr>
                <tr>
                    <td align="center">4.</td>
                    <td align="center">19CS405</td>
                    <td>OS</td>
                </tr>
                <tr>
                    <td align="center">5.</td>
                    <td align="center">19CS409</td>
                    <td>Compiler Design</td>
                </tr>
                <tr>
                    <td align="center">6.</td>
                    <td align="center">SH2222</td>
                    <td>Probability</td>
                </tr>
        </table>
    </body>
</html>
```


## OUTPUT:

<img width="1898" height="1135" alt="image" src="https://github.com/user-attachments/assets/7c849772-1295-4b25-bd08-30695928289d" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
