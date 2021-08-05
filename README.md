<?php
 $n = 12345;
 $d = $n;
 $sum = 0;
 while($n!=0)
 {
    $d = $n%10;
    $sum = ($sum + $d);
    $n = $n/10;
 }
echo $sum

?>
