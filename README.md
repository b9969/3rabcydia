
<?php
$json = file_get_contents('http://127.0.0.1/api/api.php');
$obj = json_decode($json);
print $obj->{'name'}; 
?>
return Unknown

exemple_02

echo "$obj->ip"; 
return 127.0.0.1
