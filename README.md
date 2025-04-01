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

<!DOCTYPE html>
<html>
  <head>
    <title>Week 2 Web development</title>
  </head>
  <body>
    <h1>Creating an ordered list</h1>
    <p>Following is an ordered list using roman numericals</p>
    <ol type="i">
      <li>I am tech trillionare</li>
      <li>The worst I can do is an advancing billionare</li>
      <li>Millionare is not an option</li>
    </ol>
    <h2>I am now attaching a picture from pexels.com</h2>
    <img src="Week 2/istockphoto-1457441464-612x612.jpg" alt="A private jet" width="500" height="200">
    <h2>Here is our table</h2>

    <!-- I specify that I want a table with a boarder as an attribute -->
     <table boarder="2">
      <!-- I then define a row where we will enter all our findings -->
      <thead>
        <tr>
          <th>Name</th>
          <th>Adress</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Anderson</td>
          <td>534,Oakland</td>
          <td>123456789</td>
          <td>abcde@gmail.com</td>
        </tr>
        <tr>
          <td>Veronica</td>
          <td>534,Menosota</td>
          <td>123456789</td>
          <td>abcde@gmail.com</td>
        </tr>
        <tr>
          <td>GOAT</td>
          <td>534,Washington</td>
          <td>123456789</td>
          <td>abcde@gmail.com</td>
        </tr>
        <tr>
          <td>John</td>
          <td>534,California</td>
          <td>123456789</td>
          <td>abcde@gmail.com</td>
        </tr>
        <tr>
          <td>Onkangi</td>
          <td>534,New York</td>
          <td>123456789</td>
          <td>abcde@gmail.com</td>
        </tr>
      </tbody>
       
       
     </table>
     <h3>Registration form</h3>
     <!-- Name Field -->
      <label for="name" >Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required>
      <br><br>
      <!-- Email Field -->
       <label for="email">Email:</label>
       <input type="email" id="email" name="email" placeholder="sdsdds@gmaol.com" required>
       <br><br>
       <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br><br>
        <!-- Date Field -->
         <label for="dob">Date of Birth</label>
         <input type="date" id="dob" name="dob" required>
         <br><br>
         <!-- Drop down -->
          <label for="Country">Country:</label>
          <select id="Country" name="Country">
            <option value="kenya">Kenya</option>
            <option value="uganda">uganda</option>
            <option value="tanxania">Tanzania</option>
            <br><br>

        <!-- Radio -->
         <p>Choose your gender:</p>
         <label for="male">Male</label>
         <input type="radio" id="male" name="male">
         <label for="female">Female</label>
         <input type="radio" id="female" name="female">
         <label for="other">Other</label>
         <input type="radio" id="other" name="other">
         <br><br>

         <!-- Checkboxes -->
          <p>Selct your hobbies:</p>
          <label for="swimming">Swimming</label>
          <input type="checkbox" id="swimming" name="swimming">
          <label for="reading">Reading</label>
          <input type="checkbox" id="reading" name="reading">
          <label for="athletics">Athletics</label>
          <input type="checkbox" id="athletics" name="athletics">
          <br><br>
      <h3>Before you go</h3>
      <video width="640" height="360" controls>
        <source src="C:\Anderson">
      </video>
      <br><br>
      <audio controls>
        <source src="C:\Anderson\audio">
      </audio>
          
          


  </body>
  <footer>
    <p>Thank you for choosing us</p>
    <p>Contact us at</p>
    <p>234563234 or abcde@gmail.com</p>
    
  </footer>
</html>
