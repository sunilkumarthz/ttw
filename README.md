# Taxonomy Thumbnail and Widget
TTW plugin is used for add thumbnail option for inbuilt and custom taxonomy terms and access them with short code and widget.

# Description
Using Taxonomy Thumbnail and widget plugin user can make  thumbnail option for inbuilt and custom taxonomy terms and access via widget (Taxonomy Term List) in sidebar and also use in page/post using shortcode.
Use `<?php if (function_exists('ttw_thumbnail_url')) echo ttw_thumbnail_url(); ?>` to get the url and put it in any img tag or simply use `<?php if (function_exists('ttw_thumbnail_image')) echo ttw_thumbnail_image(); ?>` in (category or taxonomy) template.

Arguments in above functions :

	1. ttw_thumbnail_url($termid , $size);
	2. ttw_thumbnail_image($termid , $size);
  
 # Plugin advantage
* Easy to configuration.
* Unblockable.
* Plugin supports Chrome, Firefox, Safari and IE
* Woocommerce Compatible
* Shortcode

# Plugin configuration 

* Drag and drop the widget `(Taxonomy Term List)`
* Shortcodes : 
	`[TTW_TERMS taxonomy='category' class='taxonomy-term-list']`
	
	For Show current post/product taxonomies
	
	`[TTW_POST_TERMS_ICON taxonomy="product_tag"  class=""  hide_empty="" post_id=""]`
	Note :
    post_id is not required
    Taxonomy is required

# Installation
You can install Categories Images directly from the WordPress admin panel:

	1. Go to wp-admin -> Plugins > Add New -> and search for 'Taxonomy Thumbnail and Widget'.
	2. Click to install.
	3. Once installed, activate.
	
OR

Manual Installation:

	1. Upload the entire `taxonomy-thumbnail-widget` folder to the `/wp-content/plugins/` directory.
	2. Activate the plugin through the 'Plugins' menu in WordPress.
	3. Go to `wp-admin -> Settings -> TTW Settings` and select taxonomies for which you want thumbnail
	4. And For access taxonomies list in sidebar go to `wp-admin -> Appearance -> Widgets -> Taxonomies List widget`


