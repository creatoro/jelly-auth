# Jelly driver for Kohana Auth

The Auth driver is the official [Kohana ORM](https://github.com/kohana/orm) Auth driver modified for [Jelly](https://github.com/creatoro/jelly).

## Installation

Enable the module in your **bootstrap.php**:

	Kohana::modules(array(
		'jelly-auth' => MODPATH.'jelly-auth',
		// ...
	));