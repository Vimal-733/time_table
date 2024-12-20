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
<!DOCTYPE html>
<html lang="en-us">
<head>
    <title>Time Table</title>
    <style>
        /* Faded background color */
        body {
            background: linear-gradient(45deg, #f0f8ff, #e6e6fa);
            font-family: Arial, sans-serif;
            color: black;
            margin: 0;
            padding: 0;
        }

        /* Header Image */
        header img {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
        }

        /* Table Styles */
        table {
            border: 2px solid #000;
            border-collapse: collapse;
            margin: 20px auto;
            text-align: center;
            width: 90%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Table header with bright colors */
        th {
            background-color: #ffcc00; /* Bright yellow */
            color: #000; /* Black text for contrast */
            padding: 10px;
        }

        /* Table rows with alternating bright colors */
        td {
            background-color: #ff5733; /* Bright orange for data cells */
            color: white;
            padding: 10px;
        }

        /* Lunch column for clarity */
        td[rowspan] {
            background-color: #c70039; /* Bright red */
            color: white;
            font-weight: bold;
        }

        /* Subtle hover effect on table rows */
        tr:hover td {
            background-color: #ffc300; /* Bright gold when hovered */
            color: black;
        }

        /* Second table (subject codes) styles */
        .ta2 {
            border: 2px solid #000;
            border-collapse: collapse;
            margin: 20px auto;
            width: 80%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .ta2 th {
            background-color: #00bfff; /* Bright cyan for headers */
            color: black;
            padding: 10px;
        }

        .ta2 td {
            background-color: #ff5733; /* Bright orange for cells */
            color: white;
            padding: 10px;
        }

        /* Heading style */
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
            text-shadow: 0 1px 2px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <!-- Header with College Logo -->
    <header>
        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-11-29 100432.png" alt="Saveetha Engineering College Logo">
    </header>

    <!-- Timetable -->
    <h1>Time Table</h1>
    <table>
        <tr>
            <th>Day/Period</th>
            <th>1 <br> 8.00-10.00</th>
            <th>2 <br> 10.00-12.00</th>
            <th>3 <br> 12.00-1.00</th>
            <th>4 <br> 1.00-3.00</th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>Free</td>
            <td>Free</td>
            <td rowspan="6">LUNCH</td>
            <td>Web Application</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td>chemistry</td>
            <td>Physics</td>
            <td>C Programming</td>
        </tr>    
        <tr>
            <th>Wednesday</th>
            <td>free</td>
            <td>Digital electronics</td>
            <td>Mentor Meet</td>
        </tr>   
        <tr>
            <th>Thursday</th>
            <td>free</td>
            <td>C Programming</td>
            <td>chemistry</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>Phy</td>
            <td>Web Application</td>
            <td>human values and professional ethics</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td>Digital electronics</td>
            <td>Web Application</td>
            <td>career development skills</td>
        </tr>
    </table>

    <!-- Subject Codes Table -->
    <table class="ta2">
        <tr>
            <th>S.NO</th>
            <th>SUB CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>SH3214</td>
            <td>Physics For Quantum Computing</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>3</td>
            <td>SH7801</td>
            <td>human values and professional ethics </td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI304</td>
            <td>Fundamentals of C Programming</td>
        </tr>
        <tr>
            <td>7</td>
            <td>19CY205</td>
            <td>chemistry</td>
        </tr>
    </table>
</body>
</html>

# OUTPUT
![Screenshot 2024-11-29 103933](https://github.com/user-attachments/assets/5dc4d979-9241-4597-b534-f537c6c56818)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
