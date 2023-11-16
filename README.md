# HR_portal
<!DOCTYPE html>
<html>
<head>
<style>


table{
border-collapse:collapse;
}
</style>


<body bgcolor="lightcyan">
<header>
<h1 style="background-color:teal;color:white;text-align:center;"> Welcome to company HR portal</h1>
<nav>
<ul type="none">
<li align="center"><a href ="#Employee Registration">Employee Registration</a></li>
<li align="center"><a href ="#Employee directory">Employee directory</a></li>
<li align="center"><a href ="#Contact us">Contact us</a></li>
</ul>
</nav>
<section id="Employee Registration">
<img height="300px" width="300px" src="1000068579.jpg"/>
<h2 align="center"><u>Employee Registration </u></h2>
<fieldset>

<form align="center">
<legend><h1>Registration form</h1>
<label>First Name:</label>
<input type ="text" value="Enter first name"><br></br>
<label>Last Name:</label>
<input type ="text" value="Enter last name"><br></br>
<label>Email:</label>
<input type ="email" value="Enter email" required="" accept=""><br></br>
<label>Password:</label>
<input type ="password" value="Enter password"><br></br>
<label>Age:</label>
<input type ="number" value="Enter password"><br></br>
<label>Date of joining:</label>
<input type ="date" value="Enter password"><br></br>
<label>Select role:</label>
<select >
<option>Software Engineering</option>
<option>Designer</option>
<option>Hardware engineer</option>
<option>HR</option>
</select>
<input type ="submit" value="submit">
</form>
</legend>
</fieldset>

</section>

<hr color="navy" size="5px">
<section id="Employee directory">
<br></br><h2 align="center"><u> Employee table </u>  </h2><br></br>
<table border="2" cellspacing="3" cellpadding="5">
<tr>
<th>Employee ID</th>
<th>Employee name</th>
<th>Employee role</th>
</tr>

<tr>
<td>255</td>
<td>Ritu kadam</td>
<td>Software Engineer</td>
</tr>

<tr>
<td>378</td>
<td>Aniket joshi</td>
<td>Designer</td>
</tr>

<tr>
<td>298</td>
<td>Arundhati Shrivastava</td>
<td>Manager</td>
</tr>


</table>

</section>

<hr color="navy" size="5px">
<br></br><br></br>

<section id="Contact us" style="background-color:grey;color:white;">
<h2 align="center">Contact us </h2> 
<iframe
  width="300"
  height="300"
  frameborder="0"
  style="border:0"
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1dYOUR_LATITUDE!2dYOUR_LONGITUDE!3d15.875862993247578!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3AYOUR_PLACE_NAME!2sYour+Place+Name!5e0!3m2!1sen!2sus!4vYOUR_API_KEY"
  allowfullscreen>
</iframe>
</section>
</header>
</body>
</head>
</html>
