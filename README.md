# Ex03 Time Table
## Date:21/09/2025

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
        <title>slots</title>
    </head>
    <body>
        <img src="logo.png" height="100" width="730">
        <h2><b>SLOT TIME TABLE-NEHA S(250165260)</b></h2>
        <table border="1" cellpadding="10" cellspacing="5" bgcolor="lavender">
            <tr bgcolor="pink">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
            </tr>
        <tr>
            <td bgcolor="pink">8-10</td>
            <td>FREE SLOT</td>
            <td colspan="2" align="center">Python</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td bgcolor="pink">10-12</td>
            <td>Python</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td colspan="3" align="center">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="pink">12-1</td>
            <td colspan="6" align="center">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="pink">1-3</td>
            <td colspan="2" align="center">Python</td>
            <td>ECA-M</td> 
            <td>Python</td>
            <td>FWAD</td> 
            <td>FWAD</td>          
        </tr>
        <tr>
            <td bgcolor="pink">3-5</td>
            <td colspan="3" align="center">FREE SLOT</td>
            <td>Python</td>
            <td colspan="2" align="center">FREE SLOT</td>
        </tr>
        </table>
        <br>
        <table border="1" cellpadding="10" cellspacing="5">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
        </table>
                
        
                
            
        

        
        
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (18).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
