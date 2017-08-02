# MLLPro_FR
# maxgalleria-media-library.php
``` <php> <?php _e('Texte langue par défaut', 'Référence du fihcier de langue' ) ?>```

#Line 528, 4729, 4930 (not better to use a variable as it's called several times?):
```<html>
<div id="new-top-promo">
  <a id="mf-top-logo" target="_blank" href="http://maxfoundry.com"><img alt="maxfoundry logo" src="<?php echo MAXGALLERIA_MEDIA_LIBRARY_PLUGIN_URL ?>/images/mf-logo.png" width="140" height="25" ></a>
  <p class="center-text"><?php _e('Makers of', 'maxgalleria-media-library' ); ?> <a target="_blank"  href="http://maxbuttons.com/">MaxButtons</a>, <a target="_blank" href="http://maxbuttons.com/product-category/button-packs/">WordPress Buttons</a> <?php _e('and', 'maxgalleria-media-library' ); ?> <a target="_blank" href="http://maxgalleria.com/">MaxGalleria</a></p>						
  <p class="center-text-no-ital"><?php _e('Click here to', 'maxgalleria-media-library' ) ?> <a href="<?php echo MLF_TS_URL; ?>" target="_blank"><?php _e('Fix Common Problems', 'maxgalleria-media-library' ) ?></a></p>
  <p class="center-text-no-ital"><?php _e('Need help? Click here for', 'maxgalleria-media-library' ); ?> <a href="https://wordpress.org/support/plugin/media-library-plus" target="_blank"><?php _e('Awesome Support!', 'maxgalleria-media-library' ); ?></a></p>
  <p class="center-text-no-ital"><?php _e('Or Email Us at', 'maxgalleria-media-library' ); ?> <a href="mailto:support@maxfoundry.com">support@maxfoundry.com</a></p>
</div>
```
      
#Line 809:
``` 
$this->write_log("This folder was not found: $relative_dir"); /* FRED-20170802 : needed on log? $this->write_log __('This folder was not found: $relative_dir', 'maxgalleria-media-library' ); */
``` 
      
#Line 999:

``` 
//echo "<p id='scanning-message'>". _e('Scanning the Media Library for existing folders...Please wait.', 'maxgalleria-media-library' ) ."."</p>";
``` 
      
#Line 1631:
``` 
"label": "<?php /* FRED-20170802  */ _e('Delete this folder?','maxgalleria-media-library'); ?>",
``` 

#Line 1645:
``` 
if(confirm("<?php _e('Are you sure you want to delete the selected folder?','maxgalleria-media-library'); ?>")) {
``` 

#Line 1676:
``` 
"label": "<?php /* FRED-20170802  */ _e('Hide this folder?','maxgalleria-media-library'); ?>",
``` 

#Line 1685:
``` 
if(confirm("<?php /* FRED-20170802  */ _e('Are you sure you want to hide the selected folder and all its sub folders and files?','maxgalleria-media-library'); ?>")) {
``` 

#Line 1904:
``` <html>
<p class="center-text"><?php echo $row_count; ?> <?php _e('files were found. Choose to display the images or just the file names?', 'maxgalleria-media-library' ) ?></p>
``` 
#Line 1906:
``` <html>
<a id="display_mlpp_images" folder_id="<?php echo $current_folder_id; ?>" image_link="<?php echo $image_link; ?>" class="gray-blue-link"><?php _e('Display images', 'maxgalleria-media-library' ) ?></a>
``` 

#Line 1907:
``` <html>
<a id="display_mlpp_titles" folder_id="<?php echo $current_folder_id; ?>" image_link="<?php echo $image_link; ?>" class="gray-blue-link"><?php _e('Display image file names only', 'maxgalleria-media-library' ) ?></a>	
``` 
#Line 2793:
``` 
echo '  <h2 class="mgmlp-title">'. __('Media Library Folders Pro Search Results','maxgalleria-media-library') .'</h2>' . PHP_EOL;
``` 

#Line 2795:
``` 
echo '  <span id="back-wraper"><a href="' . site_url() . '/wp-admin/admin.php?page=media-library-folders">'. __('Back to Media Library Folders Pro Folders','maxgalleria-media-library').'</a></span>' . PHP_EOL;
``` 

#Line 2800:
``` 
echo "<div id='search-instructions'>". __('Click on an image to go to its folder or a on folder to view its contents.','maxgalleria-media-library')."</div>";
``` 
#Line 2803:
``` 
echo "<h4>".__('Search results for:','maxgalleria-media-library'). $search_string ."</h4>" . PHP_EOL;
``` 
#Line 2927:
``` 
echo __('Invalid file name.','maxgalleria-media-library');
``` 
#Line 2932:
``` 
echo __('The file name cannot contain spaces or tabs.','maxgalleria-media-library');
``` 

#Line 4425:
``` 
printf(__('Unknown error with %s','maxgalleria-media-library'), $base_name);
``` 

#Line 4436:
``` 
printf(__('Thumbnails have been regenerated for %s image(s)','maxgalleria-media-library'), $counter);
``` 
