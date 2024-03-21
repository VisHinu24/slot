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
          
          <table border= "4" cellpadding="10px" bgcolor=green" align="center" >
          <h2 style="text-align: center;"> SLOT TIME TABLE - Vishinu H (212223220124) </h2>
          <br>
               <tr bgcolor="pink">  
               <th bgcolor="gray">   DAY/TIME </th>
               <th>   MONDAY </th>
               <th>   TUESDAY </th>
               <th>   WEDNESDAY </th>
               <th>   THURSDAY </th>
               <th>   FRIDAY </th>
               <th>   Saturday</th>
               </tr>
               <tr>
                <th bgcolor="pink"> 8-10 </th>
                <td>FWAD</td>
                <td>ML</td>
                  <td>C programming</td>
                <td> OS </td>
                <td>FREE SLOT</td>
                <td>ML</td>
               </tr>
               <tr>
                <th bgcolor="pink"> 10-12 </th>
                <td> FREE SLOT </td>
                <td> Python programm</td>
                <td colspan="2"> FREE SLOT </td>
                <td> Networks </td>
                <td>FREE SLOT</td>>
               </tr>
               <tr>
                <th bgcolor="pink"> 12-1 </th>
                 <td colspan="6" align="center">LUNCH TIME</td>
               </tr>
               <tr>
                <th bgcolor="pink"> 1-3 </th>
                <td> Networks </td>
                <td>FREE SLOT</td>
                <td> Python Programming </td>
                <td>FWAD</td>
                <td> FWAD </td>
                <td>Soft Skills</td>
               </tr>
               
              
              <tr>
               <th bgcolor="pink"> 3-5 </th>
               <td colspan="4">FREE SLOT</td>
               <td> OS </td>
               <td>FREE SLOT</td>
              </tr>
           </table>
            <table border= "4" cellpadding="10px"  align="center" >
            <br><br>
           <tr>
           <th> S.No </th>
             <th> SUBJECT CODE </th>
           <th> SUBJECT NAME </th>
           </tr>
           <tr> 
           <td> 1. </td>
           <td> 19AI414 </td>
           <td> Fundamental of web application and development </td>
           </tr>
           <tr>
           <td> 2. </td>
           <td> 19EY701 </td>
           <td> Soft Skills </td>
           </tr>
           <tr>
           <td> 3. </td>
           <td> 19AI304 </td> 
           <td> Advanced C programming </td>
           </tr>
           <tr>
           <td> 4. </td>
           <td> 19AI301 </td>
           <td> Python Programming</td>
           </tr>
           <tr>
           <td> 5. </td>
           <td> 19AI410 </td>
           <td> Introduction to Machine Learning </td>
           </tr>
           <tr>
           <td> 6. </td>
           <td> 19CS405 </td>
           <td> Operating System </td>
           </tr>
           <tr>
            <td> 7. </td>
            <td> 19CS406 </td>
            <td> Computer Networks </td>
            </tr>
           </table>
              
        </body>
</html>
```

## OUTPUT
 ![alt text](<Screenshot 2024-03-21 230803.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
