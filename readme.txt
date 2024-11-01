=== WP-Invites ===
Author: Jehy, themaster507
Contributors: Jehy, themaster507
Donate link: http://jehy.ru/articles/donate/
Tags: user,registration,authentication,register,access
Requires at least: 4.0
Tested up to: 4.8.2
Requires PHP: 5.2
Stable tag: 2.52
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Invites system for WordPress, (WordPress MU and BuddyPress - CURRENTLY BUGGY)!

== Description ==

####Description
Stop any strangers from entering your blog! Only the ones who received invitation code will be able to register. You can configure different plugin options - separators, number of chars to be used for code generation, code working time and much more! Also, now you can add codes manually and view added codes.

####Compatibility
This plugin is compatible with WordPress 4.7.5 and future compatibility for BuddyPress and WordPress multi-site networks are in development. If you find any compatibility issues for current versions - feedback appreciated.

[Changelog](https://wordpress.org/plugins/wp-invites/changelog/).

####Localization

* English
* Russian

####Attention!
This plugin only denies new registrations from strangers. If you need to make your blog really private, you should restrict viewing [with Registered-Users-Only-2 plugin](http://wordpress.org/extend/plugins/registered-users-only-2/) or somewhat alike.

####Questions
If you have troubles with my plugin, need more details, or have suggestions - please use the forum. For archive support please see [Jehy's blog](http://jehy.ru/articles/2009/02/09/wordpress-plugins/#comments) for more info.


####Please!
If you don't rate my plugin as 5/5 - please write why - and I will change plugin, add options and fix bugs. It's very unpleasant to see silent low rates.  
If you don't understand what plugin does - also don't rate it ;)

####Donate or help?
If you want to ensure the future development and support of this plugin, you can make donation [to the author](http://jehy.ru/articles/donate/) or [to the active contributor via PayPal](https://paypal.me/AnthonyMaster/5) or just write about this plugin in your blog.


###Installation
Please look instructions on the [installation page ^_^](http://wordpress.org/extend/plugins/wp-invites/installation/).

== Changelog ==

2.52 - Corrected errors in script where debugging outputting data before a page redirection when debugging not turned on.
2.51 - Corrected errors in script with array elements not set - *support now being maintained by themaster507*
2.50 - Code rewrite in Object oriented style, debug mode implemented, fixed error with user activation.
2.42,2.41 - Fix for BuddyPress.
2.40 - Many changes for admin area, added cool styling, improved some SQL queries. Also fixed localization issues.
2.30 - Fixed for WordPress 4.1, direct SQL replaced with $wpdb queries, added missing menu button.
2.21 - Fix for simple WordPress & BuddyPress combo errors. Hope it works.
2.2 - Internal release
2.1 - Several fixes for simple WordPress.
2.0 - Absolutely new version, with many functions, compatible with newest WordPress, WordPress mu and BuddyPress.

1.3 - Fixed registration incompatibility issues.
1.2 - Critical upgrade for WP MU (not for simple WordPress), install as soon as possible.
1.1 - Fixed broken compatibility mode for MySQL 4, added some error reporting
1.0 - Many different fixes, including usernames's replacing and error reporting
0.4 - Defined str_split function for compatibility with PHP4
0.3 - Updated to work with the latest BuddyPress system
0.2 - Activation and language issues with WordPress MU fixed
0.1 - First release

== Installation ==
Usually:  
1. Upload the complete folder `wp-invites` to the `/wp-content/plugins/` directory;  
3. Activate the plugin through the 'Plugins' menu in WordPress;  
2. Get activation codes through Plugins-&gt;WP-invites (Site admin-&gt;WP-invites for WP MU) link;  
4. Enjoy.

= BuddyPress is currently buggy =
Bug fixes are in development. Please stay tuned as we bring this plugin back to life.

For old versions of WordPress MU and BuddyPress:  
1. Upload the complete folder `wp-invites` to the `/mu-plugins/` directory;  
2. Put file `wp-invites-MU_INIT.php` from `wp-invites` to upper directory, `mu-plugins`;  
3. Get activation codes through Site admin-&gt;WP-invites link;  
4. Enjoy.

== Frequently Asked Questions ==

= Are there any new features in the works? =
Yes, I have many new features that are currently in development as we bring this plugin back to life. If you have any additional suggestions please use the forum.

* Beautify admin page to use WP tables for display so the invite codes would show like the posts or pages
* Add feature to disable/delete existing invite code
* Add feature to add more details when generating/manually adding codes such as custom expiration and uses allowed
* Add feature to send invite code via email with link that enters code directly to registration page
* Add a front-end widget for logged in users only to send an invite code to a friend. Admin will have a setting to what level user is required to access the widget.
* Add a back-end admin dashboard widget to send invite codes
* Add a back-end admin dashboard widget to show invite codes expiring soon, recently used, etc.

== Screenshots ==
1. Invitation code request while registering in WordPress.
2. Invitation code is displayed for administrator in user profile.
3. Invitation code is also displayed for administrator in user profile in BuddyPress.

== Upgrade Notice ==
Bug Fixes. More updates coming soon!