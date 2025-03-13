# Ex03 Time Table
## Date:13/03/2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        table{
            margin-bottom: 30px;
        }
        .colored{
        tr {
        background-color:lightcoral;
    }
    td {
        background-color:lightblue;
    }
}
    </style>
</head>

</head>
<body>
    <center><img src="saveetha.png" height="100px" width="700px" alt="something went wrong"/></center>
    <h1>  </h1>
    <center><b><caption>SLOT TIME TABLE - MANJUSRI KAVYA R (212224040186) </caption></b></center>
    <center><table class="colored" border="2">
        <tr>
            <th><b>Time/Day</b></th>
            <th><b>Monday</b></th>
            <th><b>Tuesday</b></th>
            <th><b>Wednesday</b></th>
            <th><b>Thursday</b></th>
            <th><b>Friday</b></th>
            <th><b>Saturday</b></th>
        </tr>
        <tr>
            <th><b><center>8-10</center></b></th>
            <td><center>F.AI</center></td>
            <td><center>Free Slot</center></td>
            <td><center>CDS</center></td>
            <td><center>WEB</center></td>
            <td><center>C</center></td>
            <td><center>AI</center></td>
        </tr>
        <tr>
            <th><b><center>10-12</center></b></th>
            <td colspan="2"><center>Free Slot</center></td>
            <td><center>EDM</center></td>
            <td><center>Free Slot</center></td>
            <td><center>ENG</center></td>
            <td><center>WEB</center></td>
        </tr>
        <tr>
            <th><b><center>12-1</center></b></th>
            <td colspan="6"><center>LUNCH</center></td>
        </tr>
        <tr>
            <th><b><center>1-3</center></b></th>
            <td><center>ENG</center></td>
            <td><center>C</center></td>
            <td><center>Mentor</center></td>
            <td colspan="2"><center>PHY</center></td>
            <td><center>EDM</center></td>
        </tr>
        <tr>
            <th><b><center>3-5</center></b></th>
            <td ><center>AI</center></td>
            <td>Free Slot</td>
            <td><center>F.AI</center></td>
            <td><center>MAT</center></td>
            <td>Free Slot</td>
            <td><center>MAT</center></td>
        </tr>  
    </table></center>
    <h3>  </h3>
    <center><table border="2">
        <tr>
            <td><b>S.NO.</b></td>
            <td><b>Subject code</b></td>
            <td><b><center>Subject Name</center></b></td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (WEB) </td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI302</td>
            <td>Engineering design and moodelling (EDM) </td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI405</td>
            <td>Fundamentals of Artificial intelligence (F.AI) </td>
        </tr>
        <tr>
            <td>4</td>
            <td>19MA222</td>
            <td>Probability and Queueing models (MAT) </td>
        </tr>
        <tr>
            <td>5</td>
            <td>19PH814</td>
            <td>Physics for Quantum computing (PHY) </td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EN101</td>
            <td>Communicative English (ENG) </td>
        </tr>
        <tr>
            <td>7</td>
            <td>19EY708</td>
            <td>Career Development Skills (CDS) </td>
        </tr>
        <tr>
            <td>8</td>
            <td>19AI304</td>
            <td>Fundamentals of C programming (C) </td>
        </tr>
        <tr>
            <td>9</td>
            <td>19AI501</td>
            <td>Applications of AI (AI) </td>
        </tr>
        <tr>
            <td>10</td>
            <td>ECA-M</td>
            <td>Mentor Meet (Mentor) </td>
        </tr>
    </table></center>
</body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/236e37bd-7139-4a55-87e4-60a3da8a8e5f)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
