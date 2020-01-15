# Theme Settings

> In this section of the site, the editor can configure general options for the below blocks:

1. Past Sales index head
2. Featured Listings

These two blocks do not exist on specific pages in the admin. The editor customizes by using controls provided on options pages. Option pages can be found under the `Theme Settings` menu in the sidebar of the admin dashboard.

For the past sales page that lives under `/past-sales/` link, there are two option fields:
 
* head 
* sub 

which are both controlling this section here.

<iframe src="https://share.getcloudapp.com/yAuLAgLd?embed=true" width="575" height="400" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true">              </iframe>


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
 