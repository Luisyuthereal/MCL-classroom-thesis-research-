# MCL-classroom-thesis-research-
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style>
body {
  margin: 0;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 25%;
  background-color: #f1f1f1;
  position: fixed;
  height: 100%;
  overflow: auto;
}

li a {
  display: block;
  color: #000;
  padding: 8px 16px;
  text-decoration: none;
}

li a.active {
  background-color: #04AA6D;
  color: white;
}

li a:hover:not(.active) {
  background-color: #555;
  color: white;
}
</style>
</head>
<script>
        function logout() {
            // Clear authentication data from local storage or cookies
            localStorage.removeItem('authToken'); // Example for local storage
            // Or, if you are using cookies:
            // document.cookie = "authToken=; expires=Thu, 01 Jan 1970 00:00:00 UTC; path=/;";

            // Redirect to the login page
            window.location.href = 'login.html';
        }
    </script>
<body>

<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="insitution page.html">Insitution Page</a></li>	
  <li><a href="activities.html">Activities</a></li>
  <li><a href="courses.html">Courses</a></li>
  <li><a href="calendar.html">Calendar</a></li>
  <li><a href="messeges.html">Messeges</a></li>
  <li><a href="grades.html">Grades</a></li>
  <li><a href="assist.html">Assist</a></li>
  <button onclick="logout()">Log Out</button>
</ul>

<div style="margin-left:25%;padding:1px 16px;height:1000px;">
  <h2>Mapua Malayan Colleges Laguna</h2>
  <h3>We learn, We teach, We can, We reach, We can be champions</h3>
  <p></p>
  <p></p>
  <p>Welcome to the Mapua Malayan colleges website. In here were not only teaching our students learn, but make them champions.</p>
  <p>PICTURE</p>
  <p>In Mapua Malayan Colleges Laguna we make sure were always in top notch and have a clean enviornment for our students.</p>
  <p>Picture</p>
  <p>We ensure that our school will make a safe living space for our student with high security and with well protected walls.</p>
  <p>Picture.</p>
  <p>We also have fun having events and spreading joy and love and positivity for our Students.</p>
</div>



</body>
</html>
