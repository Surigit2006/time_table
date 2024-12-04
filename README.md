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
Create a simple table using <table> tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
 M K Suriya prakash
 24901016
 <html>

<head>
    <title>image</title>

</head>
<body>
    <img src="c:\Users\Suriya\Pictures\Screenshots\timetable.png" alt="Company Logo" width="600" height="100" title="Official Logo" />
</body>
<head>
	<style>
        #table1 {
			border-collapse: collapse;
		}
		
		#table1 th, td {
			border: 2.5px solid #100f0f;
			padding: 10px;
			text-align: center;
		}
		
		#table1 th {
			background-color:aqua;
		}
        #table1 td {background-color: beige;}
        #table2 {
			border-collapse: collapse;
		}
		
		#table2 th, td {
			border: 2.5px solid #100f0f;
			padding: 10px;
			text-align: center;
		}
		
		#table2 th {
			background-color:white;
		}
	</style>
</head>
<body>
	<h1>SLOT TIMETABLE M.K.SURIYAPRAKASH(24901016)</h1>
	
	<table id="table1">
		<thead>
			<tr>
				<th>Time</th>
				<th>Monday</th>
				<th>Tuesday</th>
				<th>Wednesday</th>
				<th>Thursday</th>
				<th>Friday</th>
                                <th>Saturday</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<th>8:00 AM - 10:00 AM</th>
				<td>digital</td>
				<td>IOt</td>
				<td>free</td>
				<td>ML</td>
				<td>ML</td>
                <td>free</td>
			</tr>
			<tr>
				<th>10:00 AM - 12:00 AM</th>
				<td>physics</td>
				<td>free</td>
				<td>python</td>
				<td>maths</td>
				<td>web</td>
                                <td>web</td>
			</tr>
            <tr>
                
                <th>12:00PM - 1:00PM</th>
                <td colspan="6">Lunch</td>
            </tr>
            
    
            
			<tr>
				<th>1:00 PM -3:00 PM</th>
				<td>web</td>
				<td>digital</td>
				<td>free</td>
				<td>physics</td>
				<td>python</td>
                <td>maths</td>
			</tr>
			<!-- Add more rows as needed -->
		</tbody>
	</table>
</body>

<body>
	<h1>SUBJECT CODE</h1>
	
	<table id="table2">
		<thead>
			<tr>
				<th>S.No</th>
				<th>Subject Code</th>
				<th>Subject Name</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>1</td>
				<td width="200">SH3214</td>
				<td width="370" >Quantum physics</td>
				
			</tr>
			<tr>
				<td>2</td>
				<td>19MA222</td>
				<td>Maths</td>
				
			</tr>
			<tr>
				<td>3</td>
				<td>19EE404</td>
				<td>digital electronics</td>
				
			</tr>
            <tr>
                <td>4</td>
                <td>19CS420</td>
                <td>IOt</td>
            </tr>
            <tr>
                <td>
                    5
                </td>
                <td>19AI414</td>
                <td>web application</td>

            </tr>
            <tr>
                <td>6</td>
                <td>19AI410</td>
                <td>Mechine learning</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI301</td>
                <td>python programming</td>
            </tr>
        </tbody>
    </table>
</body>        

</html>
# OUTPUT



![Screenshot 2024-12-04 131218](https://github.com/user-attachments/assets/9a1b4f82-8e44-46cf-8b6a-5e6eb187851e)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
