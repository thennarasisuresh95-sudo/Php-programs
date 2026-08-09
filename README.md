# Php-programs
1.Display "Welcome to HTML
<!DOCTYPE html>
<html>
<head>
    <title>Welcome</title>
</head>
<body>

    <h1>Welcome to HTML</h1>

</body>
</html>

2.Headings, Paragraphs and Line Breaks
<!DOCTYPE html>
<html>
<head>
    <title>Headings and Paragraphs</title>
</head>
<body>

    <h1>HTML Programming</h1>
    <h2>Introduction</h2>

    <p>
        HTML stands for HyperText Markup Language.<br>
        It is used to create web pages.<br>
        HTML uses tags to structure the content.
    </p>

    <h3>Web Development</h3>

    <p>HTML is the basic language used for creating websites.</p>

</body>
</html>

3.Ordered and unordered list
<!DOCTYPE html>
<html>
<head>
    <title>Lists</title>
</head>
<body>

    <h2>Ordered List</h2>

    <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ol>

    <h2>Unordered List</h2>

    <ul>
        <li>Python</li>
        <li>Java</li>
        <li>C++</li>
    </ul>

</body>
</html>

4.Table with Student Details
<!DOCTYPE html>
<html>
<head>
    <title>Student Details</title>
</head>
<body>

    <h2>Student Details</h2>

    <table border="1">
        <tr>
            <th>Roll No</th>
            <th>Name</th>
            <th>Course</th>
            <th>Marks</th>
        </tr>

        <tr>
            <td>101</td>
            <td>Nila</td>
            <td>B.Sc CS</td>
            <td>85</td>
        </tr>

        <tr>
            <td>102</td>
            <td>Priya</td>
            <td>B.Sc CS</td>
            <td>90</td>
        </tr>

        <tr>
            <td>103</td>
            <td>Divya</td>
            <td>B.Sc CS</td>
            <td>88</td>
        </tr>
    </table>

</body>
</html>

5.text formatting tags
<!DOCTYPE html>
<html>
<head>
    <title>Text Formatting</title>
</head>
<body>

    <h2>Text Formatting Tags</h2>

    <p><b>This text is Bold</b></p>

    <p><i>This text is Italic</i></p>

    <p><u>This text is Underlined</u></p>

    <p>Water formula is H<sub>2</sub>O</p>

    <p>Mathematical expression: X<sup>2</sup></p>

</body>
</html>

6.Insert Image and Hyperlink
<!DOCTYPE html>
<html>
<head>
    <title>Image and Hyperlink</title>
</head>
<body>

    <h2>Image</h2>

    <img src="image.jpg" width="300" height="200" alt="Sample Image">

    <h2>Hyperlink</h2>

    <a href="https://www.google.com" target="_blank">
        Visit Google
    </a>

</body>
</html>

7.Student Registration Form
<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>

    <h2>Student Registration Form</h2>

    <form>

        <label>Name:</label>
        <input type="text" name="name">
        <br><br>

        <label>Email:</label>
        <input type="email" name="email">
        <br><br>

        <label>Password:</label>
        <input type="password" name="password">
        <br><br>

        <label>Gender:</label>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female
        <br><br>

        <label>Date of Birth:</label>
        <input type="date" name="dob">
        <br><br>

        <label>Course:</label>
        <select name="course">
            <option>B.Sc Computer Science</option>
            <option>BCA</option>
            <option>B.Sc Mathematics</option>
            <option>B.Com</option>
        </select>
        <br><br>

        <input type="submit" value="Submit">

    </form>

</body>
</html>
