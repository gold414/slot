# Ex03 Time Table
## Date:20.09.2025

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
    <title>Time Table</title>
</head>
<body>
    <center>
    <img src="logo.png" width="700" height="200">
    <br>
    <h2>SLOT TIME TABLE THANGAPAZHAM P(25017581)</h2>
    <table border="4" cellpadding="2" cellspacing="5" bgcolor="lightpink" height="200" width="700">
        <tr bgcolor="lightblue">
          <th bgcolor="lightgreen">Day/Time</th>
          <th>Monday</th>
          <th>Tuesday</th>
          <th>Wednesday</th>
          <th>thursday</th>
          <th>Friday</th>
          <th>Saturday</th>
        </tr>
        <tr bgcolor="lightpink" align="center">
            <th bgcolor="lightblue">8-10</th>
            <td colspan="2">FREE SLOT</td>
            <td >WEB</td>
            <td colspan="2">FREE SLOT</td>
            <td>WEB</td>
        </tr>
        <tr bgcolor="lightpink" align="center">
            <th bgcolor="lightblue">10-12</th>
            <td>PYTHON</td>
            <td>ENGLISH</td>
            <td>WEB</td>
            <td>ENGLISH</td>
            <td colspan="2">FREE SLOT</td>
        </tr>
        <tr bgcolor="lightpink">
            <th bgcolor="lightblue">12-1</th>
            <td colspan="7" align="center">LUNCH</td>
        </tr>
        <tr bgcolor="lightpink" align="center">
            <th bgcolor="lightblue">1-3</th>
            <td colspan="2">PYTHON</td>
            <td>MENTOR MEET</td>
            <td>PYTHON</td>
            <td colspan="2">WEB</td>
        </tr>
        <tr bgcolor="lightpink" align="center">
            <th bgcolor="lightblue">3-5</th>
            <td colspan="3">ENGLISH</td>
            <td>PHYTHON</td>
            <td>FREE SLOT</td>
            <td>ENGLISH</td>
        </tr>

    </table>
    <br>
    <table border="4" cellpadding="2" cellspacing="3" height="200" width="700">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td align="center">19AI414</td>
            <td>Fundamemtals of Web Application Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td align="center">19AI301</td>
            <td>Python Programming (PYTHON)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td align="center">19EN101</td>
            <td>Communicative English (ENGLISH)</td>
        </tr>
    </table>
    </center>
</body>

</html>
```
## OUTPUT
<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/3dc9ad70-a237-49b3-acf0-3e9e8f1f44b5" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
