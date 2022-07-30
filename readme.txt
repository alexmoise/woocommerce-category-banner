=== WooCommerce Category Banner  ===
Contributors: wpbackoffice, alexmoise
Tags: woocommerce, category, product, banner, image, archive, shop
Donate Link: http://wpbackoffice.com/plugins/woocommerce-category-banner/
Requires at least: 3.5
Tested up to: 670
Stable tag: 1.2.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Place a custom banner and link at the top of your product category pages. Easily update the image through your product category edit page.

== Description ==

Place a custom banner and link at the top of your product category pages. Easily update the image through your product category edit page. 

Features:

* No configuration needed, just install and start using
* Supports an image for each category
* Custom product category positions with a template tag for including the image in a custom area in your custom product category template.
* Support a link for each category / banner image

Getting Started:

1. From the sidebar click 'Products' -> 'Categories'
2. Select an individual category from your list
3. Paste the url of the banner you'd like to use into the "Banner Image Url" field
4. That's it, your banner should now be displaying on your category archive page.
5. Remove image by clicking the Remove File button from the edit category page.

You can hide the automatic image placement by unchecking "Automatically insert banner above main content"

You can then place the template tag wcb_show_category_banner() in your custom category template to customize the position of the image in your markup. Note - this tag must be placed on category templates - not product templates.

[Plugin's Official Documentation and Support Page](http://wpbackoffice.com/plugins/woocommerce-category-banner/)

== Installation ==

Manual Installation

1. Download the latest version of the plugin from the GitHub page
2. Go to Plugins -> Add New section in your WP admin dashboard, click Upload Plugin and upload the zip file downloaded in the previous step
3. Click Install Now, then click Activate Plugin
4. Done, now start uploading a banner image from 'Products' -> 'Categories' -> (Select category)

== Changelog ==

= 1.2.0 =
* Updated the JS file for jQuery v3.6.0 compatibility

= 1.1.2 =
* Bug fix, notice was appearing with WP DEBUG set to true

= 1.1.1 =
* Adding Template tag for custom banner position for custom product category templates.

= 1.1.0 =
* Added image upload button
* Added banner link 

= 1.0.0 =
* Initial Commit

== Screenshots ==

1. Category page where banner will be presented.
1. Category edit page, upload your image here.
