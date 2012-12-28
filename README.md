Gregorian-Jalali-Date-Convertor
===============================

Gregorian-Jalali Date Convertor php script

use these function to convert dates :

* @method gregorian_to_jalali ($g_y, $g_m, $g_d,$str)       
* @method jalali_to_gregorian($j_y, $j_m, $j_d,$str) 

$g_y: gregorian year
$g_m: gregorian month
$g_d: gregorian day
$j_y: jalali year
$j_m: jalali month
$j_d: jalali day

$str: return in string format

if $str set to true the function return converted date in string format .

easy compare jalaly and Gregorian date by :

* comparedate($_date_mix_jalaly,$_date_mix_gregorian)

give 2 dates in string format .