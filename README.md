# php-globals-variable-
PHP GLOBALS VARIABLE
<?php
	$x=100;
	$y =75;
	function addition(){
		$GLOBALS['z']= $GLOBALS['x']+$GLOBALS['y'];
	}
	addition();
	echo $z;
	?>
