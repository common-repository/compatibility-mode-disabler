=== Plugin Name ===
Contributors: canis1980
Tags: compatibility mode, internet explorer, chrome frame
Requires at least: 2.8.0
Tested up to: 4.7
Stable tag: 1.0
License: MIT
License URI: https://opensource.org/licenses/MIT

Disable Compatibility Mode in Internet Explorer for intranet sites. Also starts Chrome Frame if present.

== Description ==

This plugin will send HTTP-headers to the client to ensure that Internet Explorer does not try to display the site in compatibility mode,
which tends to break a lot of themes. This is the default behaviour for a lot of older Internet Explorer versions, when the site is identified
as an intranet site. Some clients may also have the setting activated by other means.

This plugin will also tell Internet Explorer to start Chrome Frame, if that is present, as this will also enable the sites to display in a 
proper way. 

== Installation ==

Follow these steps to install. WordPress plugins screen is recommended.

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

