<html>
 <head>
		<script src="print.js?v1.0.61"></script>		
	</head>
	<body id="pageBody" class="">
		<form method="post" action="#" id="printJS-form">
							<div style="display: flex; margin-bottom: 10px;">
								<div style="flex: 1;padding-right: 10px;">
									Name:
									<input type="text" name="name" id="name" value="John Doe" placeholder="Name">
								</div>
								<div style="flex: 1;">
									Email:
									<input type="text" name="email" id="email" value="john@doe.com" placeholder="Email">
								</div>
							</div>
							<div>
								<div>
									Message:
									<textarea name="message" id="message" placeholder="Message">Print HTML Elements</textarea>
								</div>
							</div>
						</form>
<button type="button" onclick="printJS({ printable: 'printJS-form', type: 'html', css: ['/assets/css/main.css?v1'] })">
							Print Form
						</button>
 </body>
</html>
