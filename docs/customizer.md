# Customizer Settings

> In this section of the site, the editor can configure all of the General options that are applied site-wide.
> All of the General Settings of the site can be found under the admin menu `Appearance -> Customize`.
> Here, all of the options are separated into different sub-sections. 

Sub-sections:

1. Site Identity
2. Menus
3. General Settings
4. Widgets
5. Contact Details
6. Homepage Settings
7. Script Tags
8. Additional CSS - A place to add custom CSS in case you want to override the default CSS for part of the site.


### Site Identity
-------------------

> In this section of the site, the editor can configure all of the basic site identity options like Main Logo, Footer Logo, Site Title, etc. 

#### Sections
------------------

* Logo - Used in the header for both normal and sticky versions of header.
* Logo alternate - Used in the header for both normal and sticky versions of header.
* Footer logo - Shown at the top section of the footer side by side.
* Footer logo alternate - Shown at the top section of the footer side by side.
* Primary Brand Color
* Site Title - Used for general SEO purposes.
* Tagline - Used for general SEO purposes.
* Phone Number - Used at the callout block contact modal below the Gravity form and top header bar.
* Contact Email - Used in the top header bar and the callout block contact modal below the Gravity form.
* Company Address - Not currently used, but an available option
* Company Map Address - Not currently used, but an available option
* Hours of Operation - Used at the callout block contact modal below the Gravity form.
* Site icon (Favicon) - Favicon on browser tab

Head to `Appearance -> Customize` and then choose the `Site Identity` Menu.

Here you have the ability to change the below:
* Main logo 
* Footer logo 
* Site Title and Tag line 
* Footer copyrights
* Site icon 

Image format can be anything from jpg, jpeg, png, svg and gif, but recommend using SVG format because they leave the smallest footprint, in terms of byte size, on the site. If SVG is not an option, we recommend PNG because it provides background transparency.

The Site icon can be either a GIF, PNG OR SVG and needs to be at least 512x512 px in size for pixel based image formats like GIF or PNG. SVG doesn't need any specific pixels as it is vector based format.
You can use smaller resolution images like 128x128 or even 64x64 but this will make the logo more blurry and less high resolution for retina screens.


#### Menus
-------------------

In this section, the editor can order menus used across the site. Currently we use 4 different menus: 

* `Primary Menu` - Used in the primary header section.
* `Side nav` - Used in the side nav section when you press the hanburger menu and the side nav menu expands.
* `Footer Socket` - Used in the footer section between copyrights and social icons. 
* `Digital Listing Presentation Menu` - Used by Side Landing Page Generator.

You can configure the menus here: `Appearance -> Menus`

From both within the Customizer options or Menus, you can set the order of the menu items or even delete, add or edit a menu item.

Useful docs on how to manage your WordPress Menus:

* https://en.support.wordpress.com/menus/
* https://www.wpbeginner.com/beginners-guide/how-to-add-navigation-menu-in-wordpress-beginners-guide/ 

 

#### General Settings
--------------------

This sub-menu is used to store all General site settings. Currently, we only have one option but can be extended in the future.

Current option: 
* Dropdown to set the careers page - Used inside each individual career page so the editor can dynamically set the main career page to be used from the `Back to careers page`.

If you want to test this option follow the steps below:
1. Head to `Careers page` and choose one open position. 
2. When you choose one open position, you will be redirected to the details page of this opened position. 
3. At the top of this page you will find a link that points back to the careers page.


Please note: If you are not planning to change the careers page, then we recommended leaving as is.


#### Widgets
--------------------

Widgets can be added to different sections of the site to make the site more dynamic.
Currently we use 6 Widgetized areas across the site:

* Past Sales Top Section 
* Past Sales Bottom Section 
* Past Listings Details Bottom Section 
* Blog Top Section 
* Blog Bottom Section 
* IDX Horizontal Search


The 5 first widgets are used on all of the individual pages where we can add our re-usable blocks. The 6th widgetized area is owned by Side.
More about re-usable blocks in the Blocks section of this documentation.

Please note: You can add everything from static text, images, menu items and other custom widgets.
Additionally, since we used re-usable widgets inside our widgetized areas, we can only manage them through `Appearance -> Widgets` and not through the Customizer options.

Here you can find some useful docs on how to manage your WordPress Widgets:

* https://wordpress.org/support/article/wordpress-widgets/
* https://www.wpbeginner.com/glossary/widgets/
* https://www.youtube.com/watch?v=zx258_5Vv9Y


### Homepage Settings
---------------------

The only option inside this page is to set which page will be served as the Homepage. Currently it is set to the Homepage. If you decide to create a new homepage in the future, just head to this section and select the new page from the dropdown.


### Footer Options
-----------------

Two options exist on this submenu:

* Copyright
* Disclaimer


Both options can be seen at the footer section, one side by side with the menu item and one below it.
Footer disclaimer has been softly removed from the footer, but the Customizer option is still there when you need it.


### Social Media Icons
----------------------


In this section you can set your social media accounts. The only option needed for every social network is the link to the official page.
The social media networks supported:

* Facebook
* Twitter
* Instagram
* Linked in
* Youtube
* Flickr
* Vimeo
* Tumblr
* Dribble
* RSS

Please note: There is a checkbox in this section named `Show Social Media Icons`. This box must be checked for links to be visible at the footer and top header bar.


### Script Tags
--------------------

In this section you can configure the most popular script tags on the site without having to use a 3rd party plugin.
This section currently supports the below scripts:

* Google Analytics Tracking Code
* Google Tag Manager Tracking Code
* Facebook Pixel Code

To configure, add the unique id generated by the service and NOT the whole script tag. For example: For Google Analytics all you would have to add is `UA-147648636-2`.
Everything else is done programmatically.

Here you can find some useful docs on how to manage your script tags:

* https://support.google.com/analytics/answer/7476135?hl=en
* https://support.google.com/analytics/answer/1008080?hl=en
* https://www.youtube.com/watch?v=dNtciz-7Ips
* https://www.analyticsmania.com/post/google-tag-manager-id/
* https://www.analyticsmania.com/post/google-tag-manager-id/
* https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwiAlpCN9svmAhUO5HcKHe3XDY8YABAAGgJlZg&ohost=www.google.com&cid=CAESQeD2fihacPS1JJgx6N86QvbUEBrJCC94BRPnhlNtWRdqGXtJJudPxublugJZHwhDpKH39wEfUzM8HG0UcTLLJ4qb&sig=AOD64_1uYgwxS8jpHDvZpDl-mURx_X_W7w&q=&ved=2ahUKEwi1voeN9svmAhXLZ1AKHbtWBZYQ0Qx6BAgOEAE&adurl=
* https://www.facebook.com/business/help/952192354843755


### Typography
--------------------

This section is used to change the default font used by Side in favor of some of the most popular Google fonts. Currently there are more than 30 fonts available in this dropdown and you can add more if you like programmatically.

Please note: Even if you choose a font from the dropdown, the 'Enable Google Fonts' box must be checked to enable.


### Additional CSS
--------------------

This section allows the admin to override some of the CSS on the site.
Because CSS on the site is compiled into a minified version, we do not recommended anyone that is not a theme developer or WordPress expert in general, to touch those files. 

Here you can find some useful docs on how to add additional css to your site:

* https://en.support.wordpress.com/custom-design/editing-css/
* https://themeisle.com/blog/css-in-wordpress/
* https://www.hostinger.com/tutorials/wordpress-custom-css
