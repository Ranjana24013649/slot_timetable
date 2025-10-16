# Ex03 Time Table

## Date:16.10.25

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
<html>
<head>
<title>slot Timetable</title>    
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="10" border="7" bgcolor="pink">
<caption><b>SLOT TIME TABLE -Vinolia Alaina . R(212224240184)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>Logic and combinatorics</td>
<td>EDM</td>
<td>Logic and combinatorics</td>
<td>OS</td>
<td>Cryptography</td>
<td>Cryptography</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>DS</td>
<td>-</td>
<td>EDM</td>
<td>FWD</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>-</td>
<td>Ad C</td>
<td>MENTOR</td>
<td>QA 1</td>
<td>OS</td>
<td>FWAD</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>EMPD</td>
<td>DS</td>
<td>-</td>
<td>EMPD</td>
<td>-</td>
<td>Ad C</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2" bgcolor="green">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS415</td>
<td>Cryptography</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI302</td>
<td>Engineering Design and Modelling(EDM)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center"> 19MA206</td>
<td>Logic and combinatorics</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI305</td>
<td>Advance C Programming</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics and Product Development</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19AI403</td>
<td>Introduction to Data Science<td>
    <tr>
   <td align="center">8.</td>
<td align="center">19EY710</td>
<td>Quantitative Ability 1<td> 
    </tr>
    <tr>
<td align="center">9    .</td>
<td align="center">19CS4005</td>
<td>Operating System</td>    
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-10-16 114846.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
