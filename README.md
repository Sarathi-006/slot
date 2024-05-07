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

## PROGRAM
```
<html>
<head>
<title> SLOT TIME TABLE - Sarathi S </title>
</head>
<body>
<center>
<img src="C:\Users\admin\Downloads\logo.png"height="100"width="540">
</center>
<br>
<table align="center" width="540"cellspacing="2"cellpadding="1" border="5" bgcolor="pink">
<caption><b>MY TIMETABLE</b></caption>
<tr align="center">
<th bgcolor="silver">Day/Time></th>
<th bgcolor="silver">Monday</th>
<th bgcolor="silver">tuesday</th>
<th bgcolor="silver">wednesday</th>
<th bgcolor="silver">thursday</th>
<th bgcolor="silver">friday</th>
<th bgcolor="silver">saturday</th>
</tr>
<tr align="center">
<th bgcolor="blue">8-10</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF  C</td>
<td>THEORY OF COMPUTATION6</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTALS OF WEB</td>
<td>DIGITAL ELECTRONICS</td>
</tr>
<tr align="center">
<th bgcolor="blue">10-12</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMPUTER NETWPORKS</td>
<td>FREE SLOTS</td>
<td>FREE SLOT</td>
<td>DIGITAL ELECTRONICS</td>
<td>THEORY OF COMPUTATION</td>
</tr>
<tr>
<th bgcolor="blue">12-1</th>
<td colspan="5" align="center">L U N C H </td>
</tr>
<tr align="center">
<th bgcolor="blue">1-3</th>
<td>EMPD</td>
<td>FUNDAMENTALS OF WEB</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>EMPD</td>
</tr>
<tr align="center">
<th bgcolor="blue">3-5</th>
<td>FUNDAMENTALS OF C</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMPUTER NETWPORKS</td>
<td>EMPD</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S.No</th>
<th>Subject code</th>
<th>Subject name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB </td> 
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C </td> 
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS407</td>
<td>THEORY OF COMPUTATION</td> 
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19AI303</td>
<td>EMPD</td> 
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS406</td>
<td>COMPUTER NETWORKS</td> 
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td> 
<tr>
<td align="center">7.</td>
<td align="center">19EE404</td>
<td>DIGITAL ELECTRONICS</td> 
</tr>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-05-07 104942](https://github.com/selvasachein/slot/assets/149349756/80eb87a6-6a5e-4494-a245-3cfed2656b30)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
