=== wp-require-login ===
Contributors: richard4339
Donate link: http://www.digitalxero.com/
Tags: admin, login, private
Author URI: http://www.digitalxero.com/
Plugin URI: http://www.digitalxero.com/software-development/wp-require-login/
Requires at least: 3.3.0
Tested up to: 3.3.1
Stable tag: 0.5.1

A plugin for Wordpress that redirects users to the login page whenever they try to visit any page/post/etc on the blog.

== Description ==

A simple plugin for Wordpress that redirects users to the login page whenever they try to visit any page/post/etc on the blog, with an option menu to turn this functionality on or off. When enabled, the entire blog essentially becomes a private blog.

== Installation ==

1. Upload `wp-require-login.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to the 'Require Login' Settings menu and enable.

== Frequently Asked Questions ==

= How do I enable this plugin? =

Once the plugin itself is installed, navigate to the 'Require Login' Settings menu, check the lone checkbox, and click 'Update Options'.

= I'm running a build of Wordpress that is older than 3.3. Can I use this plugin? =

I personally wrote this for a Wordpress installation in early 2008. When I revived it a few days ago, I did have to make some changes. In all honesty, it should work with 3.2 onwards, or on even earlier versions with the Settings menu portions removed from the code. I'm only listing 3.3.0 since this is the earliest version I can guarantee it works with.

== Screenshots ==

1. The Require Login Settings page.

== Changelog ==

= 0.5.1 =

* First published version.

== Upgrade Notice ==

= 0.5.1 =
Initial version.

== To Do ==

* Provide more detailed information on installation to direct users to the settings page.
* Ensure the single entry added to the meta table is removed upon deletion of the plugin.

== Git/Subversion ==

In addition to the subversion access that Wordpress is providing, this plugin is available through git at [Github](https://github.com/richard4339/wp-require-login).
