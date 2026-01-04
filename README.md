# Ex03 Time Table
## Date:04.01.2026

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
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - RITHISH RAM M 25008637</title>
</head>
<body>
    <img src="logo1.jpg" height="150" width="500" border="6">

    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - RITHISH RAM M 25003659</h3>

    <!-- TIME TABLE BASED ON PORTAL IMAGE -->
    <table border="1">
        <tr bgcolor="yellow">
            <th>Day / Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr bgcolor="cyan">
            <td bgcolor="yellow">8-10</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FCP</td>
            <td>FREE SLOT</td>
        </tr>

        <tr bgcolor="cyan">
            <td bgcolor="yellow">10-12</td>
            <td>FREE SLOT</td>
            <td>CE</td>
            <td>FWAD</td>
            <td>CE</td>
            <td>FWAD</td>
            <td>FWAD</td>
        </tr>

        <tr bgcolor="cyan">
            <td bgcolor="yellow">12-1</td>
            <td colspan="6" align="center">LUNCH</td>
        </tr>

        <tr bgcolor="cyan">
            <td bgcolor="yellow">1-3</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>MM</td>
            <td>CE</td>
            <td>FWAD</td>
            <td>CE</td>
        </tr>

        <tr bgcolor="cyan">
            <td bgcolor="yellow">3-5</td>
            <td>FCP</td>
            <td>FCP</td>
            <td>FCP</td>
            <td>FCP</td>
            <td>FCP</td>
            <td>CE</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19EN101</td>
            <td>Communicative English (CE)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming (FCP)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19EY708</td>
            <td>Mentor Meet (MM)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

INCLUDE YOUR OUTPUT IMAGE
![alt text](<Your paragraph text.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
