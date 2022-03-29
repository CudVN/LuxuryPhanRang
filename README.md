# WebLuxury
Web site Luxury Car
Send Email
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<script src="https://smtpjs.com/v3/smtp.js"></script>  
	<script type="text/javascript">
		function sendEmail() {
			Email.send({
				Host: "smtp.gmail.com",
				Username : "",
				Password : "",
				To : 'huuduc0804@gmail.com',
				From : "duc.it@toyota.binhduong.vn",
				Subject : "TEST",
				Body : "BODY",
			})
			.then(function(message){
				alert("mail sent successfully")
			});
		}
	</script>
</head>
<body>  
	<form method="post">
		<input type="button" value="Send Email" onclick="sendEmail()"/>
	</form>  
</body>
</html>
