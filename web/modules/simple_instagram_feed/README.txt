Simple Instagram Feed Block

ABOUT
Simple Instagram Feed is an integration module for the jquery.instagramFeed library
that can be found at https://github.com/jsanahuja/jquery.instagramFeed.

BENEFITS
Unlike many Instagram integrations, this module does not require a complicated token
and authorization sequence to use. Simply add the jquery.instagramFeed library,
install this module and place the block, assign the Instagram account that you would
like to pull the feed from and save. If you want to change the number of images or any
other settings, use the block settings.

USAGE
Once you have installed Simple Instagram Feed Block and placed the jquery.inatagramFeed
library in your libraries directory, navigate to Structure -> Block Layout (/admin/structure/block)
to create a new Simple Simple Instagram Feed block on your site. By default the block will use
the Instagram account and display 12 images, 6 images per row. You can change the Instagram user
account, number of images and number of images per row settings as well as displaying the Profile
and Bio for the Instagram account.

DEPENDENCIES
Requires the jquery.instagramFeed library that can be found at
https://github.com/jsanahuja/jquery.instagramFeed.

INSTALLATION
Download the repository for the jquery.instagramFeed library that can be found at
https://github.com/jsanahuja/jquery.instagramFeed and place the file jquery.instagramFeed.min.js
in a directory called: jqueryinstagramfeed

Install the Simple Instagram Feed Block:
  Using DRUSH: drush en simple_instagram_feed
  -or-
  Download it from https://www.drupal.org/project/simple_instagram_feed and install it to your website.

KNOWN LIMITATIONS
If you would like to have different feeds on different pages, you can create as many feed blocks as you like
however, currently you can not have more than one feed per page. This is being worked on and will hopefully
be resolved for the next release.
