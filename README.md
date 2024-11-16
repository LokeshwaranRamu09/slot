# Ex03 Time Table
## Date:16/11/2024

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
    <body>
        <img src="logo.png">
        <table border="4" bgcolor="lightblue" cellspacing="5" cellpadding="15">
            <caption>Timetable R.Lokeshwaran(24011606)</caption>
            
            </tr>
                <th bgcolor="blue">Timings/Days</th>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="blue">Thursday</th>
                <th bgcolor="blue">Friday</th>
                <th bgcolor="blue">Saturday</th>
            </tr>
            <tr> 
                <td bgcolor="cyan">8-10</td>
                <td>Free slot</td>
                <td>Free slot</td>
                <td>Free slot</t>
                <td>Physics for quantum computing</td>
                <td>Fundementals of web application</td>
                <td>Free slot</td>
            </tr>
            <tr> 
               <td bgcolor="cyan">10-12</td>
               <td>Digital Electronics</td>
               <td>Calculus and matrix algebra</td>
               <td>Fundementals of C programming</td>
               <td>Basic Electrical,Electronics,and Measurement</td>
               <td>Fundementals of C programming</td>
               <td>Physics for quantum computing</td>
            </tr>
            <tr> 
                <td bgcolor="cyan">12-1</td>
                <th colspan="6">lunch</th>
                
            </tr>
            <tr>
                <td bgcolor="cyan">1-3</td>
                <td>Fundementals of web application</td>
                <td>Fundementals of web application</td>
                <td>Mentor Meet</td>
                <td>Digital Electronics</td>
                <td>Basic Electrical,Electronics,and Measurement</td>
                <td>Calculus and matrix algebra</td>
            </tr>
            <tr>
                <td bgcolor="cyan">3-5</td>
                <td>free slot</td>
                <td>free slot</td>
                <td>free slot</td>
                <td>free slot</td>
                <td>cds</td>
                <td>free slot</td>
            </tr>   

        </table>
        <br>
        <table border="2" cellspacing="10" cellpadding="10">
        <tr>
            <td>S.NO</td>
            <td>Subject Code</td>
            <td>Subject Name</td>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI304</td>
            <td>Fundementals of C programming</td>

        </tr>
            <td>2.</td>
            <td>19AI414</td>
            <td>Fundementals of web application</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19EE305</td>
            <td>Basic Electrical,Electronics,and Measurement</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and matrix algebra</td>
        </tr>
        <tr> 
            <td>6.</td>
            <td>ECA-M-SCOFT</td>
            <td>Mentor Meet</td>
        </tr>
        <tr> 
            <td>7.</td>
            <td>SH3214</td>
            <td>Physics for quantum computing</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>cds</td>
            <td>Career developement skills</td>




        </tr>

      </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (37).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
