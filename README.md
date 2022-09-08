# mayuresh016.github.io
<%@ page language="java" contentType="text/html; charset=ISO-8859-1"
    pageEncoding="ISO-8859-1"%>
    
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

<title>Laibrary Management system </title>


<style type="text/css">
.colum{

 float: left;
  padding: 10px;
  height: 600px; 

}
.left{
width: 30%;
}
.right{
width: 60%;

}
.left1{
width: 30%;
}
</style>
</head>
<body>

<div class="colum left" style="background: black;"> <br> <br>
<h4 align="center" style="color: white;">Application Login <br> Page</h4>
<br> <br>
<p align="center" style="color: white;">You Can login and register from here <br> to access the application </p>

</div>
 <div class="colum right">
 <div style="padding-top:200px; " align="center">
 
 <div class="colum left1">
 <span> <b>id</b> </span> <br><br>
  	<span > <b> password</b></span> <br><br>
  	 	<span style="padding-right: 10px;" > <b> User</b></span>
  	
 
 </div>
 <div class="colum left1">
 
 <form  action="loginuser" method="post">
 	<input type="text" name="id" id="id" placeholder="id"> <br> <br>
 	<input  type="password" name="password" id="password" placeholder="password"> <br> <br>
 	<select style="width: 200px; " name="user" id="user">
 	<option value="laibrerian">laibrerian</option>
 	<option value="student">Student </option>
 	
 	</select><br> <br>
 	<button type="submit">Login</button>&nbsp;
 	
 
 <a style="align-items: center;"  href="adminReg"> <button type="button" >Register</button> </a>
 </form>
 </div>
 </div> <br>

 
 </div>















<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
</html>
