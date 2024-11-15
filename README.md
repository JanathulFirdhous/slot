# Ex03 Time Table
## Date:15.11.24

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
        <img src="logo.png" height="100" width="600">
    <table border="2" cellspacing="12" cellpadding="12">
        <caption>Timetable Janathul Firdhous(24900115)</caption>
        <tr bgcolor="cyan">
            <th>time & day</th>
            <th>MON</th>
            <th>TUE</th>
            <th>WED</th>
            <th>THUR</th>
            <th>FRI</th>
            <th>SAT</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td>Free slot</td>
            <td>FWAD</td>
            <td>Free slot</td>
            <td>UHV</td>
            <td>Phy</td>
            <td>Free slot</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>Eng</td>
            <td>Phy</td>
            <td>Che</td>
            <td>Free slot</td>
            <td>Che</td>
            <td>c prog</td>
    </tr>
      <tr>
        <td>1-3</td>
        <td>c prog</td>
        <td>Eng</td>
        <td>mentor meet</td>
        <td>DE</td>
        <td>FWAD</td>
        <td>FWAD</td>
      </tr>
      <tr>
        <td>3-5</td>
        <td>Free slot</td>
        <td>DE</td>
        <td colspan="4">Free slot</td>
      </tr>
    
    </table>
        <table border="2" cellspacing="9" cellpadding="6">
            <caption>Explantion</caption>
            <tr bgcolor="green">
                <th>S.No</th>
                <th>Course code</th>
                <th>Course name</th>
            
            </tr>
            <tr>
                <td>1</td>
                <td>19EN101</td>
                <td>COMMUNICATION ENGLISH(Eng)</td>
                
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>FUNDAMENTALS OF C PROGRAMMING(c prog)</td>
            
          </tr>
          <tr>
            <td>3</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT(FWAD)</td>
          </tr>
          <tr>
            <td>4</td>
            <td>SH3214</td>
            <td>PHYSICS FOR QUANTUM COMPUTING(Phy)</td>
          </tr>
          <tr>
            <td>5</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING(Che)</td>
          </tr>
          <tr>
            <td>6</td>
            <td>SH7801</td>
            <td>HUMAN VALUES AND PROFEESIONAL ETHICS(UHV)</td>
          </tr>
          <tr>
            <td>7</td>
            <td>19EE404</td>
            <td>DIGITAL ELECTRONICS(DE)</td>
          </tr>
          <tr>
            <td>8</td>
            <td>ECA-SCOFT</td>
            <td>MENTOR MEETING(mentor meet)</td>
          </tr>
        </table>
        </body>
</html>



```


## OUTPUT
![alt text](<Screenshot (18).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
