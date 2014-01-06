=== SO Related Posts ===
Contributor: senlin
Donate link: http://so-wp.com/donations
Tags: related posts
Requires at least: 3.6
Tested up to: 3.9-alpha
Stable tag: 2014.01.06
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This Meta Box plugin Addon lets the user choose one or more Related Posts from all published Posts and shows them underneath the Post.

== Description ==

For a while already I have been breeding on how to make a Related Posts plugin that doesn't query the database n times looking for related posts by tags, categories or what not. Most of the existing Related Posts plugin have an incredible (negative) impact on your site speed, so the benefits don't outweigh the costs.

Instead I was thinking that it would be much more flexible too if the user can choose his/her own Related Posts from a simple Posts drop down.

As the [Meta Box plugin](http://wordpress.org/plugins/meta-box/) by [Rilwis](http://profiles.wordpress.org/rilwis/) already comes with both a Post field and a Repeater field, I have combined these two and made it so that you can now show as many Related Posts as you want underneath the current Post. 

The Addon doesn't come with any settings; you can just choose which Posts to add. The meta box is only visible in the Edit Post screen.

I have decided to only support this plugin through [Github](https://github.com/senlin/so-related-posts/issues). Therefore, if you have any questions, need help and/or want to make a feature request, please open an issue over at Github. You can also browse through open and closed issues to find what you are looking for and perhaps even help others.

**PLEASE DO NOT POST YOUR ISSUES VIA THE WORDPRESS FORUMS**

Thanks for your understanding and cooperation.

== Installation ==

Go to **Plugins > Add New** in your WordPress Dashboard, do a search for "so related posts" and install it.

 &hellip; OR &hellip;


 1. Download zip file.

 2. Upload the zip file via the Plugins > Add New > Upload page &hellip; OR &hellip; unpack and upload with your favourite FTP client to the /plugins/ folder.

 3. Activate the plugin on the Plug-ins page.

Done!


== Frequently Asked Questions ==

= Where are the Settings? =

You can stop looking, there are no settings. When you go into your Post Edit screen, you will see the Related Posts Metabox where you can choose Related Posts for your current Post.

= Why is the plugin showing an error message after activation? =

This plugin is an Addon for the [Meta Box plugin](http://www.deluxeblogtips.com/meta-box/). If you don't have that installed, this Addon is useless, so better not install it.

= I don't like the output on my Single Post, can I change anything? =

Yes, you can. The output comes in its own class (`so-related-posts`) and in it you will find an `h4` for the title and an unordered list which has a class of `related-posts`. In your theme's `style.css` you can add any styling as you please.

= I have an issue with this plugin, where can I get support? =

Please open an issue on [Github](https://github.com/senlin/so-related-posts/issues)

== Screenshots ==

none

== Changelog ==

= 2014.01.06 =

* first release