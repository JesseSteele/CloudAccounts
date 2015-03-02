CloudAccounts for WordPress
verb.ink Cloud Accounts user details for WordPress.org sites

Description:
This is a simple WordPress plugin intended for WordPress Multisite. It creates a settings page where superadmins can list usernames for accounts that subscribing site admins can view for their reference. The plugin provides a simple page where users/admins can view their usernames for other web apps included in their verb.ink subscription, along with instructions, such as for email, and a place for users to keep personal notes. It also includes built-in top admin bar links for logging in to these accounts.

FYI: This will enter permanent records in the database at two stages because of notifications: The first entry is when the Superadmin enters information a notification will appear and the user will be able to access a different more information on the settings page. The second entry when the user acknowledges the notification. These changes should be benign, but cannot be reset from WP.

Installation instructions:

1. Copy the folder "cloudaccounts" to your wordpress plugins directory. (usually /wp-content/plugins/)

2. Then enable the plugin "Cloud Accounts" from the plugins page in the admin dashboard. It can be network-enabled or enabled per site.

3. There are no options.

4. Only Multisite Superadmins can enter information in each site's "settings" page. Only site admins can view the information and make notes that are not visible from the superadmin view.

Notes:
This is not in the main WordPress repository because it is custom written specifically for verb.ink. However, in being consistent with the verb.ink policy of being able to duplicate one's entire account, the plugin is made available here. This plugin is planned to become obsolete in the verb.ink roadmap.

Future roadmap is low-priority, but may include:
- Quick access dropdown from admin bar for site admins
- Non-multisite use for admins to manage accounts for users
- Ability for users to change their passwords through this interface
- Other web apps to be listed
- Customizable enough so it can be useful if added to the WordPress.org plugin repository

Special Thanks:

Devin
http://wptheming.com/2011/08/admin-notices-in-wordpress

Ronny Kibet ronnykibet.com
https://www.youtube.com/watch?v=_nW-h52I7Tg

Vitaly Polonetsky
http://stackoverflow.com/questions/4554758/how-to-read-if-a-checkbox-is-checked-in-php

Atli
http://www.dreamincode.net/forums/topic/229971-showhide-text-with-html-no-css-or-java-possible

Twitter @wpLifeGuard
http://wplifeguard.com/how-to-add-links-to-wordpress-3-3s-admin-bar
