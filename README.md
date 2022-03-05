# DBS_WealthManager

<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>WealthManager</title>
<link href="stylesheet.css" rel="stylesheet" type="text/css" />
</head>

<body>
<div id="banner">
<span class="head">Wealth Manager</span><br />
<marquee class="clg" direction="right" behavior="alternate" scrollamount="1">Customer16</marquee>
</div>
<br />

<div align="center">
<div id="wrapper">
<br />
<br />

<span class="SubHead">Welcome <?php echo $name;?></span>
<br />
<br />
<table border="0" class="table" cellpadding="10" cellspacing="10">
<tr><td><a href="RequestMeeting.php" class="Command">Request Meetings</a></td>
<td><a href="" class="RequestedMeetings">RequestedMeetings</a></td></tr>
<tr><td><a href="issue.php" class="Command">Appointments</a></td><td><a href="changePasswordAdmin.php" class="Command">Change Password</a></td></tr>
<tr><td><a href="logout.php" class="Command">Logout</a></td></tr>
</table>
<br />
<br />

<br />
<br />

</div>
</div>
</body>
</html>
