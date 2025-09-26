# My-Second-project-
My second project 
<!DOCTYPE html>
<html>
<head>
    <title>Students Registration Form</title>
</head>
<body>
    <h1 style="text-align:center;">Students Registration Form</h1>

    <form>
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your full name"><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone" placeholder="Enter your phone number"><br><br>

        <label for="course">Course:</label><br>
        <select id="course" name="course">
            <option value="bca">BCA</option>
            <option value="bsc">BSc</option>
            <option value="bcom">BCom</option>
        </select><br><br>

        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="address">Address:</label><br>
        <textarea id="address" name="address" placeholder="Enter your address"></textarea><br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>
