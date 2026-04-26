# Ex02 Time Table

NAME:SIVA SHALINI.S
ROLL.NO: 212224240154

# Date:26/04/26

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

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
            border-collapse: collapse;
            margin: 20px auto;
            width: 80%;
        }

        th,
        td {
            border: 3px solid black;
            padding: 10px;
            text-align: center;
        }

        th {
            background: pink;
        }
        td{
            background: red;
        }
      
        }
       body{
            background-color: blue;
        }
    </style>
</head>

<body>

    <img src="https://kommodo.ai/i/xFrDZmXRMtJPnF6cT76i" width="600" height="100">

    <h2>SLOT TIME TABLE - SIVA SHALINI.S 212224240154</h2>


    <table>
        <tr>
            <th>Day and Time</th>
            <th>8 to 10</th>
            <th>10 to 12</th>
            <th> lunch </th>
            <th> 1 to 3</th>
            <th> 3 to 5</th>
        </tr>
        <tr>
            <th> Monday</th>
            <td> FWd </td>
            <td> FC </td>
            <td> lunch </td>
            <td> FC </td>
            <td> FC </td>
        </tr>
        <tr>
            <th> Tuesday </th>
            <td> FC </td>
            <td> FC </td>
            <td> lunch </td>
            <td> FWAD </td>
            <td> Python </td>
        </tr>
        <tr>
            <th> Wednesday</th>
            <td> FC </td>
            <td> FWAD </td>
            <td> lunch </td>
            <td> MMEET </td>
            <td> Python </td>
        </tr>
        <tr>
            <th> Thursday</th>
            <td> FC </td>
            <td> Python </td>
            <td> lunch</td>
            <td> FC </td>
            <td> FC </td>
        </tr>
        <tr>
            <th> Friday</th>
            <td> FC </td>
            <td> FWAD</td>
            <td> lunch </td>
            <td> FC </td>
            <td> FC </td>
        </tr>
        <tr>
            <th> Saturday </th>
            <td> FC </td>
            <td> Python </td>
            <td> lunch </td>
            <td> FC </td>
            <td> FC </td>
    </table>
</body>

</html>

```


# OUTPUT


<img width="865" height="720" alt="image" src="https://github.com/user-attachments/assets/73bd8cd5-b6f2-447c-b356-c8bf20445339" />


# RESULT

The program for creating slot timetable using basic HTML tags is executed successfully.
