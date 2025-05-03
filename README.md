# first01-project-
make page using HTML and css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CS202 Assignment no#01</title>
  <style>
    body {
      background-color: #f0f4f8;
      font-family: Arial, sans-serif;
      color: #333;
      margin: 50px;
      padding: 40px;
     
    }

    
    h1 {
      color: #0a0a23;
      text-align: center;
    }

    h2 {
     
      text-align: center;
      color: #0077cc;
    }
    h3 {
      margin-top: 30px;
      margin-bottom: 10px;
    }

    p {
      text-align: justify;
      margin: 20px 0;
      
    }

    ul {
      list-style-type: square;
      margin-left: 40px;
    }

    ol {
      list-style-type: upper-roman;
      margin-left: 40px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }

    table{
        width: 77%;
        margin: 20px auto;
      border-collapse: collapse;
    }

    th, td {
        border: 1px solid #333;
      padding: 8px 12px;
      text-align: center;
    }

    a {
      color: #0077cc;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: #ff4500;
      text-decoration: underline;
    }
    .section{
        font-size: 22px;
        margin-top: 30px;
        margin-bottom: 10px;
        color: #0a0a23;
        font-weight: bold;
    }
    .container {
      background-color: #fff;
      padding: 40px;
      max-width: 800px;
      margin: 0 auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      /*background-color: #ffffff;
      padding: 20px;
      border-radius: 10px;
      margin: 0 auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);*/
    }

  </style>
</head>
<body>

  <div class="container">
    <h1>BC220407795 and Khadijha Aqdas Portfolio</h1>
    <h2>Web Developer & Tech Educator</h2>

    <p>Hello! My name is Khadijha Aqdas. I am a university student and a web development enthusiast. I enjoy building 
    responsive websites and teaching others the fundamentals of front-end technologies.</p>
   <div class="section">My Skills</div>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>Responsive Web Design</li>
      <li>Teaching & Mentoring</li>
    </ul>

    <div class="section">My Hobbies</div>
    <ol>
      <li>Traveling</li>
      <li>Reading</li>
      <li>Photography</li>
      <li>Cooking</li>
    </ol>


    <div class="section">My Achievements</div>
    <table>
      <tr>
        <th>Year</th>
        <th>Achievement</th>
      </tr>
      <tr>
        <td>2022</td>
        <td>Completed my FSC.</td>
      </tr>
      <tr>
        <td>2026</td>
        <td>Completed my Bachelor Degree</td>
      </tr>
    </table>

    <div class="section"><h3>More About Me</h3></div>
    
      <a href="https://meblog.com" target="_blank">Visit my blog</a>
    
  </div>

</body>
</html>

