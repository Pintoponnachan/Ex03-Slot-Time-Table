# Ex03 Time Table
## Date:
16/09/2023

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
```html
<!doctype html>
<html>
  <head bg=""C:\Users\SEC\Downloads\logo.png"">
    <title>Slot time table</title>
  </head>
  <body>
    <img src="logo.png" >
    <h2 align="center"> <b>Slot time table-Pinto ponnachan(212221040121)</b></h2>
    <table bgcolor="white" align="center" border="15" cellpadding="15" cellspacing="4">
      <tr bgcolor="#7fffd4">
        <th>Day/time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
      </tr>
      <tr>
        <td bgcolor="f8f6f0">
          8-10
        </td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="c77cfa">Mobile computing</td>
        <td bgcolor="#ccccff">MPMC</td>
        <td bgcolor="#fdd7e4">WEB</td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="#fdd7e4">WEB</td>
      </tr>
      <tr>
        <td bgcolor="f8f6f0">10-12</td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="99c68e">MAD</td>
        <td bgcolor="87ceCC">game programming</td>
        <td bgcolor="ccccff">MPMC</td>
        <td bgcolor="87cefa">CNS</td>
      </tr>
      <tr>
        <td bgcolor="f8f6f0">12-1</td>
        <td bgcolor="dbf9db" colspan="6">LUNCH</td>
      </tr>
      <tr>
        <td bgcolor="f8f6f0">1-3</td>
        <td bgcolor="ccccff">MPMC</td>
        <td bgcolor="99c68e">MAD</td>
        <td bgcolor="87ceCC">Game programming</td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="#faf0dd">CD</td>
        <td bgcolor="87cefa">FREE SLOT</td>
      </tr>
      <tr>
        <td bgcolor="f8f6f0">4-5</td>
        <td bgcolor="87cefa">CNS</td>
        <td bgcolor="#fdd7e4">WEB</td>
        <td bgcolor="#faf0dd">CD</td>
        <td bgcolor="87cefa">FREE SLOT</td>
        <td bgcolor="c77cfa">Mobile computing</td>
        <td bgcolor="87cefa">FREE SLOT</td>
      </tr>
    </table>
  </body>
</html>
<br>
    <table bgcolor="white" align="center" border="10" cellpadding="10" cellspacing="4">
      <tr>
        <th>S.NO</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
      </tr>
      <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development(WEB)</td>
      </tr>
      <tr>
        <td>2.</td>
        <td>19CS409</td>
        <td>Compiler design(CD)</td>
      </tr>
      <tr>
        <td>3.</td>
        <td>19CS414</td>
        <td>Mobile application development(MAD)</td>
      </tr>
      <tr>
        <td>4.</td>
        <td>19CS412</td>
        <td>Cryptography and network security(CNS)</td>
      </tr>
      <tr>
        <td>5.</td>
        <td>19EC408</td>
        <td>Microprocessor and microcontroller(MPMC)</td>
      </tr>
      <tr>
        <td>6.</td>
        <td>19AI513</td>
        <td>Game programming</td>
        <tr>
          <td>7.</td>
          <td>19CS517</td>
          <td>Mobile computing</td>
        </tr>
```


## OUTPUT
![image](https://github.com/Pintoponnachan/Ex03-Slot-Time-Table/assets/131936892/b4855fa3-a70e-4f34-8e67-2dc8d133475a)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
