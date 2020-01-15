<p>
<img src="https://i.imgur.com/rMRS3Tk.png" alt="">
</p>

## Table of Contents
* <a href="customizer">Customizer Options</a>
* <a href="theme">Theme Settings</1>
* <a href="posttypes">Custom Post Types</a>
* <a href="blocks">Blocks</a>


<h3 id="customizer">Customizer Options</h3>

> In this section of the site, the editor can configure all of the General options that are applied site-wide.
> All of the General Settings of the site can be found under the admin menu `Appearance -> Customize`.
> Here, all of the options are separated into different sub-sections. 

__Sub-sections:__

1. Site Identity
2. Menus
3. General Settings
4. Widgets
5. Contact Details
6. Homepage Settings
7. Script Tags
8. Additional CSS - A place to add custom CSS in case you want to override the default CSS for part of the site.


<h3>Site Identity</h3>

> In this section of the site, the editor can configure all of the basic site identity options like Main Logo, Footer Logo, Site Title, etc. 

<h3>Sections</h3>

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


<h3>Menus</h3>

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

 

<h3>General Settings</h3>

This sub-menu is used to store all General site settings. Currently, we only have one option but can be extended in the future.

Current option: 
* Dropdown to set the careers page - Used inside each individual career page so the editor can dynamically set the main career page to be used from the `Back to careers page`.

If you want to test this option follow the steps below:
1. Head to `Careers page` and choose one open position. 
2. When you choose one open position, you will be redirected to the details page of this opened position. 
3. At the top of this page you will find a link that points back to the careers page.


Please note: If you are not planning to change the careers page, then we recommended leaving as is.


<h3>Widgets</h3>
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


<h3>Homepage Settings</h3>
The only option inside this page is to set which page will be served as the Homepage. Currently it is set to the Homepage. If you decide to create a new homepage in the future, just head to this section and select the new page from the dropdown.


<h3>Footer Options</h3>

Two options exist on this submenu:

* Copyright
* Disclaimer


Both options can be seen at the footer section, one side by side with the menu item and one below it.
Footer disclaimer has been softly removed from the footer, but the Customizer option is still there when you need it.




<h3>Social Media Icons</h3>


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


<h3>Script Tags</h3>

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


<h3>Typography</h3>

This section is used to change the default font used by Side in favor of some of the most popular Google fonts. Currently there are more than 30 fonts available in this dropdown and you can add more if you like programmatically.

Please note: Even if you choose a font from the dropdown, the 'Enable Google Fonts' box must be checked to enable.


<h3>Additional CSS</h3>

This section allows the admin to override some of the CSS on the site.
Because CSS on the site is compiled into a minified version, we do not recommended anyone that is not a theme developer or WordPress expert in general, to touch those files. 

Here you can find some useful docs on how to add additional css to your site:

* https://en.support.wordpress.com/custom-design/editing-css/
* https://themeisle.com/blog/css-in-wordpress/
* https://www.hostinger.com/tutorials/wordpress-custom-css


--------------------------------------------------------------------



<h2 id="theme">Theme Settings</h2>

> In this section of the site, the editor can configure general options for the below blocks:

1. Past Sales index head
2. Featured Listings

These two blocks do not exist on specific pages in the admin. The editor customizes by using controls provided on options pages. Option pages can be found under the `Theme Settings` menu in the sidebar of the admin dashboard.

For the past sales page that lives under `/past-sales/` link, there are two option fields:
 
* head 
* sub 

which are both controlling this section here.

<iframe src="https://share.getcloudapp.com/yAuLAgLd?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


For the featured listings that are used by the Featured listings Block, there are five option fields:

* MLS ID (repeater field)
* Pocket Listings (relationship field)
* Primary Agent ID (relationship field)
* Active Listings Shortcode (WYWIWYG editor)
* Max Listings - The default max listings shown inside the block is 5. The editor has the ability to decrease the number of listings shown by selecting a different number in the `max listings` field. Additionally, if all available slots are taken, then other data sources will be disregarded.
* Has mortgage calculator - Used as an option to show or hide the Mortgage calculator data on the listing details page.

Different cases that the featured listings data will come from:

* 1a : data based on pocket listings -  data are relationships from the listing custom post type and you can manually choose up to 5 
* 1b : data based on individual MLS ID - data are coming through the individual MLS ID number and market and this field is a repeater which means that you can use up to 5 different MLS ID numbers and markets
* 2 : data based on primary agent ID and their associated markets - data are coming from the selected agent DRE number. If the DRE number contains listings, then these will be fetched into the featured listings 
* 3 : data based on short code - data are coming from the short code provided inside the WYSIWYG editor.
 
 
 --------------------------------------------------------------------
 
 
 <h2 id="posttypes">Post Types</h2>
 
 > In this section we cover all available custom post types on the site.
 
 1. Members
 1. Testimonials
 1. About
 1. Community Details
 1. Sell & Buy
 
 
