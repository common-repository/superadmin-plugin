=== Plugin Name ===
Contributors: HiddenKnowledge
Tags: admin, superadmin
Requires at least: 3.0
Tested up to: 3.0
Stable tag: 1.0

This is a plugin that tries to protect the superadmin (userid 1) against attempts to edit or delete this user.

== Description ==

This is a plugin that tries to protect the superadmin (userid 1) against attempts to edit or delete this user.
Please note: This plugin is not extensivly tested and might be dangerous when used in the wrong way.
Users can easily disable these protections if they are able to execute php in any way.

**Do not rely on this plugin too much.**

== Installation ==

1. Upload `superadmin.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Known bugs ==

1. Currently the first post is protected as well.
