=== Banner Display Thumbnail ===
Contributors: Module Express
Donate link: http://beautiful-module.com/
Tags: responsive Banner Display Thumbnail,Banner Display Thumbnail,mobile touch Banner Display Thumbnail,image slider,responsive header gallery slider,responsive banner slider,responsive header banner slider,header banner slider,responsive slideshow,header image slideshow
Requires at least: 3.5
Tested up to: 4.4
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A quick, easy way to add an Responsive header Banner Display Thumbnail OR Responsive Banner Display Thumbnail inside wordpress page OR Template. Also mobile touch Banner Display Thumbnail

== Description ==

This plugin add a Responsive Banner Display Thumbnail in your website. Also you can add Responsive Banner Display Thumbnail page and mobile touch slider in to your wordpress website.

View [DEMO](http://beautiful-module.com/demo/banner-display-thumbnail/) for additional information.

= Installation help and support =

The plugin adds a "Responsive Banner Display Thumbnail" tab to your admin menu, which allows you to enter Image Title, Content, Link and image items just as you would regular posts.

To use this plugin just copy and past this code in to your header.php file or template file 
<code><div class="headerslider">
 <?php echo do_shortcode('[bdt_gallery.slider]'); ?>
 </div></code>

You can also use this Banner Display Thumbnail inside your page with following shortcode 
<code>[bdt_gallery.slider] </code>

Display Banner Display Thumbnail catagroies wise :
<code>[bdt_gallery.slider cat_id="cat_id"]</code>
You can find this under  "Banner Display Thumbnail-> Gallery Category".

= Complete shortcode is =
<code>[bdt_gallery.slider cat_id="9" autoplay="true"]</code>
 
Parameters are :

* **limit** : [bdt_gallery.slider limit="-1"] (Limit define the number of images to be display at a time. By default set to "-1" ie all images. eg. if you want to display only 5 images then set limit to limit="5")
* **cat_id** : [bdt_gallery.slider cat_id="2"] (Display Image slider catagroies wise.) 
* **autoplay** : [bdt_gallery.slider autoplay="true"] (Set autoplay or not. value is "true" OR "false")

= Features include: =
* Mobile touch slide
* Responsive
* Shortcode <code>[bdt_gallery.slider]</code>
* Php code for place image slider into your website header  <code><div class="headerslider"> <?php echo do_shortcode('[bdt_gallery.slider]'); ?></div></code>
* Banner Display Thumbnail inside your page with following shortcode <code>[bdt_gallery.slider] </code>
* Easy to configure
* Smoothly integrates into any theme
* CSS and JS file for custmization

== Installation ==

1. Upload the 'banner-display-thumbnail' folder to the '/wp-content/plugins/' directory.
2. Activate the 'Banner Display Thumbnail' list plugin through the 'Plugins' menu in WordPress.
3. If you want to place Banner Display Thumbnail into your website header, please copy and paste following code in to your header.php file  <code><div class="headerslider"> <?php echo do_shortcode('[bdt_gallery.slider limit="-1"]'); ?></div></code>
4. You can also display this Images slider inside your page with following shortcode <code>[bdt_gallery.slider limit="-1"] </code>


== Frequently Asked Questions ==

= Are there shortcodes for Banner Display Thumbnail items? =

If you want to place Banner Display Thumbnail into your website header, please copy and paste following code in to your header.php file  <code><div class="headerslider"> <?php echo do_shortcode('[bdt_gallery.slider limit="-1"]'); ?></div>  </code>

You can also display this Banner Display Thumbnail inside your page with following shortcode <code>[bdt_gallery.slider limit="-1"] </code>



== Screenshots ==
1. Designs Views from admin side
2. Catagroies shortcode

== Changelog ==

= 1.0 =
Initial release