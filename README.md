# Ex03 Time Table
# Date:22/4/25
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table> `tag in html.

## STEP 4
Add header row using` <th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM


```
<html>
    <head>
     <center>  
         <tilte>
            <img src="/static/sec.jpg" alt="sec image"width="700"height="100">
        </tilte>
     </center>
    </head>
    
    <body background="yellow">
        <table border="3"  cellspacing="10" cellpadding="3" align="center">
            <p align="center" > TIMETABLE - ASHWANTH(24900175)</p>
            <tr align="center" bgcolor="beige">
                <th>day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="beige">8-10</td>
                <td bgcolor="orange">FREE SLOT</td>
                <td colspan="2" bgcolor="orange"><center>EDM</center></td>
                <td bgcolor="orange">PHYSICS</td>
                <td colspan="2" bgcolor="orange"><center>FREE SLOT</center></td>
            </tr>
            <tr align="center">
                <td bgcolor="beige">10-12</td>
                <td bgcolor="orange">FWDP</td>
                <td bgcolor="orange">MATHS</td>
                <td bgcolor="orange">C PROG</td>
                <td bgcolor="orange">FREE SLOT</td>
                <td bgcolor="orange">C PROG</td>
                <td bgcolor="orange">DE</td>
            </tr>
            <tr align="center">
                <td bgcolor="beige">12-1</td>
                <td colspan="6" bgcolor="beige"><center>  L U N C H    </center></td>
            </tr>
            <tr align="center">
                <td bgcolor="beige">1-3</td>
                <td bgcolor="orange">DE</td>
                <td bgcolor="orange">FREE SLOT</td>
                <td bgcolor="orange">MENTOR MEET</td>
                <td bgcolor="orange">FWDP</td>
                <td bgcolor="orange">PHYSICS</td>
                <td bgcolor="orange">MATHS</td>
            </tr>
            <tr align="center">
                <td bgcolor="beige">3-5</td>
                <td colspan="4" bgcolor="orange"><center>FREE SLOT</center></td>
                <td bgcolor="orange">CDS</td>
                <td bgcolor="orange">FWDP</td>
            </tr>
        </table>
    <br><br>
           <table border="3" cellspacing="10" cellpadding="3"  align="center" > 
            <tr align="center" bgcolor="beige">
                <th>s.no</th>
                <th>Subject code</th>
                <th>Subject Name</th>
            </tr>
            <tr align="center"bgcolor="cyan" >
                <td bgcolor="beige">1</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling(EDM)</td>
            </tr>
            <tr align="center" bgcolor="cyan">
                <td bgcolor="beige">2</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming(C PROG)</td>
            </tr>
            <tr align="center" bgcolor="cyan">
                <td bgcolor="beige">3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application(FWDP)</td>
            </tr>
            <tr align="center"bgcolor="cyan" >
                <td bgcolor="beige">4</td>
                <td>19EE404</td>
                <td>Digital Electronics(DE)</td>
            </tr>
            <tr align="center"bgcolor="cyan" >
                <td bgcolor="beige">5</td>
                <td>19EY708</td>
                <td>Career Development Skills(CDS)</td>
            </tr>
            <tr align="center"bgcolor="cyan" >
                <td bgcolor="beige">6</td>
                <td>19MA201</td>
                <td >Calculus and Matrix Algebra(MATHS)</td>
            </tr>
            <tr align="center" bgcolor="cyan">
                <td bgcolor="beige">7</td>
                <td>SH3214</td>
                <td>Physics for Quantum Computing(PHYSICS)</td>
            </tr>
            <tr align="center" bgcolor="cyan">
                <td bgcolor="beige">8</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet(SCOFT)</td>
            </tr>
        </table>
        <br>
        <hr>

    </body>
</html>
```
# OUTPUT
![WhatsApp Image 2025-04-23 at 6 09 39 PM](https://github.com/user-attachments/assets/99a5fa2c-37e3-4f9e-baac-5b0dcb94b5d7)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
