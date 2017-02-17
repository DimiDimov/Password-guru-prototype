# Password-guru-prototype
Password Guru is a library that makes it simple to make a secure website. 

Simply download the source code from github, add it into your website file system and begin using the resources.

All of the resources will be provided using calls to javascript methods.
EXAMPLE:
Lets say that you are using JQuery to extract your HTML inputs to use in your javascript.
You would grab the username and password with lines of code like this:

  var username = $("#username").val();
  var password = $("#password").val();
 
From this point you will need to verify the strength of your users password to prevent their information being stolen
You can simply call the Password Guru function check strength

  var strengthResult = PassGuruCheck(username, password);
  
The strengthResult that is returned will be a String that is either pass or the error that describes why the password was not successful. Possible errors include:
"PasswordTooCommon"
"PasswordVariationOfUsername"
and others...


