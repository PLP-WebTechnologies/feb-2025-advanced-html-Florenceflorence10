# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

ANSWER
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Document</title>
</head>
<body>
    <!-- Ordered list with Roman numerals -->
    <section>
        <h1>Roman Numerals List</h1>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
        </ol>
    </section>

    <!-- External image from Pexels -->
    <section>
        <h1>Beautiful Image</h1>
        <img src="https://images.pexels.com/photos/248797/pexels-photo-248797.jpeg" alt="Nature View" width="600">
    </section>

    <!-- Table of 5 contacts -->
    <section>
        <h1>Contact List</h1>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Elm Street</td>
                <td>+123456789</td>
                <td>john.doe@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Avenue</td>
                <td>+987654321</td>
                <td>jane.smith@example.com</td>
            </tr>
            <tr>
                <td>Mike Johnson</td>
                <td>789 Pine Road</td>
                <td>+192837465</td>
                <td>mike.johnson@example.com</td>
            </tr>
            <tr>
                <td>Susan Lee</td>
                <td>321 Maple Blvd</td>
                <td>+564738291</td>
                <td>susan.lee@example.com</td>
            </tr>
            <tr>
                <td>Emma Brown</td>
                <td>654 Cedar Lane</td>
                <td>+748392016</td>
                <td>emma.brown@example.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration form -->
    <section>
        <h1>Registration Form</h1>
        <form>
            <!-- Name field -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <br><br>

            <!-- Email field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            <br><br>

            <!-- Date field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown -->
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <!-- Radio buttons -->
            <label>Subscription Plan:</label><br>
            <input type="radio" id="free" name="plan" value="free">
            <label for="free">Free</label><br>
            <input type="radio" id="premium" name="plan" value="premium">
            <label for="premium">Premium</label>
            <br><br>

            <!-- Checkboxes -->
            <label>Interests:</label><br>
            <input type="checkbox" id="coding" name="interest" value="coding">
            <label for="coding">Coding</label><br>
            <input type="checkbox" id="gaming" name="interest" value="gaming">
            <label for="gaming">Gaming</label><br>
            <input type="checkbox" id="traveling" name="interest" value="traveling">
            <label for="traveling">Traveling</label>
            <br><br>

            <!-- Submit button -->
            <button type="submit">Register</button>
        </form>
    </section>
</body>
</html>


