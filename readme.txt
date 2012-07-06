=== Members Import ===
Contributors: manishkrag
Tags: csv, user, import, users, member, members, batch, batch import, batch import members, batch import users, one click user creation, import csv, import from csv, user registration, wordpress members import,wordpress csv import, wordpress users import
Stable tag: 1.0
Tested up to: 3.4

This plug-in allows you to batch import of users/members taken from an uploaded CSV file.

== Description ==

This allows you to batch import of users/members taken from an uploaded CSV file.
It will add users/members with basic information, including firstname, lastname, username, password and email address.
Each user who is added will be a 'subscriber' if value not provided in csv file, and be able to login to your site.

You can also choose to send a notification to the new users and to display password nag on user login.

There are no additional options available at the moment, but if you want to add a bunch of users in one go, this will do this for you quickly.

<b>Basic Fields:</b>
user_login
user_pass
user_email 
user_url 
user_nicename
display_name 
user_registered 
first_name
last_name 
nickname 
description
rich_editing 
comment_shortcuts 
admin_color
use_ssl 
show_admin_bar_front 
show_admin_bar_admin
role

== Features ==

* Create users/members in wordpress site in a single click.
* Imports all users/members fields.
* Imports user/members meta fields.
* Allows setting user role.
* Sends new user notification (if the option is selected)
* Shows password nag on user login (if the option is selected)
* If username already present in database then this user will not register thus we are avoiding the multi use of same username.

== Installation ==

* Upload `members-import` to the `/wp-content/plugins/` directory.
* Activate the plugin through the 'Plugins' menu in WordPress.
* You will see a new 'Members Import' option under the existing 'Users' menu area.
* data in csv file should be delimitted by double quote(").

== Frequently Asked Questions ==

= CSV file format? =

* CSV file should have all the field name separated by comma(,) and delimitted by double quote(") in first row.
* Data present from the second row are assume as data to be import.
* In a row all the data should be separated by comma(,) and delimitted by double quote(").

== Changelog ==

= 1.0.0 =
* First release of plug-in. No changes.
