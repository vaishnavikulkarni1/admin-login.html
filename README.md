<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->

<html>
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8" />
<title>Cyberbullying</title>
<meta name="keywords" content="" />
<meta name="description" content="" />
<link href="default.css" rel="stylesheet" type="text/css" media="screen" />
<script language="JavaScript">
function validation()
{
var a = document.form.userid.value;
var b = document.form.pass.value;
if(a=="")
{
alert("Enter your UserId");
document.form.userid.focus();
return false;
}
if(b=="")
{
alert("Enter your Password");
document.form.pass.focus();
return false;
}

}
</script>
</head>
<body>
<!-- start header -->
<div id="header">
	<div id="logo">
		
    <h1 align="center"><font size="+3">A System to Filter Unwanted Messages from OSN User Walls</font></h1>
    <div style="top:150px;">       
    <h1 align="center"><font size="+3"COLOR="RED">ADMIN PAGE</font></h1></div>
            
		
	</div>
	
</div>
<!-- end header -->
<!-- start page -->
<div id="page">
	<div style="position:absolute; right:40px; top:180px;">
	

				
					<div>
						
        
      
        
      </div>
				
			
	
	</div>
<div style="position:absolute;  top:230px;">
<fieldset>
      
    <legend><font color="Blue"><strong><font size="4">Admin Login</font></strong></font></legend>
	<table height="160">
	<form action="adminlogin.jsp" method="post" name="form" onsubmit="return validation();">
	<tr>
	    <td height="37">Admin</td>
	<td><input type="text" name="userid" id="s" size="15" value="" /></td>
	</tr>
	<tr>
	    <td height="35">Password</td>
	<td><input type="password" name="pass" id="s" size="15" value="" /></td>
	</tr>	
  
  <tr>
<td height="39"></td>
<td><input type="submit" name="submit" class="button2" value="Login">
<input type="reset" name="reset" class="button2" value="Clear">
</td>
</tr>
  </form>
	</table>
	  </fieldset>
	<br><br><br>
        <p><img src="images/newUser.png"><font size="3"><a href="newuser.jsp"><font color="blue">New User Signup Here?</font></a></font></p>
        <p><img src="images/newUser.png"><font size="3"><a href="index.html"><font color="blue">For User</font></a></font></p>
</div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br> <br><br>
	<div id="content" align="right">
		<div class="post">
			
		</div>

	</div>
	<!-- end content -->
	<!-- start rightbar -->
	
	<!-- end rightbar -->
	<div style="clear: both;">&nbsp;</div>
</div>
<!-- end page -->
<br><br><br><br><br><br><br>
<div id="footer">
	

  <p align="right"><font color="Blue" size="2"><strong>Online Social Network</strong></font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/icon3.jpg">&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/icon1.jpg">&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/icon4.jpg">&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/icon5.jpg">&nbsp;&nbsp;&nbsp;&nbsp;<img src="images/Icon7.png" width="30" height="30"></p>
</div>
</body>
</html>
