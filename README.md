# Ex03 Time Table
## Date:10\12\2025

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
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TimeTable</title>
</head>
<body>
    </head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - LITYA M ( 25002964 ) </h3>
        <table align="center" border="5" cellpadding="10" cellspacing="2" bgcolor="">
        <tr>
          <th bgcolor="yellow">Day/time</th>    
          <th bgcolor="yellow" style="padding:20px;width:200px;">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow"style="padding:20px;width:200px;">1-3</th>
          <th bgcolor="yellow"style="padding:20px;width:200px;">3-5</th>
        </tr>
        <tr align="center">
           <th bgcolor="yellow">MONDAY </th>
           <td colspan="2" align="center" bgcolor="MAGENTA">PYTHON PROGRAMMING</td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td bgcolor="LIGHTSLATEBLUE">FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
           <td bgcolor="ORANGE">COMMUNICATIVE ENGLISH </td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">TUESDAY  </th>
            <td align ="center" bgcolor="LIGHTSLATEBLUE">FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT </td>
            <td align="center">FREE SLOT</td>
            <td bgcolor="MAGENTA">PYTHON PROGRAMMING </td>
            <td bgcolor="LIGHTSLATEBLUE">FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT </td>
         </tr> 
         <tr align="center" >
            <th bgcolor="yellow">WEDNESDAY </th>
            <td bgcolor="LIGHTSLATEBLUE">FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT </td>
            <td>FREE SLOT </td>
            <td>MENTOR MEET   </td>
            <td bgcolor="ORANGE">COMMUNICATIVE ENGLISH </td>
         </tr> 
         <tr align="center" >
            <th bgcolor="yellow">THURSDAY  </th>
            <td>FREE SLOT </td>
            <td bgcolor="ORANGE">COMMUNICATIVE ENGLISH</td>
            <td bgcolor="LIGHTSLATEBLUE">FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT </td>
         </tr>
          <tr align="center" >
            <th bgcolor="yellow">FRIDAY </th>
            <td >FREE SLOT</td>
            <td bgcolor="MAGENTA">PYTHON PROGRAMMING    </td>
            <td bgcolor="MAGENTA">PYTHON PROGRAMMING </td>
            <td>FREE SLOT </td>
         </tr>
         <tr align="center">
            <th bgcolor="yellow">SATURDAY  </th>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>FREE SLOT </td>
            <td bgcolor="ORANGE">COMMUNICATIVE ENGLISH </td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr align="center" >
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr align="center" >
            <th>1.</th>
            <td>5Q1-1</td>
            <td >PYTHON PROGRAMMING </td>
         </tr>
         <tr align="center" >
             <th>2.</th>
             <td>5P2-1</td>
             <td >COMMUNICATIVE ENGLISH  </td>
          <tr align="center">
             <th>3.</th>
             <td>5P1-2</td>
             <td >FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>
         </table>   
    </body>
</html>

```

## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-12-10 094703" src="https://github.com/user-attachments/assets/ef885925-2d20-4ec7-98a3-064dde9edb89" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
