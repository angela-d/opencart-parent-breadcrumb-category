# Parent Breadcrumb Category v1.0 #
For Open Cart 2.3.0.2 &amp; 3.0.2.0

For a list of improvements & fixes, see the [changelog](CHANGELOG.md).


Features
* Self-extracting in OCMOD format
* No configuration - install it & it works
* Includes Parent category *and* subcategories in all product breadcrumbs
* Strengthen your SEO

***


## [:link: Install Instructions](installing-instructions.md) ##

## [:link: Upgrade Instructions](upgrade-instructions.md) ##


***

## Usage ##

This super simple Opencart plugin works by adding a modification to your Opencart product page that generates SEO-friendly links to all parent and subcategories for the product.

Before:

![before](./img/before.png)

After:

![after](./img/after.png)

### Things to consider ###
This plugin was tested on both 2.3.0.2 &amp; 3.0.2.0 with and without SEO URLs enabled (if SEO links are disabled in your admin, this plugin will still generate links to said categories/subcategories, but the URL structure will have the native querystring URLs, rather than the pretty /myproductname style path.)

To enable the pretty SEO URLs, go to:
Settings -> Edit -> Server -> Enable SEO URLs

* Make sure `.htaccess.txt` in the root directory of your site gets renamed to `.htaccess` (if on Apache)

* This plugin was not tested in situations where a product is not attached to any categories.


Tested in PHP 7.2+

### Note ###
You do not need to clone this repository to utilize the plugin, all you have to do is download the
[zip file](./../../releases).

You can also download it from the [Open Cart Marketplace](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=33870).

I included the source in this repository for those who like to review the codebase prior to using new code.
