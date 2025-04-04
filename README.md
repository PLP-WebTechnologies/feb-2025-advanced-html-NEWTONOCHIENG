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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML5 Example</title>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Welcome to My HTML5 Demo Page</h1>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Roman Numeral List</h2>
    <ol type="I">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ol>
  </section>

  <!-- External Image -->
  <section>
    <h2>Sample Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Nature View" width="500">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact List</h2>
    <table border="1" cellpadding="10">
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Alice Smith</td>
          <td>Nairobi, Kenya</td>
          <td>+254712345678</td>
          <td>alice@example.com</td>
        </tr>
        <tr>
          <td>Bob Kimani</td>
          <td>Mombasa, Kenya</td>
          <td>+254722345678</td>
          <td>bob@example.com</td>
        </tr>
        <tr>
          <td>Carol Wanjiku</td>
          <td>Kisumu, Kenya</td>
          <td>+254733345678</td>
          <td>carol@example.com</td>
        </tr>
        <tr>
          <td>David Otieno</td>
          <td>Nakuru, Kenya</td>
          <td>+254744345678</td>
          <td>david@example.com</td>
        </tr>
        <tr>
          <td>Emily Njeri</td>
          <td>Eldoret, Kenya</td>
          <td>+254755345678</td>
          <td>emily@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="/submit" method="post">
      <!-- Name -->
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

      <!-- Email -->
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter a valid email" required><br><br>

      <!-- Password -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Choose a strong password" minlength="6" required><br><br>

      <!-- Date -->
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required><br><br>

      <!-- Dropdown -->
      <label for="country">Country:</label>
      <select id="country" name="country" required>
        <option value="">Select your country</option>
        <option value="kenya">Kenya</option>
        <option value="uganda">Uganda</option>
        <option value="tanzania">Tanzania</option>
      </select><br><br>

      <!-- Radio Buttons -->
      <label>Gender:</label><br>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female" required>
      <label for="female">Female</label><br><br>

      <!-- Checkboxes -->
      <label>Hobbies:</label><br>
      <input type="checkbox" id="reading" name="hobbies" value="reading">
      <label for="reading">Reading</label><br>
      <input type="checkbox" id="traveling" name="hobbies" value="traveling">
      <label for="traveling">Traveling</label><br>
      <input type="checkbox" id="sports" name="hobbies" value="sports">
      <label for="sports">Sports</label><br><br>

      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Multimedia Section -->
  <section>
    <h2>Multimedia</h2>

    <!-- Audio -->
    <h3>Sample Audio</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <!-- Video -->
    <h3>Sample Video</h3>
    <video controls width="500" autoplay muted>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My HTML5 Demo Page</p>
  </footer>

</body>
</html>
Happy Coding! 💻✨
