# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
'''
Home page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Day Events - Saveetha Engineering College</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>SPORTS DAY EVENTS</h1>
        </header>
        <main>
            <div class="college-info">
                <img src="exp9.png" alt="Saveetha Engineering College Logo" class="logo">
                <h2>SAVEETHA ENGINEERING COLLEGE</h2>
                <p>BE THE BEST 2001</p>
            </div>
            <div class="buttons">
                <button class="btn login-btn">LOGIN</button>
                <button class="btn register-btn">REGISTER</button>
            </div>
        </main>
        <footer>
            <p>"BORN TO WIN"</p>
        </footer>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f0f2f5; /* Light grey background */
}

.container {
    background-color: #aadde6; /* Light blue background for the main content area */
    width: 90%;
    max-width: 400px;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

header h1 {
    background-color: #c0392b; /* Red background for header */
    color: white;
    padding: 10px 0;
    margin-bottom: 20px;
    border-radius: 5px;
    font-size: 1.5em;
}

.college-info {
    margin-bottom: 30px;
}

.college-info .logo {
    width: 100px;
    height: 100px;
    border-radius: 50%; /* Placeholder for a circular logo */
    margin-bottom: 10px;
    border: 2px solid #2c3e50; /* Dark border for logo */
}

.college-info h2 {
    color: #2c3e50; /* Dark blue text */
    margin: 10px 0 5px;
}

.college-info p {
    color: #555;
    font-size: 0.9em;
}

.buttons .btn {
    display: block;
    width: 80%;
    padding: 12px;
    margin: 15px auto;
    border: none;
    border-radius: 5px;
    font-size: 1.1em;
    cursor: pointer;
    transition: background-color 0.3s ease;
    color: white;
}

.login-btn {
    background-color: #c0392b; /* Red login button */
}

.register-btn {
    background-color: #c0392b; /* Red register button */
}

.btn:hover {
    opacity: 0.9;
}

footer p {
    margin-top: 30px;
    color: #7f8c8d; /* Grey text for footer */
    font-style: italic;
    font-size: 0.8em;
}

page 2

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Day Events</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>SPORTS DAY EVENTS</h1>
        <ul>
            <li>→ CRICKET</li>
            <li>→ BADMINTON</li>
            <li>→ VOLLEY BALL</li>
            <li>→ 100MTS</li>
            <li>→ 200MTS</li>
            <li>→ 400MTS</li>
            <li>→ 4*100 RELAY</li>
        </ul>
        <div class="logo">
            <img src="exp9.1.png" alt="Sports Burst Logo">
            <p>SPORTS BURST</p>
        </div>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

.container {
    background-color: #fff;
    padding: 30px 50px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

h1 {
    color: #333;
    margin-bottom: 20px;
}

ul {
    list-style: none; /* Remove default bullet points */
    padding: 0;
    text-align: left;
    margin-bottom: 30px;
}

li {
    margin-bottom: 10px;
    color: #555;
    font-size: 1.1em;
}

.logo img {
    max-width: 150px;
    height: auto;
    margin-bottom: 10px;
}

.logo p {
    font-size: 1.2em;
    font-weight: bold;
    color: #e44d26; /* Example color, adjust as needed */
    margin: 0;
}

page 3

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>EVENT REGISTRATION FORM</h1>
        <p>Fill the Details</p>
        <form>
            <div class="input-group">
                <label for="fullName">Full Name</label>
                <input type="text" id="fullName" name="fullName" required>
            </div>
            <div class="input-group">
                <label for="gender">Gender</label>
                <input type="text" id="gender" name="gender" required>
            </div>
            <div class="input-group">
                <label for="age">Age</label>
                <input type="number" id="age" name="age" required>
            </div>
            <div class="input-group">
                <label for="registerNumber">Register Number</label>
                <input type="text" id="registerNumber" name="registerNumber" required>
            </div>
            <div class="input-group">
                <label for="department">Department</label>
                <input type="text" id="department" name="department" required>
            </div>
            <div class="input-group">
                <label for="mobileNumber">Mobile Number</label>
                <input type="tel" id="mobileNumber" name="mobileNumber" required>
            </div>
            <div class="input-group">
                <label for="email">Email ID</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="input-group">
                <label for="eventsToRegister">Events to register</label>
                <input type="text" id="eventsToRegister" name="eventsToRegister">
            </div>
            <button type="submit" class="register-button">REGISTER</button>
        </form>
    </div>
</body>
</html>

body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(to right, #4CAF50, #2196F3); /* Example gradient background */
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.container {
    background-color: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 400px;
    text-align: center;
}

h1 {
    color: #333;
    margin-bottom: 5px;
}

p {
    color: #666;
    margin-bottom: 20px;
}

.input-group {
    margin-bottom: 15px;
    text-align: left;
}

.input-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #555;
}

.input-group input[type="text"],
.input-group input[type="number"],
.input-group input[type="tel"],
.input-group input[type="email"] {
    width: calc(100% - 20px); /* Adjust for padding */
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box; /* Include padding and border in the element's total width and height */
}

.register-button {
    background-color: #a80101ff; /* Reddish color similar to the image */
    color: white;
    padding: 15px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    width: 100%;
    margin-top: 20px;
}

.register-button:hover {
    background-color: #a80303ff;
}

'''
# OUTPUT:
<img width="1017" height="582" alt="NITHI FIGMA" src="https://github.com/user-attachments/assets/fc5dee2c-5e66-4228-a91f-5b4fe801cce5" />

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
