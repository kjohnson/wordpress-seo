=== Yoast SEO ===
Contributors: yoast, joostdevalk, tacoverdo, omarreiss, atimmer, jipmoors
Donate link: https://yoast.com/
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Tags: SEO, XML sitemap, Google Search Console, Content analysis, Readability
Requires at least: 4.6
Tested up to: 4.8.1
Stable tag: 5.3.1
Requires PHP: 5.2.4

Improve your WordPress SEO: Write better content and have a fully optimized WordPress site using the Yoast SEO plugin.

== Description ==

WordPress out of the box is already technically quite a good platform for SEO. This was true when Joost wrote his original [WordPress SEO](https://yoast.com/articles/wordpress-seo/) article in 2008 (updated every few months) and it's still true today, but that doesn't mean you can't improve it further! This plugin is written from the ground up by Joost de Valk and his team at [Yoast](https://yoast.com/) to improve your site's SEO on *all* needed aspects. While this [Yoast SEO plugin](https://yoast.com/wordpress/plugins/seo/) goes the extra mile to take care of all the technical optimization, more on that below, it first and foremost helps you write better content.  Yoast SEO forces you to choose a focus keyword when you're writing your articles, and then makes sure you use that focus keyword everywhere.

> <strong>Premium Support</strong><br>
> The Yoast team does not always provide active support for the Yoast SEO plugin on the WordPress.org forums. One-on-one email support is available to people who bought the [Premium Yoast SEO plugin](https://yoast.com/wordpress/plugins/seo-premium/) only.
> Note that the Premium SEO plugin has several extra features too, including the option to have multiple focus keywords and a redirect manager, so it might be well worth your investment!
>
> You should also check out the [Yoast Local SEO](https://yoast.com/wordpress/plugins/local-seo/), [Yoast News SEO](https://yoast.com/wordpress/plugins/news-seo/) and [Yoast Video SEO](https://yoast.com/wordpress/plugins/video-seo/) extensions to Yoast SEO. These of course come with support too.

> <strong>Bug Reports</strong><br>
> Bug reports for Yoast SEO are [welcomed on GitHub](https://github.com/Yoast/wordpress-seo). Please note GitHub is _not_ a support forum, and issues that aren't properly qualified as bugs will be closed.

= Write better content with Yoast SEO =
Using the snippet preview, you can see a rendering of what your post or page will look like in the search results, whether your title is too long or too short, and whether your meta description makes sense in the context of a search result. This way the plugin will help you not only increase rankings but also increase the click through rate for organic search results.

= Page Analysis =
The Yoast SEO plugins [Page Analysis](https://yoast.com/content-seo-wordpress-linkdex/) functionality checks simple things you're bound to forget. It checks, for instance, if you have images in your post and whether they have an alt tag containing the focus keyword for that post. It also checks whether your posts are long enough, whether you've written a meta description and if that meta description contains your focus keyword, if you've used any subheadings within your post, etc. etc.

The plugin also allows you to write meta titles and descriptions for all your category, tag and custom taxonomy archives, giving you the option to further optimize those pages.

Combined, this plugin makes sure that your content is the type of content search engines will love!

= Technical WordPress Search Engine Optimization =
While out of the box WordPress is pretty good for SEO, it needs some tweaks here and there. This Yoast SEO plugin guides you through some of the settings needed, for instance by reminding you to enable pretty permalinks. But it also goes beyond that, by automatically optimizing and inserting the meta tags and link elements that Google and other search engines like so much:

= Meta & Link Elements =
With the Yoast SEO plugin you can control which pages Google shows in its search results and which pages it doesn't show. By default, it will tell search engines to index all of your pages, including category and tag archives, but to only show the first pages in the search results. It's not very useful for a user to end up on the third page of your "personal" category, right?

WordPress itself only shows canonical link elements on single pages, but Yoast SEO makes it output canonical link elements everywhere. Google has recently announced they would also use `rel="next"` and `rel="prev"` link elements in the `head` section of your paginated archives. This plugin adds those automatically. See [this post](https://yoast.com/rel-next-prev-paginated-archives/) for more info.

= XML Sitemaps =
The Yoast SEO plugin has the most advanced XML Sitemaps functionality in any WordPress plugin. Once you check the box, it automatically creates XML sitemaps and notifies Google & Bing of the sitemaps' existence. These XML sitemaps include the images in your posts & pages too, so that your images may be found better in the search engines too.

These XML Sitemaps will even work on large sites, because of how they're created, using one index sitemap that links to sub-sitemaps for each 1,000 posts. They will also work with custom post types and custom taxonomies automatically, while giving you the option to remove those from the XML sitemap should you wish to.

Because of using [XSL stylesheets for these XML Sitemaps](https://yoast.com/xsl-stylesheet-xml-sitemap/), the XML sitemaps are easily readable for the human eye too, so you can spot things that shouldn't be in there.

= RSS Optimization =
Are you being outranked by scrapers? Instead of cursing at them, use them to your advantage! By automatically adding a link to your RSS feed pointing back to the original article, you're telling the search engine where they should be looking for the original. This way, the Yoast SEO plugin increases your own chance of ranking for your chosen keywords and gets rid of scrapers in one go!

= Breadcrumbs =
If your theme is compatible, and themes based on for instance Genesis or by WooThemes often are, you can use the built-in Breadcrumbs functionality. This allows you to create an easy navigation that is great for both users and search engines, and will support the search engines in understanding the structure of your site.

Making your theme compatible isn't hard either, check [these instructions](https://kb.yoast.com/kb/implement-wordpress-seo-breadcrumbs/).

= Edit your .htaccess and robots.txt file =
Using the built-in file editor, you can edit your WordPress blog's `.htaccess` and `robots.txt` file, giving you direct access to the two most powerful files, from an SEO perspective, in your WordPress install.

= Social Integration =
SEO and Social Media are heavily intertwined. That's why this plugin also comes with a Facebook OpenGraph implementation and will soon also support Google+ sharing tags.

= Multi-Site Compatible =
The Yoast SEO plugin, unlike some others, is fully Multi-Site compatible. The XML Sitemaps work fine in all setups and you even have the option, in the Network settings, to copy the settings from one blog to another, or make blogs default to the settings for a specific blog.

= Import & Export functionality =
If you have multiple blogs, setting up plugins like this one on all of them might seem like a daunting task. Except that it's not, because what you can do is simple: you set up the plugin once. You then export your settings and simply import them on all your other sites. It's that simple!

= Import functionality for other WordPress SEO plugins =
If you've used All In One SEO Pack or HeadSpace2 before using this plugin, you might want to import all your old titles and descriptions. You can do that easily using the built-in import functionality. There's also import functionality for some of the older Yoast plugins, like Robots Meta and RSS footer.

Should you have a need to import from another SEO plugin to Yoast SEO, or from a theme like Genesis or Thesis, you can use the [SEO Data Transporter](http://wordpress.org/extend/plugins/seo-data-transporter/) plugin, which will easily convert your SEO meta data from and to a whole set of plugins like Platinum SEO, SEO Ultimate, Greg's High Performance SEO, and themes like Headway, Hybrid, WooFramework, Catalyst etc.

Read [this migration guide](https://yoast.com/all-in-one-seo-pack-migration/) if you still have questions about migrating from another SEO plugin to Yoast SEO.

= Yoast SEO Plugin in your Language! =
Currently a huge translation project is underway, translating Yoast SEO in as much as 24 languages. So far, the translations for French and Dutch are complete, but we still need help on a lot of other languages, so if you're good at translating, please join us at [translate.yoast.com](http://translate.yoast.com).

= News SEO =
Be sure to also check out the premium [News SEO module](https://yoast.com/wordpress/plugins/news-seo/) if you need Google News Sitemaps. It tightly integrates with Yoast SEO to give you the combined power of News Sitemaps and full Search Engine Optimization.

= Further Reading =
For more info, check out the following articles:

* The [Yoast SEO Knowledgebase](https://kb.yoast.com/kb/category/yoast-seo/).
* [WordPress SEO - The definitive Guide by Yoast](https://yoast.com/articles/wordpress-seo/).
* Once you have great SEO, you'll need the [best WordPress Hosting](https://yoast.com/articles/wordpress-hosting/).
* The [Yoast SEO Plugin](https://yoast.com/wordpress/plugins/seo/) official homepage.
* Other [WordPress Plugins](https://yoast.com/wordpress/plugins/) by the same team.
* Follow Yoast on [Facebook](https://facebook.com/yoast) & [Twitter](http://twitter.com/yoast).

== Installation ==

=== From within WordPress ===
1. Visit 'Plugins > Add New'
1. Search for 'Yoast SEO'
1. Activate Yoast SEO from your Plugins page.
1. Go to "after activation" below.

=== Manually ===
1. Upload the `wordpress-seo` folder to the `/wp-content/plugins/` directory
1. Activate the Yoast SEO plugin through the 'Plugins' menu in WordPress
1. Go to "after activation" below.

=== After activation ===
1. You should see (a notice to start) the Yoast SEO configuration wizard.
1. Go through the configuration wizard and set up the plugin for your site.
1. You're done!

== Frequently Asked Questions ==

You'll find answers to many of your questions on [kb.yoast.com](https://kb.yoast.com/kb/category/yoast-seo/).

== Screenshots ==

1. The Yoast SEO plugin general meta box. You'll see this on edit post pages, for posts, pages and custom post types.
2. The fully configurable XML sitemap for Yoast SEO.
3. Easily import SEO data from other SEO plugins like All In One SEO pack, HeadSpace2 SEO and wpSEO.de.
4. Example of the SEO analysis functionality.
5. Example of the readability analysis functionality.
6. The advanced section of the Yoast SEO meta box.

== Changelog ==

= 5.3.1 =

Release Date: August 22nd, 2017

* Bugfixes
	* Fixes a bug where "mark as fixed" on the search console page didn't work.
	* Fixes a bug where the configuration wizard JavaScript file was too large.

= 5.3.0 =

Release Date: August 22nd, 2017

* Enhancements
	* Adds missing I18n function call to make a string translatable
	* Adds XML schema for image sitemap, props: [stodorovic](https://github.com/stodorovic)
	* Adds schema.org meta-data on every page, instead of only on the homepage
	* Adds the possibility to filter posts by readability score.
	* Exposes tinyMCEHelper as window.YoastSEO.wp._tinyMCEHelper in JavaScript
	* Exposes the ReplaceVar class in YoastReplaceVarPlugin as window.YoastReplaceVarPlugin.ReplaceVar in JavaScript

* Bugfixes
	* Adds sanitization for the Twitter Image meta field
	* Fixes use of `register_meta` for usage in WordPress 4.6 and higher
	* Initialize the providers on hook `after_theme_setup` to make sure custom providers are added properly, props: [stodorovic](https://github.com/stodorovic)
	* Changes the label of the "Bad" score to "Needs improvement" while filtering on SEO or readability scores.

= 5.2.0 =

Release Date: August 8th, 2017

* Enhancements
	* Added wpseo_pre_adjacent_rel_links filter to bypass built-in rel prev/next functionality.
	* Introduces classes to allow collecting data in the Premium plugin.
	* Renamed OnPage.org to Ryte.
	* Allow WordPress WHIP messages to be dismissed for a period of 4 weeks.
	* Adds a filter for word combinations that consist of a single one-character word.
	* Adds aria-current to the onboarding wizard active step.

* Bugfixes
	* Removes JQMIGRATE JavaScript warnings.

= 5.1.0 =

Release Date: July 25th, 2017

* Enhancements
	* Adds the post-type and taxonomy identifiers on the titles and metas settings tab.
	* Adds support for importing of Jetpack SEO data.
	* Improves the readability feature for Dutch, English, French, German, Italian and Spanish.
	* Adds a WordPress SEO Premium motivation box on Yoast SEO settings pages.
	* Adds a WordPress SEO Premium motivation on the social tabs.
	* Adds support for third party sitemaps providers to be registered and used.
	* Changes the column titles in the taxonomy list table to icons.
	* Adds a subheader on the notification dashboard to clarify problems and issues which are muted.
	* Improves avatars on the credit page, props [Mike DeHart](https://github.com/mikedehart)

* Bugfixes
	* Fixes a bug where `remove_meta_if_default` and `dont_save_meta_if_default` don't return the given input value as default.
	* Fixes a performance issue related to calculating text link counts when saving a post.
	* Fixes a typo in the readme.txt, props [Raymond Rutjes](https://github.com/rayrutjes)

= 5.0.2 =

Release Date: July 13th, 2017

* Only load babel polyfill if it hasn't been loaded by another plugin yet.
* Adds a feature toggle to disable the link counter tool & link columns.
* Fixes a compatibility issue with WordPress 4.6.
* Fixes an issue where the link columns would disappear after quick-editing a post.

= 5.0.1 =

Release Date: July 6th, 2017

* Fixes a fatal error that could occur when trying to save a post that has `<a>`-tags with invalid URLs in it.

= 5.0.0 =

Release Date: July 6th, 2017

* Bugfixes
	* Fixes a bug where images via `https` were not working, props [Jannik Zschiesche](https://github.com/apfelbox).
	* Fixes a bug where the whip notification can be shown multiple times.

* Enhancements
	* Introduces a module that counts links in the content.
	* Adds Flesch Reading for Italian.
	* Changes 'page title' to 'seo title' in the snippet preview.
 	* Changes recommended maximum sentence length for Italian from 20 to 25 words, based on more in-depth research.
 	* Implements the extracted version of the Algolia Search which is now present in `yoast-components`.
 	* Adds a banner for the structured data course.

 * Under the hood
 	* Introduces a database table to keep track of the linking structure. If the table cannot be created, a notification will be shown.
 	* When there are posts or pages to reindex, a notice will be shown.

= Earlier versions =

For the changelog of earlier versions, please refer to the separate changelog.txt file.
