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
<!DOCTYPE html>
<html lang="en">
     <head>
              <title> web </title>
     </head>
     <body bgcolor="white" TEXT="black">
<center>
     <img src="image.png"  height="100" width="1000" align="center" /></center>
          
          <table border= "5"  cellpadding="10px" bgcolor="black" align="center" >
          <h2 style="text-align: center;"> SLOT TIME TABLE - Vishinu H (212223220124) </h2>
               <tr bgcolor="pink">  
               <th bgcolor="gray">   DAY/TIME </th>
               <th>   MONDAY </th>
               <th>   TUESDAY </th>
               <th>   WEDNESDAY </th>
               <th>   THURSDAY </th>
               <th>   FRIDAY </th>
               <th >   Saturday</th>
               </tr>
               <tr>
                <th bgcolor="pink"> 8-10 </th>
                <td bgcolor="#FFA07A">FWAD</td>
                <td bgcolor="#FFA07A">ML</td>
                  <td bgcolor="#FFA07A">C programming</td>
                <td bgcolor="#FFA07A"> OS </td>
                <td bgcolor="#FFA07A">FREE SLOT</td>
                <td bgcolor="#FFA07A">ML</td>
               </tr>
               <tr>
                <th bgcolor="pink"> 10-12 </th>
                <td bgcolor=#FF7F50> C Programming </td>
                <td bgcolor=#FF7F50> Python programming</td>
                <td colspan="2" bgcolor=#FF7F50> FREE SLOT </td>
                <td bgcolor=#FF7F50> Networks </td>
                <td bgcolor=#FF7F50>FREE SLOT</td>>
               </tr>
               <tr>
                <th bgcolor="pink"> 12-1 </th>
                 <td colspan="6" align="center" bgcolor=#FF8C00>LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="pink"> 1-3 </th>
                <td bgcolor="#FFFF00"> Networks </td>
                <td bgcolor="#FFFF00">FREE SLOT</td>
                <td bgcolor="#FFFF00"> Python Programming </td>
                <td bgcolor="#FFFF00">FWAD</td>
                <td bgcolor="#FFFF00"> FWAD </td>
                <td bgcolor="#FFFF00">Soft Skills</td>
               </tr>
               
              
              <tr>
               <th bgcolor="pink"> 3-5 </th>
               <td colspan="4" bgcolor="#F0E68C">FREE SLOT</td>
               <td bgcolor="#F0E68C"> OS </td>
               <td bgcolor="#F0E68C">FREE SLOT</td>
              </tr>
           </table>
            <table border= "4" cellpadding="10px"  align="center" >
            <br><br>
           <tr>
           <th bgcolor=#FFFFE0> S.No </th>
             <th bgcolor="#E0FFFF"> SUBJECT CODE </th>
           <th bgcolor="#E6E6FA"> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td bgcolor=#FFFFE0>  1. </td>
           <td bgcolor="#E0FFFF"> 19AI414 </td>
           <td bgcolor="#E6E6FA"> Fundamental of web application and development(FWAD) </td>
           </tr>
           <tr>
           <td bgcolor=#FFFFE0> 2. </td>
           <td bgcolor="#E0FFFF"> 19EY701 </td>
           <td bgcolor="#E6E6FA"> Soft Skills </td>
           </tr>
           <tr>
           <td bgcolor=#FFFFE0> 3. </td>
           <td bgcolor="#E0FFFF"> 19AI304 </td> 
           <td bgcolor="#E6E6FA"> Advanced C programming </td>
           </tr>
           <tr>
           <td bgcolor=#FFFFE0> 4. </td>
           <td bgcolor="#E0FFFF"> 19AI301 </td>
           <td bgcolor="#E6E6FA"> Python Programming</td>
           </tr>
           <tr>
           <td bgcolor=#FFFFE0> 5. </td>
           <td bgcolor="#E0FFFF"> 19AI410 </td>
           <td bgcolor="#E6E6FA"> Introduction to Machine Learning(ML) </td>
           </tr>
           <tr>
           <td bgcolor=#FFFFE0> 6. </td>
           <td bgcolor="#E0FFFF"> 19CS405 </td>
           <td bgcolor="#E6E6FA"> Operating System(OS) </td>
           </tr>
           <tr>
            <td bgcolor=#FFFFE0> 7. </td>
            <td bgcolor="#E0FFFF"> 19CS406 </td>
            <td bgcolor="#E6E6FA"> Computer Networks </td>
            </tr>
           </table>
              
        </body>
</html>
```

## OUTPUT
![w](<Screenshot 2024-03-22 155817.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
