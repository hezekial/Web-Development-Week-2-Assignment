# Web-Development-Week-2-Assignment

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Week 2 Assignment</title>
</head>
<body>

    <!-- Ordered list with Roman numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>Kenya<li>Uganda<li>Tanzania<li>Rwanda</li></li></li></li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/541484/sun-flower-blossom-bloom-pollen-541484.jpeg" alt="Nature Image" width="600">

    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Contact No.</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Ken Wenger</td>
                <td>Nairobi, Kenya</td>
                <td>+25424724712</td>
                <td>kenwenger@jkia.com</td>
            </tr>
            <tr>
                <td>Abigael Wenger</td>
                <td>Kisii, Kenya</td>
                <td>+25447866621</td>
                <td>Abiwenger@lolo.com</td>
            </tr>
            <tr>
                <td>Michael Owen</td>
                <td>London, UK</td>
                <td>+1 287 288288</td>
                <td>owenmichael@go.uk</td>
            </tr>
            
        </tbody>
    </table>

      <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit_registration" method="post">
        
        <!-- Name Field -->
        <div class="form-group">
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        </div>
        <br><br>

        <!-- Email Field -->
        <div class="form-group">
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required>
        </div>
        <br><br>
        <!-- Password Field -->
        <div class="form-group">
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
        </div>
        <br><br>
        <!-- Date of Birth Field -->
        <div class="form-group">
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required>
        </div>
        <br><br>

        <!-- Dropdown (Select) -->
        <div class="form-group">
            <label for="country">Country:</label><br>
            <select id="country" name="country" required>
                <option value="" disabled selected>Select your country</option>
                <option value="usa">United States</option>
                <option value="uk">United Kingdom</option>
                <option value="india">India</option>
                <option value="australia">Australia</option>
            </select>
        </div>
        <br><br>

        <!-- Radio Buttons -->
        <div class="form-group">
            <label>Gender:</label>
            <label for="male">
                <input type="radio" id="male" name="gender" value="male" required> Male
            </label>
            <label for="female">
                <input type="radio" id="female" name="gender" value="female" required> Female
            </label>
            <label for="other">
                <input type="radio" id="other" name="gender" value="other" required> Other
            </label>
        </div>
        <br><br>
        <!-- Checkboxes -->
        <div class="form-group">
            <label for="terms">I agree to the terms and conditions.
                <input type="checkbox" id="terms" name="terms" required> 
            </label>
        </div>
        <br><br>
        <!-- Submit Button -->
        <div class="form-group">
            <input type="submit" value="Register">
        </div>
        
    </form>

</body>
</html>
