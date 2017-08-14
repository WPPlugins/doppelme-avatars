=== DoppelMe Avatar Buddypress Integration ===
Contributors: doppelme
Donate Link: 
Tags: avatars, buddypress, doppelme, avatar
Requires at least: 3.3.1 & Buddypress 1.5.4
Tested up to: 3.6.0
Stable tag: 1.04

Adds user editable avatars to Buddypress. Users can create and edit their own avatars within your BuddyPress installation.

== Description ==

Adds user editable avatars to Buddypress. Users can create and edit their own avatars within your BuddyPress installation.

* Easy for users to update their avatar based on their mood.
* Lots of fun items for your users to play with
* Removes the need to moderate uploaded avatars


== Installation ==


Requires SOAP and Simple XML PHP modules (normally installed as standard)

You'll need to register your website via this link: http://partner.doppelme.com/register.php, then whitelist the IP address 
your site is hosted on.

Once you have these, place this in your wp-config.php file with the partner ID and Key define( 'BP_DOPPELME_PARTNER_ID', 'XXX' ); define( 'BP_DOPPELME_PARTNER_KEY', 'XXX' );

== Frequently Asked Questions ==  

= Can I edit which avatar items are available to my users? =

Yes, just visit http://partner.doppelme.com to modify the items that are available to your users.


= I get Access Permission Failed message. How can I resolve? =

Got to http://partner.doppelme.com and add your site's IP address to the whitelist. Alternatively, if you don't know your IP address, enter * to match all addresses.


== Screenshots ==

1. The avatar editor as part of the users profile area
2. Updating your avatar
3. Users' avatars used on the site


== Upgrade Notice ==

* None

== Changelog ==
**Version 2.0**
* Updates from HWDSB 

**Version 1.04**
* Removal of whitespace

**Version 1.03**
* Correction for missing files

**Version 1.02**

* Support for 1.7 theme compatibility
* Tested with BP 1.7.2

**Version 1.01**

* Force re-check of access permissions from admin panel
* Tested with BP 1.6.4

**Version 1.00

* First version marked as stable

**Version 0.13**

* First public release

