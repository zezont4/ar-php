# Contribution to Ar-PHP Library, namespace-psr4 added

## I changed class names to match its file name

## Install
Add this code into composer.json:

	"repositories": [
		{
		    "type": "vcs",
		    "url": "https://github.com/zezont4/ar-php"
		}
	    ],
    
Add the "johntaa/ar-php": "dev-master" into the require section of your composer.json.
Run composer install.


## Usage

    <?php
	use Johntaa\Arabic\Arabic;
	
		$Arabic = new Arabic('Glyphs'); 
		
		$text ="";
			$text = $Arabic->utf8Glyphs($text); 
		
		
		
## Why I need it :
 My application producing Images using GD extension and these images conatain arabic phrases, but GD cannot understand how to connect these phrases letters , So this great library helped me to solve this problem.
 
## Support Arabic 

For more support in using arabic language in php, I think this site deserve a visit:  [PHP Arabic -- Ar-PHP](http://www.ar-php.org/)
