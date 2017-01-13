# SocialSubscribe

Q: What it does?<br> 
A: It is going to add people to your email list on https://mailchimp.com/. <br><br>

Q: How it looks like?<br>
A: Use it as it is now and you will get blank white page with one field to enter email and red button to submit. Underneath is one additional facebook colored button.<br><br>

Q: How it works?<br>
A: When email address is entered into email field and "subscribe with your email" button is pressed email address entered will be validated and delivered to mailchimp.php using ajax call. Communication with mailchimp api is executed using mailchimp class found here: https://github.com/drewm/mailchimp-api. After email address is added to the list return message will be sent back and displayed.<br>

Clicking "subscribe with facebook" button will trigger facebook pop up window and ask for permissions. After permissions are granted email is retrieved from facebook profile and handled with same logic as described above.<br><br>

Q: Is it all set?<br>
A: To make it work you will need to:<br>
   Check index.html and insert your facebook app id in appropriate place marked with commentary.<br>
   Check mailchimp.php and insert mailchimp api key and list id in appropriate place marked with commentary.


