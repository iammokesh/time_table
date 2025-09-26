# Ex03 Time Table
# Date:26.09.2025
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
<title> Course Schedule </title>
</head>
<body>
<img src="logo.png" height="100" width="540">
<table align="corner" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SCHEDULE OF ALL COURSES</b></caption>
<tr align="corner">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">8-10</th>
<th bgcolor="yellow">10-12</th>
<th bgcolor="yellow">12-1</th>
<th bgcolor="yellow">1-3</th>
<th bgcolor="yellow">3-5</th>

</tr>
<tr align="corner">
<th bgcolor="yellow">MONDAY</th>
<td >FUNDAMENTAL OF WEB</td>
<td>PYTHON</td>
<td rowspan="6" >LUNCH </td>
<td colspan="2">FREE SLOT</td>


</tr>
<tr align="corner">
<th bgcolor="yellow">TUESDAY</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH </td>
<td colspan="2">FREE SLOT</td>


</tr>
<tr align="corner">
<th bgcolor="yellow">WEDNESDAY</th>
<td >FUNDAMENTAL OF WEB </td>
<td>FUNDAMENTAL OF WEB</td>
<td>MENTOR MEET</td>
<td>PYTHON</td>

</tr>
<tr align="corner">
<th bgcolor="yellow">THURSDAY</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>PYTHON</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>PYTHON</td>

</tr>
<tr>
<th bgcolor="yellow">FRIDAY</th>
<td>FREE SLOT</td>
<td>FUNDAMENTAL OF WEB</td>
<td>FREE SLOT</td>
<td>PYTHON</td>
</tr>
<tr>
<th bgcolor="yellow">SATURDAY</th>
<td>COMMUNICATIVE ENGLISH</td>
<td>FUNDAMENTAL OF WEB</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
</tr>

</table>
<br>
<table align="corner" cellspacing="2" cellpadding="4" border="2">
<tr align="corner">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="corner">1.</td>
<td align="corner">19AI414</td>
<td>FUNDAMENTALS OF WEB (FWAD)</td>
</tr>
<tr>
<td align="corner">2.</td>
<td align="corner">19AI301</td>
<td>PYTHON PROGRAMMING (PYTHON PROGRAM)</td>
</tr>
<tr>
<td align="corner">3.</td>
<td align="corner">19EN301</td>
<td> COMMUNICATIVE ENGLISH (ENG))</td>
</tr>

</table>
</body>
</html>

```
    
        
        


# OUTPUT
![alt text](<Screenshot (8).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
