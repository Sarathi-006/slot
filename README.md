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
```<html>
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <BODY>
        <img src="logo.png" width="1100" height="150">
        <table border="2" cellspacing="10" cellpadding="5">
            <caption>SLOT TIME TABLE-PRIYAADARSHINI K(23000629)</caption>
                    <tr>
                          <th bgcolor="cyan"><B>DAY/TIME</th>
                          <th bgcolor="cyan"><B>Monday</th>
                          <th bgcolor="cyan">Tuesday</th>
                          <th bgcolor="cyan">Wednesday</th>
                          <th bgcolor="cyan">Thursday</th>
                          <th bgcolor="cyan">Friday</th>
                          <th bgcolor="cyan">Saturday</th>
                    </tr>
                    <tr>
                          <td bgcolor="cyan"><B>8-10</td>
                          <td bgcolor="pink">FREE SLOT</td>
                          <td bgcolor="pink">TRANS</td>
                          <td bgcolor="pink">CHEM</td>
                          <td bgcolor="pink">FREE SLOT</td>
                          <td bgcolor="pink">FWAD</td>
                          <td bgcolor="pink">CS</td>
                    </tr>
                    <tr>
                        <td bgcolor="cyan"><B>10-12</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">PHY</td>
                        <td bgcolor="pink">TRANS</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">CHEM</td>
                    </tr>
                    <tr>
                        <td bgcolor="cyan"><B>12-1</td>
                        <th colspan="6" bgcolor="pink">LUNCH</th>
                    </tr>
                    <tr>
                        <td bgcolor="cyan"><B>1-3</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">FWAD</td>
                        <td bgcolor="pink">STATISTICS</td>
                        <td bgcolor="pink">FWAD</td>
                        <td bgcolor="pink">CN</td>
                        <td bgcolor="pink">STATISTICS</td>
                    </tr>
                    <tr>
                        <td bgcolor="cyan"><B>3-5</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">PHY</td>
                        <td bgcolor="pink">CN</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">FREE SLOT</td>
                        <td bgcolor="pink">FREE SLOT</td>
                    </tr>
            </table>
            <br>
        </br>
            <table border="5" cellspacing="10" cellpadding="5" width="600" height="50">
                <tr>
                    <th>S. NO.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI414</td>
                    <td>Fundamentals of Web Application Development (FWAD)</td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19PH214</td>
                    <td>Physics for Quantum Computing (PHY)</td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19CS406</td>
                    <td>Computer Networks (CN)</td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19CY205</td>
                    <td>Principles of Chemistry in Engineering (CHEM)</td>
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19MA211</td>
                    <td>Statistics and Numerical Method (STATISTICS)</td>
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19MA219</td>
                    <td>Transforms and its Applications (TRANS)</td>
                </tr>
                <tr>
                    <td>7.</td>
                    <td>19EY702</td>
                    <td>Creative Skills (CS)</td>
                </tr>
            </table>
    </BODY>
</html>
```

## OUTPUT
![Screenshot 2024-05-13 104505](https://github.com/Sarathi-006/slot/assets/149349756/1bdcdc0b-e12f-4c2e-8285-3a5323565faf)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
