WordPress Quick Install
=======================

I keep this script on my server so that I can start an up-to-date WordPress project almost anywhere, along with the plugins I enjoy and am used to working with.  It's hosted here on GitHub, so I can execute this from the terminal by typing:

`curl https://raw.github.com/snaptortoise/wordpress-quick-install/master/wordpress | sh`

It will download the latest version of WordPress, along with the latest version of all the plugins listed at the end of this README doc, and install them to the current directory.  I find it saves time.

Alternatively, you can make the `wordpress`  file executable and keep it somewhere in your `$PATH` if you're rather keep it local.

Plugin List
-----------
- All-in-One-SEO-Pack
- Sitemap Generator
- Secure WordPress
- Hierarchy Plugin
- Image Widgets (Why isn't this standard?)
- Super-cache
- W3 Total Cache (A little redundant with above, but hey, I like options.)
- Register Plus Redux (Good for membership-style sites)
- Regenerate Thumbnails (good for when you need to change custom thumb sizes late in a project)
- Taxonomy Taxi
- Custom Post Type UI 
- WordPress Importer
- Password Protect WordPress
- WP-Quick-Pages
- FeedWordPress
- BackWPup
