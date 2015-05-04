=== Recent Revisions ===
````
Plugin Name: Recent Revisions
Tags: revision, revision control, summary, posts, post revisions, dashboard, admin, revision overview, version control, versioning, wiki
Requires at least: 3.6
Tested up to: 4.2.1
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Contributors: birdsarah, benjamin4
Donate link: http://www.sarahbird.org/recent-revisions
````
== Description ==

Shows an overview of your recent post revisions on your administration dashboard. Ideal for sites with content that gets updated by multiple authors where you want to keep an eye on the changes that have been made. Number of revisions displayed is configurable as well whether you want the author and the date shown. Posts are displayed in GMT to enable effective collaboration across timezones.

Experiences, feedback and thoughts welcome (http://www.sarahbird.org/contact or https://github.com/birdsarah/wp-recent-revisions/issues)
 
This plugin was based on Rick's "Dashboard: Recent Posts Extended" http://rick.jinlabs.com - a big thank you for his hard work.

**See Also:** 

* Revision Management - http://codex.wordpress.org/Revision_Management
* Dashboard Recent Posts Extended - http://wordpress.org/extend/plugins/dashboard-recent-posts-extended/

== Installation ==

Download RecentRevisions from http://wordpress.org/extend/plugins/recent-revisions/

No need to unzip just leave it as it is. Then from your WordPress administration page, click on Plugins -> Add New -> Upload -> Browse…

When you have found the file click OK and then Install Now.

From the Plugins Page “Activate Now”

Then select Dashboard and **ensure your RecentRevisions are visible by selecting “Recent Revisions” under Screen Options (top right corner)**

== Screenshots ==

1. Recent Revisions Dashboard View
2. Recent Revisions Options
3. Recent Revisions Dashboard (De)Activate

== Frequently Asked Questions ==

**Why can’t I see any revisions?**
WP_POST_REVISIONS is most likely set to 0 or FALSE in your wp-config.php. This value is the number of previous post versions that are saved by WordPress and used for the revision history. When set to TRUE, all revisions are saved (WordPress default).
For further help, see the codex guide on editing wp-config.php - http://codex.wordpress.org/Editing_wp-config.php#Post_Revisions

**Does it work with custom post types?**
Yes, Recent Revisions supports custom post types!

Simply add **revisions** to 'supports' when declaring the custom post types:
http://codex.wordpress.org/Function_Reference/register_post_type

**I have a question / feature request**
Please create a topic in the support forum - https://wordpress.org/support/plugin/recent-revisions

== ChangeLog ==

**v1.1.1**

* Fix: Exclude Auto Drafts
* Update Screenshots

**v1.1**

* New option: Use GMT or local timezone
* Use date format of WP preferences
* New option: Link to differences
* Fix: Also show the most recent revision
* Fix: Show '(no title)' if post title is empty
* Add German Translation

**v1.0.5**

* Really minor formatting changes

**v1.0**

* First time out - feedback welcome.
