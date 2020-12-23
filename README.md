## "WPS minify" - module for opencart 2.3/3.0


### Installation
+ Copy the contents of the "upload" folder to the root of your site
  and also you need to manually correct 1 line in the /system/startup.php file,
  replacing 
  `require_once(DIR_SYSTEM . 'framework.php');	` =>
  `require_once(modification(DIR_SYSTEM. 'framework.php'));`
  This is required to modify the framework.php file via modifiers.
+ Update modifications

