# Ex03 Time Table
## Date:31.10.2023


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
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIMETABLE - PRASANA (23013745)</b></caption>
<tr align="center">
	<th bgcolor="yellow">Day/Time</th>
	<th bgcolor="yellow">Monday</th>
	<th bgcolor="yellow">Tuesday</th>
	<th bgcolor="yellow">Wednesday</th>
	<th bgcolor="yellow">Thursday</th>
	<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="yellow">8-10</th>
	<td>FREE</td>
	<td>FREE</td>
	<td> WEB</td>
	<td>C PROGRAM</td>
	<td>MATHS</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">10-12</th>
	<td>FREE</td>
	<td>CHEMISTRY</td>
	<td>FREE</td>
	<td>WEB </td>
	<td>PHYSICS</td>
</tr>
<tr>
	<th bgcolor="yellow">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">1-3</th>
	<td>CHEMISTRY</td>
	<td>ENGLISH</td>
	<td>C PROGRAM</td>
	<td>ENGLISH</td>
	<td>WEB</td>
</tr>
<tr align="center">
	<th bgcolor="yellow">3-5</th>
	<td>PHYSICS</td>
	<td>SOFT SKILL</td>
	<td>FREE</td>
	<td>MATHS</td>
	<td>FREE</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19MA201</td>
<td>Maths</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Web development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>Communicative English</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Chemistry</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY701</td>
<td>Soft skills</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI3041</td>
<td>C PROGRAM</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19PH214</td>
<td>PHYSICS</td>
</tr>


</table>
</body>
</html>
```

## OUTPUT
![Screenshot (8)](https://github.com/Prasanavausdevan/slot/assets/144870579/9fa89a0f-8303-45f2-bb54-4dd37a6c2533)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
