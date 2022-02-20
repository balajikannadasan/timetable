# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
~~~
<!DOCTYPE html>
<html>
 <head>
 <title>BIO</title>
 </head>
 <body>
 <table border = "2" cellspacing="5" bordercolor="black" 
bgcolor="yellow">
  <img src="logo.png" width="700px" height="100px"/>
 <tr>
 <th colspan="8">Time Table</th>
 </tr>
 <tr>
 <th colspan="2">Name:K.Balaji</th>
 <th colspan="2">Ref.no:21005757</th>
 <th colspan="2">Department:AIDS</th>
 <th colspan="4">Saveetha Engineering</th>
 </tr>
 <tr>
 <th>DAYS</th>
 <th>1</th>
 <th>2</th>
 <th>3</th>
 <th>4</th>
 <th rowspan="6">Lunch break</th>
 <th>5</th>
 <th>6</th>
 </tr>
 <tr>
 <td><em>Monday</em></td>
 <td colspan="2">19A1401/Karthi Govindaraju</td>
 <td colspan="2">19MA221/Jaba Jasphin E.T</td>
 <td colspan="2">19MA220/Jaba Jasphin E.T</td>
 </tr>
 <tr>
 <td><em>Tuesday</em></td>
 <td colspan="2">19EY701/Praveen P</td>
 <td colspan="2">19AI303/Ram G.R</td>
 <td colspan="2">19AI302/Ram G.R</td>
 </tr>
 <tr>
 <td><em>Wednesday</em></td>
 <td colspan="2">----</td>
 <td colspan="2">19MA220/Jaba Jasphin E.T</td>
 <td colspan="2">19AI401/Karthi Govindharaju</td>
 </tr
 <tr>
 <td><em>Thursday</em></td>
 <td colspan="2">19AI302/Ram G.R</td>
 <td colspan="2">19AI301/Jaba Jasphin E.T</td>
 <td colspan="2">19AI303/Ram G.R</td>
 </tr>
 <tr>
 <td><em>Friday</em></td>
 <td colspan="2">----</td>
 <td colspan="2">19AI301/Jaba Jasphin E.T</td>
 <td colspan="2">19AI402/Karthi Govindaraju</td>
 </tr>
 </table>
 </body>
<body>
    <h1>List of Subjects</h1>
    <ol type="l">
    <li>19EY701-Soft Skills</li>
    <li>19MA221-Python Lab</li>
    <li>19MA220-Linear Algebra</li>
    <li>19AI401-Web Technology</li>
    <li>19AI402-Web Technology Lab</li>
    <li>19AI303-Mechanics</li>
    <li>19AI302-Mechanics Lab</li>
</body>
</html>
~~~
# OUTPUT
<!DOCTYPE html>
<html>
 <head>
 <title>BIO</title>
 </head>
 <body>
 <table border = "2" cellspacing="5" bordercolor="black" 
bgcolor="yellow">
  <img src="logo.png" width="700px" height="100px"/>
 <tr>
 <th colspan="8">Time Table</th>
 </tr>
 <tr>
 <th colspan="2">Name:K.Balaji</th>
 <th colspan="2">Ref.no:21005757</th>
 <th colspan="2">Department:AIDS</th>
 <th colspan="4">Saveetha Engineering</th>
 </tr>
 <tr>
 <th>DAYS</th>
 <th>1</th>
 <th>2</th>
 <th>3</th>
 <th>4</th>
 <th rowspan="6">Lunch break</th>
 <th>5</th>
 <th>6</th>
 </tr>
 <tr>
 <td><em>Monday</em></td>
 <td colspan="2">19A1401/Karthi Govindaraju</td>
 <td colspan="2">19MA221/Jaba Jasphin E.T</td>
 <td colspan="2">19MA220/Jaba Jasphin E.T</td>
 </tr>
 <tr>
 <td><em>Tuesday</em></td>
 <td colspan="2">19EY701/Praveen P</td>
 <td colspan="2">19AI303/Ram G.R</td>
 <td colspan="2">19AI302/Ram G.R</td>
 </tr>
 <tr>
 <td><em>Wednesday</em></td>
 <td colspan="2">----</td>
 <td colspan="2">19MA220/Jaba Jasphin E.T</td>
 <td colspan="2">19AI401/Karthi Govindharaju</td>
 </tr
 <tr>
 <td><em>Thursday</em></td>
 <td colspan="2">19AI302/Ram G.R</td>
 <td colspan="2">19AI301/Jaba Jasphin E.T</td>
 <td colspan="2">19AI303/Ram G.R</td>
 </tr>
 <tr>
 <td><em>Friday</em></td>
 <td colspan="2">----</td>
 <td colspan="2">19AI301/Jaba Jasphin E.T</td>
 <td colspan="2">19AI402/Karthi Govindaraju</td>
 </tr>
 </table>
 </body>
<body>
    <h1>List of Subjects</h1>
    <ol type="l">
    <li>19EY701-Soft Skills</li>
    <li>19MA221-Python Lab</li>
    <li>19MA220-Linear Algebra</li>
    <li>19AI401-Web Technology</li>
    <li>19AI402-Web Technology Lab</li>
    <li>19AI303-Mechanics</li>
    <li>19AI302-Mechanics Lab</li>
</body>
</html>
