# Kohana Auth driver for Jelly

This is an Auth driver based on the ORM Auth driver, rewritten for [Jelly](https://github.com/creatoro/jelly).

## Installation

Enable the module in your **bootstrap.php**:

	Kohana::modules(array(
		'jelly-auth' => MODPATH.'jelly-auth',
		// ...
	));