# TakRaghami.php
https://quera.org/problemset/3539?tab=description
<?php
$n = (int)readline("Enter a number: ");
function add_digits($n){
    if ($n > 0)
    {
		return ($n - 1) % 9 + 1;
    }else{
		return 0;
    }
}
print_r(add_digits($n));