<h3>Members</h3>
 
 This custom post type includes all team members along with their respective default (D) & custom (C) fields and is used on both headshot block and agent details bar block:
 
 * Title (D) - Used only on the admin columns to show the member that you want to edit.
 * Description (D) - Shown inside the modal of each individual member in headshots block.
 * Featured image (D)
 * First Name (C)
 * DRE (C) - Shown inside the member card and inside the modal.
 * Position (C) - Shown inside the member card and inside the modal.
 * Phone Number (C) - Shown on the headshot modal.
 * Email (C): Shown on the headshot modal.
 * Show contact button (C) - Shown on agent details bar. Can toggle on/off and currently used on pocket listings page.
 * Show schedule button (C) - Shown on agent details bar. Can toggle on/off and currently used on pocket listings page.
  
 
<h3>Testimonials</h3>
 
 This custom post type includes all the testimonials along with their respective default (D) & custom (C) fields which are used in testimonials small, testimonials large and testimonials compact block:
 
 * Main title (D) - Used in the admin columns section to identify which testimonial you want to edit.
 * Description (D) - Acts as the testimonial review (body) and it is a text editor.
 * Featured Image (D) - Background image shown behind the testimonial large and testimonials small block.
 * Title (C)- Simple text field.
 * Client Name (C)- Simple text field.
 * Client Info (C)- Simple text field.
 * CTA (C)- Can choose either a page from your site, an external link or a custom link. Have the ability to change the text, link and link target.
 * Review Link (C)- Can choose either a page from your site, an external link or a custom link. Have the ability to change the text, link and link target.
 
 
 <h3>About, Community Details and Sell & Buy CPT</h3>
 -------------------------------------------------
 
 All these custom post types are created in order to provide some pre-filled blocks to the content editor when they try to create a new page.
 Depending on the page that you are editing, you will see different blocks getting pre-filled on each page.  


--------------------------------------------------------------------


<h2 id="blocks">Blocks</h2>

> This section outlines all of the blocks on the site and admin options.


Blocks:


* Agent Details bar
* Callout block
* Callout blocks
* CTA block
* Featured listings
* Headshots block
* List slider
* Listings card grid
* Map
* Media element
* Media element map
* Press block
* Section head
* Stat block
* Testimonials large
* Testimonials small
* Testimonials compact


<h3>Agent Details Bar</h3>

This block is used to show the agent details bar shown below:

<iframe src="https://share.getcloudapp.com/7Kuyj99J?embed=true" width="575" height="50" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains 3 custom fields:

* Agent (relationship field)
* Show contact button
* Show schedule button


The Agent field is a relationship field which queries the Members CPT and you can use a specific member to be shown in this agent details bar.

Please note: only 1 agent can be added per block.

Both show the contact button and show schedule button are toggle fields which are used to show the buttons for both contact and schedule modals.


<h3>Callout Block</h3>--
This block is used to show the callout block shown below:

<iframe src="https://share.getcloudapp.com/9ZuNz124?embed=true" width="575" height="200" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains of the following custom fields:

* Header - The header title of the block.
* Sub - The sub title of the block.
* Block Size - It can be either default which is the default height and width or full which is used as a hero at the top of some pages like the homepage.
* Block Type - It can be either solid BG color, image or video. For the video option there is an additional mobile fallback image that we recommend using to achieve optimal site performance.
* Has modal - A toggle option that enables a modal when site user clicks on the CTA button. The CTA button text is always "contact" by default.
* Select modal form - This option is only shown when the above option is enabled and gives the editor the ability to choose what gravity form the want to appear on the front-end.
* Button - The editor can set url link and text.
* Button Style - This is a dropdown field that contains 4 different options (solid primary, solid secondary, stroke black and stroke white) where stroke white is the default value.


<h3>Callout Blocks</h3>-
This block is used to show the below callout blocks:

<iframe src="https://share.getcloudapp.com/E0uERp5d?embed=true" width="575" height="200" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains only one unique option and this is "Items" which is a repeater that repeats the callout block fields. Only two items can be added per callout block.

<h3>CTA</h3>------------

This block is used to show the CTA block shown below:

<iframe src="https://share.getcloudapp.com/Z4uwmRGl?embed=true" width="575" height="200" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

It is a more simplified version of callout blocks and consists of the following fields:

* Header - The header title of the block
* Sub - The sub title of the block
* Button - This is a link field in which you can choose the link of the button, text and link target
* Button Style - This is a dropdown field which contains 4 different options (solid primary, solid secondary, stroke black and stroke white) where stroke white is the default value


