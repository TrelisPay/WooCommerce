
# Trelis WooCommerce Ethereum Payments Plugin

## Instructions
1. Download the latest release of the Trelis Wordpress Plugin
2. Upload the zip file to Wordpress as a new plugin
3. Navigate to WooCommerce -> Settings -> Payments -> TrelisPay -> Manage
4. Copy the api webhook url
5. Connect your merchant Ethereum wallet to Trelis.com and navigate to the API dashboard
6. Create a new api key. Enter the api webhook url. Copy and paste the API key and secret into the Wordpress dashboard.
That's it! Ethereum payments are now live.

### Supported currencies
- If your store is in US dollars, Trelis Pay will automatically offer payment in USDC at a 1:1 exchange rate
- Alternately, when creating a new product you can set the price to USDC or ETH
- Other currencies are not currently supported

### Disclaimers
- The Trelis WooCommerce plugin is in alpha
- See license terms for further disclaimers of warranties
- Support information available at docs.trelis.com/support

~~~~~


=== Trelis Crypto Payments ===
Contributors: ronantrelis
Donate link: https://art.trelis.com/product/woocommerce-plugin-donation/
Tags: tag1, tag2
Requires at least: 6.1
Tested up to: 8.1
Stable tag: 4.3
Requires PHP: 7.4
License: GPL-3.0
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

Here is a short description of the plugin.  This should be no more than 150 characters.  No markup here.

== Description ==

This is the long description.  No limit, and you can use Markdown (as well as in the following sections).

For backwards compatibility, if this section is missing, the full length of the short description will be used, and
Markdown parsed.

A few notes about the sections above:

* "Contributors" is a comma separated list of wordpress.org usernames
* "Tags" is a comma separated list of tags that apply to the plugin
* "Requires at least" is the lowest version that the plugin will work on
* "Tested up to" is the highest version that you've *successfully used to test the plugin*
* Stable tag must indicate the Subversion "tag" of the latest stable version

Note that the `readme.txt` value of stable tag is the one that is the defining one for the plugin.  If the `/trunk/readme.txt` file says that the stable tag is `4.3`, then it is `/tags/4.3/readme.txt` that'll be used for displaying information about the plugin.

If you develop in trunk, you can update the trunk `readme.txt` to reflect changes in your in-development version, without having that information incorrectly disclosed about the current stable version that lacks those changes -- as long as the trunk's `readme.txt` points to the correct stable tag.

If no stable tag is provided, your users may not get the correct version of your code.

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Screenshots are stored in the /assets directory.
2. This is the second screen shot

== Changelog ==

= 1.0 =
* A change since the previous version.
* Another change.

= 0.5 =
* List versions from most recent at top to oldest at bottom.

== Upgrade Notice ==

= 1.0 =
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.

== A brief Markdown Example ==

Markdown is what the parser uses to process much of the readme file.

[markdown syntax]: https://daringfireball.net/projects/markdown/syntax

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Links require brackets and parenthesis:

Here's a link to [WordPress](https://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax]. Link titles are optional, naturally.

Blockquotes are email style:

> Asterisks for *emphasis*. Double it up  for **strong**.

And Backticks for code:

`<?php code(); ?>`