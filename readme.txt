=== Embed videos and respect privacy ===
Contributors: michael.zangl, bernhard.kabelka
Tags: youtube, germany, deutschland
Requires at least: 4.5
Tested up to: 6.6.1
Stable tag: 2.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows you to embed YouTube/Vimeo videos without sending data to Google/Vimeo on every page view. Required for a GDPR (German: DSGVO) compliant website.

== Description ==

This is meant to be used in the European Union, but can be used in any other country where you want some more privacy for your users.

No settings required, YouTube and Vimeo links get replaced automatically. Adjust the displayed message according to your local needs. Optionally, other media included via [embed] can be replaced as well.

See https://github.com/michaelzangl/wp-video-embed-privacy/wiki for more technical information.

= German Background =

Das deutsche Datenschutzrecht - und jetzt die europäische DSGVO - ist relativ streng. Der normale YouTube-Link zum Einbinden entspricht nicht (unbedingt) den Datenschutzbestimmungen.

Dieses Plugin baut erst eine Verbindung zu YouTube bzw. Vimeo auf, wenn der Nutzer aktiv auf den Abspielen-Knopf klickt.

Es ist kein Setup erforderlich: YouTube- und Vimeo-Links werden automatisch ersetzt. Die angezeigten Nachrichten können bei Bedarf an lokale Bedürfnisse angepasst werden. Zusätzlich können optional auch andere über [embed] eingebundene Medien ersetzt werden.

== Installation ==

You need to enable url_allow_fopen.

As any other WordPress plugin.

Download the relase zip from the github repository or from wordpress.org, upload it to your WordPress.

It simply works out of the box, no configuration required.

== Frequently Asked Questions ==

If you find a problem, please open an issue on GitHub: https://github.com/michaelzangl/wp-video-embed-privacy/issues

= How to add a YouTube video =

Simply post the YouTube link as usual. Or use the [embed] shortcode. Do not use the HTML embed link (<embed...>).

= Can I enable caching? =

Yes, select the corresponding checkbox in settings.

== Screenshots ==

1. Example video before the YouTube-Player is loaded

== Changelog ==

= 1.0 =
* First version

= 1.2 =
* Add link to Google privacy page

= 2.0 =
* Add settings
* Internationalize
* Prevent external requests to preview generator

= 2.1 =
* Add Vimeo
* Fix some styling issues

= 2.2 =
* Fix a small bug with the previews

= 2.3 =
* Add filter for option texts
* Minor clean-up
