# Application
<!DOCTYPE html> 
<html>
<head>
    <title>Job Application</title>
</head>
    
<body style=" margin-left: 20mm; margin-right: 20mm; margin-top: 15mm; margin-bottom: 25mm;">
<h2>Job Application Form</h2>
<p style="font-size: 20px;">Complete the below form</p>
<form action="/action_page.php">
<form> 
<!-- Name-->

    <label for="fname">Given name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Family name:</label><br>
    <input type="text" id="lname" name="lname"><br><hr>

<!-- Gender-->

<p> Please choose your gender</p>    
    <input type="radio" id="male" name="gender" value="Male">
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="Female">
    <label for="Female">Female</label><br>
    <input type = "radio" id ="non" name="gender" value="Perfer not to say">
    <label for="non">Prefer not to say</label><hr>

<!-- Date of birth-->

<h2 style="font-size: larger;"><label for="DoB">Date of birth</label></h2><br>
    <input type="date" id="DoB" name="DoB"><br><hr>

<h2 style="font-size: larger;">Proficiency</h2>

<!-- Roles -->

    <label for="skill">Please choose one role.</label><br>
    <input type="radio" id="skill" name="profession" value="General Manager">
    <label for="General Manager">General Manager</label><br>
    <input type="radio" id="skill" name="profession" value="Project Lead">
    <label for="Project Lead">Project Lead</label><br>
    <input type="radio" id="skill" name="profession" value="Finance">
    <label for="finance">Psychology Specialist</label><br><hr>

<!-- Experience -->

    <h2 style="font-size: larger;"><label for="experience">Year(s) of experience.</label></h2><br>
    <input type="text" id="experience" name="experience">

<!-- Salary -->

    <h2 style="font-size: larger;"><label for="experience">Previous salary</label></h2><br>
    <input type="text" id="experience" name="experience">

    <h2 style="font-size: large;"><label for="experience">Expected salary for the chosen role.</label></h2><br>
    <input type="text" id="experience" name="experience"><br><hr>

<!-- Educational background -->

<h2 style="font-size: larger;">Educational Background</h2>
    <label for="educational background">University</label><br>
    <input type="text" id="educational background" name="educational background"><br>
    <label for="educational background">Year Graduation</label><br>
    <input type="text" id="educational background" name="educational background"><br>
    <label for="educational background">Level of Education</label><br>
    <input type="text" id="educational background" name="educational background"><br>
    <label for="educational background">Internship Experience</label><br>
    <input type="text" id="educational background" name="educational background"><br><hr>

<!-- Interview -->

<h2 style="font-size: larger;">Interview</h2>
    <label for="skill">Please choose two of the given date and time.</label><br>
    <input type="checkbox" id="Interview1" name="interview1" value="24-Sept-2023, 15pm-15:25pm">
    <label for="Interview1">24-Sept-2023, 15pm-15:25pm</label><br>
    <input type="checkbox" id="Interview2" name="interview2" value="25-Sept-2023, 14pm-14:25pm">
    <label for="Interview1">25-Sept-2023, 14pm-14:25pm</label><br>
    <input type="checkbox" id="Interview3" name="interview3" value="25-Sept-2023, 15:35pm-16pm">
    <label for="Interview1">25-Sept-2023, 15:35pm-16pm</label><br><hr>

    <P style="font-size: 15px; font-family: Verdana, Geneva, Tahoma, sans-serif;">Should you have any question, kindly let us know.</P>
    <input type="text" id="question" name="question"><hr>
  


</form>
<footer>
    <p style="font-size: larger; font-style: normal;">Published by The Mental-Ed team</p>
    <p style="font-size: large;">Email: <a href="the.mental.ed@gmail.com" style="color:red ;">the.mental.ed@gmail.com</a></p>
    <p style="font-size: large;">Contact: <a href="tel:+885 98 345 234">(+885) 98 345 234</a></p>
</footer>

</body>

</html>
