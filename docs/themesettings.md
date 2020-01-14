# Theme Settings

> In this section you can configure some additional general options that are applied to certain pages. 

1. Past Sales
1. Featured Listings

Due to the fact that these two section don't have a specific page, so the editor can customize them, the only way to provide controls for them is by creating these options pages which can be find under the `Theme Settings` menu in the sidebar of the admin dashboard.

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
* Max Listings
* Has mortgage calculator

There are these different cases here on where the data for the featured listings will come from:

* 1a : data based on pocket listings -  data are relationships from the listing custom post type and you can manually choose up to 5 
* 1b : data based on individual MLS ID - data are coming through the individual MLS ID number and market and this field is a repeater which means that you can use up to 5 different MLS ID numbers and markets
* 2 : data based on primary agent ID and their associated markets - data are coming from the selected agent DRE number. If the DRE number contains listings, then these will be fetched into the featured listings 
* 3 : data based on shortcode - data are coming from the shortcode provided inside the WYSIWYG editor.


Please note that the default max listings shown inside the featured listings block is 5 and you have the ability to change that number through the `max listings` field to a lower number. Also note that 5 is the max number that we can use in both occasions and if any of the first data sources allocate all available slots, then all the other data sources will be disregarded.
 
 Has mortgage calculator is used as an option to control on whether to show or hide Mortgage calculator inside listing details page.