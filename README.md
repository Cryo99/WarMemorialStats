# WarMemorialStats

A userscript that shows War Memorial Series cache stats on geocaching.com. It adds the [War Memorial Series](https://www.warmemorialseries.co.uk/) banner in the following places:

* the Stats Bar area of your account dashboard (old UI);
* the sidebar of your account dashboard (new UI)
* your public profile (old and new UIs);
* other users' profiles (old and new UIs);
* War Memorial Series cache pages.

On cache pages it adds the C. O.'s banner as well.

__Please note:__ War Memorial Series caches have a range of names and are harder to match. If you find one that doesn't display the banner, please let me know so I can include it.

## Credits

This script was inspired by, and is based on, James Inge's [Church Micro Stats](https://greasyfork.org/en/scripts/9641-church-micro-stats) and works in concert with it, as you can see from the screen shots. Thanks and credit should go to James for his efforts.

The icon image is extracted from the War Memorial Series banner by Chris AKA Bus.Stop

__Please note:__ in order for the banner to be added to your public profile, you need to have some content in the "Bio" area (old UI) or About tab (new UI). If this area is empty, the necessary container is not generated by the site. An empty HTML comment (&#60;!-- --&#62;) is sufficient and prevents the need for unwanted output in your profile. This is also true for James' Church Micro Stats. This may be fixed in a later version.

__Update:__ This should no longer be true in the new UI.

## Version History

### Version 1.0.0

* Rewritten to use [GCStatsBannerLib](https://greasyfork.org/en/scripts/389508-gc-stats-banner-library).
* Updated to work on the new accounts page.

### Version 0.0.3

* Internal changes.

### Version 0.0.2

* Improved cache matching for the various names used in the series.
* Internal changes.

### Version 0.0.1

* Initial release.
