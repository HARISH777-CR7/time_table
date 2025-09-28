# Ex03 Time Table
# Date:
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

````
<!DOCTYPE html>
<html >
<head>
  <title>Slot Time Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 20px;
    }
    h2 {
      margin-bottom: 5px;
    }
    table {
      border-collapse: separate;
      margin: 20px auto;
      width: 80%;
    }
    th, td {
      font-weight: bold;
      border: 1px solid black;
      padding: 10px;
      text-align: center;
    }
    th {
      background: rgb(81, 0, 255);
    }
    .highlight {
      background: rgb(255, 255, 255);
    }
  </style>
</head>
    <img src="Screenshot 2025-09-28 160301.png" alt="Background Image" style="width:300px; margin-bottom:20px;">
    <h2>SLOT TIME TABLE - HARISH K (25013390)</h2>
  
  <table>
    <tr>
      <th>Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <TH>Saturday</TH>
    </tr>
    <tr>
      <td>8-10</td>
      <td>FREE</td>
      <td>WEB</td>
      <td>FREE</td>
      <td>C PROGRAM</td>
      <td>DS</td>
      <TD>WEB</TD>
       
     
    </tr>
    <tr>
      <td>10-12</td>
      <td >WEB</td>
      <td >DS</td>
      <td colspan="4">F R E E</td>
       
    </tr>
    <tr>
      <td>12-1</td>
      <td colspan="6" >L U N C H</td>
    </tr>
    <tr>
      <td>1-3</td>
      <td >DS</td>
      <td >WEB</td>
      <td >MENTOR</td>
      <td >C PROGRAM</td>
      <td >WEB</td>
      <TD rowspan="2">FREE</TD>
    </tr>
    <tr>
      <td>3-5</td>
      <td colspan="2">C PROGRAM</td>
       
      <td >DS</td>
      <td >DS</td>
      <td >C PROGRAM</td>
      
<table>
    <tr>
      <th>S. No.</th>
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
      <td>19AI403</td>
      <td>Introduction To Data Science</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>19AI304</td>
      <td>Fundamentals Of C Programming</td>
    </tr>
     
  </table>

````
# OUTPUT
<img width="1493" height="1113" alt="Screenshot 2025-09-28 162145" src="https://github.com/user-attachments/assets/7a83dec5-4dce-4536-81ec-e0745751a901" />
<img width="1495" height="1106" alt="Screenshot 2025-09-28 162209" src="https://github.com/user-attachments/assets/2a5b50ba-81f7-4d72-9339-a5856a41e342" />
<img width="1322" height="884" alt="Screenshot 2025-09-28 162222" src="https://github.com/user-attachments/assets/8c1b9d48-b08f-48c0-9dfc-75149bdc9131" />
<img width="1919" height="1135" alt="Screenshot 2025-09-28 162244" src="https://github.com/user-attachments/assets/e66e6e3b-ef73-47d1-ae33-61cf8b81950b" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
