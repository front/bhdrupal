
PHONEGAP
http://drupal.org/project/phonegap
====================================

DESCRIPTION
-----------
This project with its pairing phongap app is a bridge between Native apps on mobile and Drupal

FEATURES
-----------
- Mobile Authentication (from within Native app)
- Mobile uploading of content (from within Native app)
- Mobile display of Drupal VIews (from within Native app)

INSTALLATION
-----------
1) Copy phonegap directory to your modules directory
2) Enable the module at module administration page
3) Enable permission to upload content to mobile on the permissions page
4) Go to {yoursite.com/}admin/config/services/phonegap and configure which content type should be created for uploaded content, whether or not new content should be published and or promoted to the homepage and what input format should be used to render content (always be careful to an appropriate filter)
5) Check permissions 'post articles from mobile' to set which roles are allowed to post content
6) Install and enable Views if you wish to display
7) Install Drugap on your Android
8) From the app go to settings and enter the URL of your site
9) On the same settings page enter the name and display for the View you wish to use to return content
10) Save settings
11) On the mobile app, go to account and log in
12) Upload content from you mobile and view it back on the device 

The partner phonegap app source code can be downloaded from 

http://code.google.com/p/drupal-phonegap/downloads/list

Replace phonegap.js with the version that matches your phonegap version number and platform (IOS Blackberry
Android etc), and place www folder within your project

A compiled version of the Android app can be downloaded and installed to your phone (Android) from here

https://market.android.com/details?id=uk.co.adappt.drupalphonegap

Jon Anthony
