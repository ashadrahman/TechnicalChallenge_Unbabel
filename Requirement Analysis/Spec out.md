FUNCTIONAL SPECIFICATION FOR LOGIN FORM

This form asks to enter e-mail and password to access web site.
 

Controls description:

•	E-mail Address:
  •	Textbox with maximum 320 chars [Note: Typical maximum length is 320 characters], empty by default.
  •	Placeholder – ‘Enter email address’.
  •	The general format of email address is local-part@domain
  
•	Password: 
  •	Textbox with maximum 128 chars [Note: Typical maximum length is 128 characters]. When user types password then display ‘*’ instead of entered chars.
  •	Empty by default.
  •	Placeholder – ‘Password’.
  •	Common guidelines advocated by proponents of software system security include: Use a minimum password length of 8 or more characters if permitted. Include lowercase and uppercase alphabetic characters, numbers and symbols if permitted.



Clicking ‘Log In’ does the following:
•	If mandatory fields were not provided yet then a red error message is displayed below the title, saying ‘Field ‘<field name>’ is mandatory.’. Pre-populate all e-mail and password.

•	If e-mail address was provided, but such e-mail is not registered in the system then a red error message is displayed below the title, saying ‘Invalid e-mail or password.’. Pre-populate all e-mail and password. [Note: system does not tell real reason to avoid hacking]

•	If Password was provided but does not correspond the provided e-mail then an error red message is displayed below the title, saying ‘Invalid e-mail or password.’. Pre-populate all e-mail and password. [Note: system does not tell real reason to avoid hacking]

•	In additional, if all fields were provided and OK, but a system error occurred, then a red error message is displayed below the title saying ‘Operation failed. Please try again and if an error occurs again please contact your administrator.’. Pre-populate all e-mail and password.

•	Forgot Password link - if user forgets password then user click on that option to enter the username(email id) and the reset password email is sent to that specified email id.

•	If all fields are OK then open the Home page.
