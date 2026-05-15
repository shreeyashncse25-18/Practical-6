<!DOCTYPE html>
<html>
<head>
    <title>Scholarship Registration Form</title>
</head>

<body bgcolor="lightblue">

    <h1 align="center" style="background-color:darkblue; color:white;">
        Scholarship / Seminar Registration Form
    </h1>

    <hr>

    <fieldset>
        <legend><b>Personal Details</b></legend>

        <b>Full Name :</b>
        <input type="text" name="fullname" placeholder="Enter your name">
        <br><br>

        <b>Email ID :</b>
        <input type="email" name="email" placeholder="Enter email">
        <br><br>

        <b>Mobile No :</b>
        <input type="text" name="mobile" placeholder="Enter mobile number">
        <br><br>

        <b>Date of Birth :</b>
        <input type="date" name="dob">
        <br><br>
    </fieldset>

    <br>

    <fieldset>
        <legend><b>Academic Details</b></legend>

        <b>Roll Number :</b>
        <input type="text" name="rollno">
        <br><br>

        <b>Department :</b>
        <select name="dept">
            <option>--Select--</option>
            <option>Computer Science</option>
            <option>Mechanical</option>
            <option>Civil</option>
            <option>Electronics</option>
        </select>
        <br><br>

        <b>Year :</b>
        <select name="year">
            <option>--Select Year--</option>
            <option>First Year</option>
            <option>Second Year</option>
            <option>Third Year</option>
            <option>Fourth Year</option>
        </select>
        <br><br>
    </fieldset>

    <br>

    <fieldset>
        <legend><b>Gender</b></legend>
        <input type="radio" name="gender" value="male"> Male &nbsp;
        <input type="radio" name="gender" value="female"> Female &nbsp;
        <input type="radio" name="gender" value="other"> Other
    </fieldset>

    <br>

    <fieldset>
        <legend><b>Topics Interested In</b></legend>
        <input type="checkbox"> Web Development &nbsp;
        <input type="checkbox"> Artificial Intelligence <br><br>
        <input type="checkbox"> Cloud Computing &nbsp;
        <input type="checkbox"> Cyber Security
    </fieldset>

    <br>

    <fieldset>
        <legend><b>Scholarship Category</b></legend>

        <b>Apply For :</b>
        <select name="scholarship">
            <option>--Select--</option>
            <option>Merit Based</option>
            <option>Need Based</option>
            <option>Sports Quota</option>
            <option>Government Scholarship</option>
        </select>
        <br><br>

        <b>Remarks :</b><br>
        <textarea rows="4" cols="40" placeholder="Write here..."></textarea>
        <br><br>

        <input type="submit" value="Submit Form"> &nbsp;
        <input type="reset" value="Clear Form">
    </fieldset>

</body>
</html>
