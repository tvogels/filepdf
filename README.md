FPDF for use with Symfony2
==============================

Uses File_PDF v 1.48

Setup
-----

Add the following lines to your `deps` file:

	[FilePDF]
	   git=http://github.com/tvogels/filepdf.git
	   target=filepdf

And those to `app/autoload.php`:

```php
$loader->registerPrefixes(array(
    ...
    'Horde_'        => __DIR__.'/../vendor/filepdf/lib',
```

Now run `php bin/vendors update` or `php bin/vendors install`.
