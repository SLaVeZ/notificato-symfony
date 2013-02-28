notificare-symfony
==================

An integration bundle for the notificare push notifications module into the Symfony2 framework.

Installation Instructions
=========================

Using composer (for Symfony 2.1)
--------------------------------

The best way to install the bundle is by using [Composer](http://getcomposer.org). Add the following to `composer.json` in the root of your project:

``` javascript
{ 
  "require": {
    "wrep/notificare-symfony": "dev-master"
  }
}
```

Including bundle in Kernel
--------------------------

*app/AppKernel.php*

```
public function registerBundles()
{
    $bundles = array(
        // System Bundles
        ...
        new Wrep\Bundle\NotificareBundle\NotificareBundle(),
        ...
    );
}
```

License
-------

This bundle is under the MIT license. See the complete license in the bundle:

    Resources/meta/LICENSE
    
About
-----

See also the list of [contributors](https://github.com/Wrep/notificare-symfony/contributors).

Reporting an issue or a feature request
---------------------------------------

Issues and feature requests are tracked in the [Github issue tracker](https://github.com/wrep/notificare-symfony/issues). You're very welcome to submit issues or submit a pull request.