<h3>Featured Listings</h3>

This block is used to show the Featured Listings block shown below:

<iframe src="https://share.getcloudapp.com/NQuv4097?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block doesn't have any fields because all options exist inside `Theme Settings -> Featured Listings`


<h3>Headshots</h3>------

This block is used to show the Headshots block shown below:

<iframe src="https://share.getcloudapp.com/d5ueyq5W?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block consists of 2 fields:

* Agent - A relationship field that queries the Members CPT and editor can choose between different members that they want to show inside the headshots block. The editor has the ability to add, remove or order the different members.
* Has Slider - A toggle field that provides the ability to show the headshots block as a slider carousel instead of a grid.


<h3>List Slider</h3>----

This block is used to show the List Slider block shown below:

<iframe src="https://share.getcloudapp.com/2Nur6Ogn?embed=true" width="250" height="400" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block consists of 1 main field and another 3 sub fields:

* Items - This is a repeater field that includes 3 sub fields inside it. You can add up to 7 different fields and you have the ability to add, remove or re-order these items
* Head - The head title that is used on both the list slider nav and list slide body
* Sub - The sub title that is used inside the list slide body below the head title
* Sub - The body text that is used inside the list slide body below the sub title

Please note: The numbering is dynamically generated so you don't have to add those number items manually. Also the numbers are inline SVGs which means that once we change the primary branding color, these numbers change as well.
 

<h3>Listing Cards Grid</h3>

<iframe src="https://share.getcloudapp.com/04ugyXEO?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block doesn't include any options as it take listings from HJ pocket listings.


<h3>Map</h3>------------

This block is used to show the Map block shown below:

<iframe src="https://share.getcloudapp.com/P8uYN4ye?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains only one field. The map address field utilizes Google maps API behind the scenes.


<h3>Media Element</h3>--

This block is used to show the Media Element shown below:

<iframe src="https://share.getcloudapp.com/z8unl0GQ?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block consists of the following fields:

* Header text - the header title of the block
* Body text - the body text of the block
* Image - the image of the block 
* CTA - the button of the block which includes a link, text and a link target.
* Button Style - This is a dropdown field which contains 4 different options (solid primary, solid secondary, stroke black and stroke white) where stroke white is the default value
* Reverse - This is a toggle field which allows the media element to reverse the order of text and image.



<h3>Media Element Map</h3>

This block is exactly the same as the Media Element block, but instead of an image, the block shows a map.

This block also includes an address field that utilizes Google maps API behind the scenes.


<h3>Press</h3>----------
This block is used to show the Press block below:

<iframe src="https://share.getcloudapp.com/bLuGOnL1?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block consists of the following fields:

* Items - this is a relationship field that queries the Posts.
* CTA - the button of the block which includes a link, text and a link target.
* Has Title - This is a toggle field which is used to whether show or hide a section title above the press block
* Section title - the section title of the block that is shown above the press block
* Title alignment - the alignment of the section title. It can be left, center or right 


<h3>Stat Block</h3>-----
This block is used to show the Stat block below:

<iframe src="https://share.getcloudapp.com/llu4gGj4?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block contains the following custom fields:

* Has title - Whether the stat block has a section title above the stat bloc items.
* Section title - The section title of the block that is shown above the stat block.
* Title alignment - the alignment of the section title. It can be left, center or right.
* Items - A repeater field that includes sub fields inside it and there is a limit of 3 items per block.
* Text - The subfield inside the items field. Used to show the title of the stat block.
* Number - The subfield inside the items field. Used to show the number of the stat block.

Please note: The numbers animation is programmatic, and the numbers start "rolling" when the block is in viewport.  


<h3>Testimonials Large</h3>
This block is used to show the testimonials large block shown below:

<iframe src="https://share.getcloudapp.com/p9u5Lqjn?embed=true" width="575" height="250" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>

This block contains an "Items" field which is a relationship field that queries the testimonials CPT. The editor can add as many testimonials as they want.

Please note: If only one testimonial is added, then the carousel functionality is disabled.

<h3>Testimonials Small</h3>
This block is used to show the testimonials small block shown below:

<iframe src="https://share.getcloudapp.com/o0uQ9nDY?embed=true" width="575" height="150" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains an "Items" field which is a relationship field that queries the testimonials CPT. The editor can add as many testimonials as they want.

Please note: If only one testimonial is added, then the carousel functionality is disabled.


<h3>Testimonials Compact</h3>
This block is used to show the testimonials compact block shown below:


<iframe src="https://share.getcloudapp.com/yAuLA524?embed=true" width="575" height="150" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


This block contains an "Items" field which is a relationship field that queries the testimonials CPT. The editor can add as many testimonials as they want.

Please note: If only one testimonial is added, then the carousel functionality is disabled.

