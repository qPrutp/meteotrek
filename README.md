// додати в index.php
// з 12 стрічки, ці стрічки повинні бути в межах php тегів

	error_reporting(E_ALL & ~E_DEPRECATED & ~E_WARNING & ~E_NOTICE); 
	 
	define('MTSROOT', realpath(dirname(__FILE__)).DIRECTORY_SEPARATOR);
	require_once MTSROOT."mapLandMeteotrek/src/app.php";


// з наступної стрічки після link href="gwsse.css" rel="stylesheet"
	<?php mtsHeaders(); ?>

// php підключення додатку потрібно для відслідковування авторизації
