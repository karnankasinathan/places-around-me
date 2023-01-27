# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the git repository into Theia IDE

### Step 2:
Create a new Django project.

### step 3:
Write the needed HTML code.

### step 4:
Run the Django server and execute the HTML files.
## Code:
```html
map.html :
         <!DOCTYPE html>
<html>
    <head>
        <title>Map Of SEC</title>
    </head>
    <body>
        <map name="image-maps-2023-01-10-171049" id="ImageMapsCom-image-maps-2023-01-10-171049">
            <area  alt="Admin Block" title="Admin Block" href="http://matharaj.student.saveetha.in/admin1" shape="rect" coords="382,224,654,347" style="outline:none;" target="_self"     />
            <area  alt="Cse Block" title="Cse Block" href="http://mathanraj.student.saveetha.in/cse" shape="rect" coords="658,208,930,338" style="outline:none;" target="_self"     />
            <area  alt="Ece Block" title="Ece Block" href="http://mathanraj.student.saveetha.in/ece" shape="rect" coords="230,209,375,339" style="outline:none;" target="_self"     />
            <area  alt="EEE Block" title="EEE Block" href="http://mathanraj.student.saveetha.in/eee" shape="rect" coords="194,186,238,316" style="outline:none;" target="_self"     />
            <area  alt="Rectangular Bloak" title="Rectangular Bloak" href="http://dario.student.saveetha.in/rb" shape="rect" coords="0,168,191,281" style="outline:none;" target="_self"     />
            <area  alt="SEC Girls Hostel" title="SEC Girls Hostel" href="http://dario.student.saveetha.in/girls" shape="rect" coords="939,171,939,175" style="outline:none;" target="_self"     />
            <area  alt="SEC Girls Hostel" title="SEC Girls Hostel" href="http://mathanraj.student.saveetha.in/girls" shape="rect" coords="840,123,1020,175" style="outline:none;" target="_self"     />
            <area  alt="SEC Boys Hostel" title="SEC Boys Hostel" href="http://mathanraj.student.saveetha.in/boys" shape="rect" coords="559,120,715,171" style="outline:none;" target="_self"     />
            <area shape="rect" coords="1023,553,1025,555" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>
        <img id="Image-Maps-Com-image-maps-2023-01-10-171049" src="http://dario.student.saveetha.in:8080/mini-browser/home/project/places-around-me/placeproj/static/images/SEC_Img.png" border="0" width="1025" height="555" orgWidth="1025" orgHeight="555" usemap="#image-maps-2023-01-10-171049" alt="" />

    </body>
</html>


1. rb.html :
        <!DOCTYPE html>
<html>
    <head>
        <title>Rectangular Block</title>

    </head>
    <body>
        <p><b>Rectangular Block</b> Consist Of : <br>Mechanical Departmentk<br>Chemical Engineering Department<br>
            
        </p>
        <p>
            Mechanical engineering is the study of physical machines that may involve force and movement.<br>
            It is an engineering branch that combines engineering physics and<br>
            mathematics principles with materials science, <br>
            to design, analyze, manufacture, and maintain mechanical systems.<br>
            It is one of the oldest and broadest of the engineering branches.
        </p>
    </body>
</html>

2. g.html :
          <!DOCTYPE html>
<html>
    <head>
        <title>SEC Girls Hostel</title>

    </head>
    <body>
        <h2>SEC Girls Hostel</h2>
        <p>
            A Girld hostel is a lower-priced inn of sorts that offers basic,<br>
            shared accommodations. Typically, a hostel features a large room with separate beds,<br>
            a shared bathroom, and a communal kitchen. Some hostels have private rooms,<br>
            but the lower-cost ones generally offer bunk beds.
        </p>
    </body>
</html>


3. eee.html :
            <!DOCTYPE html>
<html>
    <head>
        <title>EEE Block</title>

    </head>
    <body>
        <h2>Electrical and Electronics Block</h2>
        <p>
            The department of Electrical and Electronics Engineering (EEE) is one of the <br>
            two oldest departments of the institution spanning 75 years of existence<br>
            which offers undergraduate programme B.E-EEE (and two post graduate programmes Power Systems Engineering and Power Electronics and Drives)<br>
            and research programme.
            
        </p>
    </body>
</html>

4.ece.html :
           <!DOCTYPE html>
<html>
    <head>
        <title>ECE Block</title>

    </head>
    <body>
        <h2>Electronics and Communication Block</h2>
        <p>It has an array of courses for students to choose and study such as power electronics, <br>
            information technology, electronic hardware and software, automation, robotics and <br>
            control, communications, radio and television, computer engineering, solid – state devices, <br>
            microelectronics, VLSI and other circuits & systems used ...
            
        </p>
    </body>
</html>

5. cse.html :
            <!DOCTYPE html>
<html>
    <head>
        <title>CSE Block</title>

    </head>
    <body>
        <p><b>CSE Block</b> Consist Of : <br> IT Deparment <br> CSE Department <br> AI&DS Department <br> IOT Department<br>AIML Department<br>
            Cyber Security Department <br>
            
        </p>
        <p>
            The Department of Computer Science & Engineering (CSE) was established in the year 1997 affiliated to Madras University.<br>
            The department has grown to current strength of 2700 students from a humble beginning with 250 students.<br>
            The department is equipped with the latest state-of- the-art laboratories.
        </p>
    </body>
</html>


6.b.html :
         <!DOCTYPE html>
<html>
    <head>
        <title>SEC Boys Hostel</title>

    </head>
    <body>
        <h2>SEC Boys Hostel</h2>
        <h3><b>8 things that happen in boys hostel</b></h2>
        <ol>
            <li>Introduction. ...</li>
            <li>Violent birthday celebrations. ...</li>
            <li>All night gaming. ...</li>
            <li>Bathroom singing at its best. ...</li>
            <li>The troublemakers creating fuss. ...</li>
            <li>The bullies making life tough for juniors. ...</li>
            <li>The romeos of the hostel. ...</li>
            <li>The long, long gossip sessions.</li>
        </ol>
    </body>
</html>

7. admin1.html :
               <!DOCTYPE html>
<html>
    <head>
        <title>Admin Block</title>

    </head>
    <body>
        <p><b>Admin Block</b> Consist Of : <br> Exam Cell <br> Management Cell <br> MBA Block <br> Principal Office<br>and Bio Medical Block<br>
            
        </p>
    </body>
</html>
```
## Output:

     
     
     
     
     
     






## Result:
Write your result
