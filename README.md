# Registration-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>

    <h2>Registration Form</h2>

    <form action="#" method="post">
        <!-- Name Input -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <!-- Email Input -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br><br>

        <!-- Gender Dropdown -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select><br><br>

        <!-- Date of Birth Input -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>

</body>
</html>

Event Registration form
