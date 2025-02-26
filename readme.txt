=== Sell Digital Downloads ===
Contributors: wpecommerce, wp.insider
Donate link: https://wp-ecommerce.net/wordpress-isell-easily-sell-digital-downloads-from-your-wordpress-site-1916
Tags: sell digital products, sell downloads, sell download, sell products, ecommerce, commerce, paypal, paypal ipn, orders, sell photos, sell ebook, selling, e-downloads, e-store, eshop, download, downloads, digital downloads, e-commerce, wp ecommerce, sell videos  
Requires at least: 3.0
Tested up to: 5.7
Stable tag: 2.2.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

All in one WordPress plugin for selling digital downloads. It allows you to sell digital downloads via PayPal and manage orders from WP dashboard.

== Description ==

We are deprecating this plugin. You can use the [PayPal Express Checkout plugin](https://wordpress.org/plugins/wp-express-checkout/) which is a simple and lightweight plugin to handle the selling of digital downloads using the PayPal Express Checkout API.

I needed an easy and lightweight plugin to sell digital downloads. I don't want any kind of bloat in the plugin, so this plugin is not an elephant plugin. If you want to sell digital downloads via PayPal, this plugin will do the job nicely.

WordPress iSell is a simple WordPress plugin to sell digital downloads. It integrates flawlessly with PayPal. User interface (UI) of the plugin is very simple to use, I call this plugin for users, not for developers but developers should not feel left behind. I know how painful it is to modify client's plugins and then find out after a few weeks or months that they had updated the plugin and boom! all changes are lost. There are filters and hooks for almost every important functionality in WP iSell.

= Sell Digital Downloads Features =

* You can upload files easily via WordPress media uploader or your own FTP software
* You can sell various types of downloads. For example: pdf, ebook, photo, music, video, audio, mp3 etc
* Digital downloads are automatically sent to your customer via email after PayPal payment
* You can create unlimited products
* You can also create custom orders
* You can manage products and orders through standard WordPress UI. It feels as if you are managing your WordPress posts/pages. This plugin utilizes the custom post type feature of WordPress.
* It works flawlessly with the latest version of WordPress.
* It's a developer friendly plugin. It can be extended by using the proper hooks and filters.
* Your digital downloads are served to your customer as encrypted links. It's not just full links to your files.
* Easy File download using PayPal
* Upload thumbnails for your downloads
* Create a product display box using a shortcode

For detailed documentation please visit the [WordPress Sell Digital Downloads](https://wp-ecommerce.net/wordpress-isell-easily-sell-digital-downloads-from-your-wordpress-site-1916) plugin page.

= Get involved =

Developers can contribute to the source code on the [Sell Digital Downloads GitHub Repository](https://github.com/wp-insider/sell-digital-downloads).

== Installation ==

1. Go to the Add New plugins screen in your WordPress admin area
1. Click the upload tab
1. Browse for the plugin file (sell-digital-downloads.zip)
1. Click Install Now and then activate the plugin


== Frequently Asked Questions ==

= Can I use this plugin to sell digital downloads from a WordPress Site? =

Yes

= Can I use this plugin to sell digital downloads via PayPal? =

Yes

== Screenshots ==

For screenshots please visit the [WordPress Sell Digital Downloads](https://wp-ecommerce.net/wordpress-isell-easily-sell-digital-downloads-from-your-wordpress-site-1916) plugin page

== Changelog ==

= 2.2.7 =
* Digital file uploader has been updated.
* Thumbnail file uploader has been updated.

= 2.2.6 =
* Replaced deprecated <iframe> redirect with javascript redirect when user is downloading file.
* Added a new action hook so addons can intercept the download request and do additional tasks.
* Replaced the escape function with esc_sql function.

= 2.2.5 =
* Added "Custom Thanks Page URL" option for each product.
* Added [isell_buy_now] shortcode. You can use this shortcode to put a buy now button for a product on any WordPress post or page.
* Changed debug log filename from "wp_isell_debug.log" to "wp-isell-debug.txt".
* Fixed typos in readme.txt.
* Changed language textdomain from "isell" to "sell-digital-downloads".
* Changed the admin dashboard menu icon to use a cart icon.

= 2.2.4 =
* The plugin will automatically create the necessary pages (Download, Thanks, Error) at activation. No need to create these pages manually anymore.
* Removed deprecated function to fix the notice that was shown upon plugin activation.
* All the different admin dashboard menu items are now under the one "iSell" main menu.
* Fixed a warning that was getting shown after editing a product.
* Improved some help text and fixed some minor typos.

= 2.2.3 =
* Sell Digital Downloads is now compatible with WordPress 4.3.

= 2.2.2 =
* Updated description in the plugin settings.

= 2.2.1 =
* Updated the button code to send additional parameters to PayPal.

= 2.2.0 =
* Added some tweaks to the plugin to fix the PayPal IPN validation issue.

= 2.1.9 =
* Ability to upload a thumbnail for each product
* Show a [product display box](https://wp-ecommerce.net/create-product-download-box-in-wordpress-2613) using a shortcode

= 2.1.8 =
* Added debug functionality. This will be very useful if orders are not being updated or users are not getting emails

= 2.1.7 =
* Plugin is now compatible with WordPress 3.9

= 2.1.6 =
* Plugin now works with WordPress 3.8

= 2.1.5 =
* Plugin is now compatible with WordPress 3.7

= 2.1.4 =
* Plugin is now compatible with WordPress 3.6

= 2.1.3 =
* Media Uploader no longer breaks when you insert images to your WordPress post/page

= 2.1.2 =
* Digital files can now be uploaded via media uploader from "Products->Add New" interface
* Another alternative method has been added to resolve file download issues across different servers.

= 2.1.1 =
* Plugin icons are now properly displayed in the WordPress 3.5 admin interface

= 2.0 =
* fixed a function undefined error in the plugin admin area

= 1.9 =
* fixed a span tag in the metabox_order_payment_info.php file 

= 1.8 =
* some design improvements and new icons added for products and orders post type, new custom columns for product and order are added to products and orders screens(All Product/Orders), settings page link in admin notice fixed, pages now use ID on settings page instead of URLS

= 1.7 =
* Plugin dashboard menu position changed, new metabox("other information") for product post type, support for pending payment status added and new hooks/filters are added

= 1.6 =
* download page support added, new hooks/filters, various bug fixed and stability improvements

= 1.5 =
* order refund support and bug fixes

= 1.4 =
* thanks page, large file downloads support added and  bug fixes

= 1.3 =
* bugs fixed

= 1.2 =
* Permissions error when clicked on the iSell settings link bug fixed.

= 1.0 =
* This is the first version of the plugin. Please report bugs if you found one.

== Upgrade Notice ==
None
