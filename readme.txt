=== SQID Payments Gateway for Woocommerce ===
Contributors: SQID Payments
Donate link:
Tags:  australia,  cart, checkout, commerce, credit card, e-commerce, ecommerce, sqidpayments, payment gateway, woocommerce, westpac
Requires at least: 3.8.0
Tested up to: 4.1.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

The SQID Payments Gateway for Woocommerce allows Australian Merchants to accept payments on your Woocommerce store for Visa Card and Mastercard.

== Description ==

[SQID Payments](https://sqidpayments.com.au) offers one of the fastest and easiest way to accept payments online in Australia. SQID can create the merchant account for you and __settles funds to any Australian Bank__ and you can __use your existing business account__ because SQID Payments is an aggregator for Westpac Bank.

The innovative payment solution enables online businesses to quickly integrate payments into their websites. The developer-friendly REST API is flexible and well documented. A SQID Merchant Account also includes access to a __Virtual POS terminal for mobile and desktop based payments__. Access to SMS and email based marketing tools that allow you to send direct payment links for deals, offers and bill payments are just part of the normal merchant account.  All major card brands like MasterCard, VISA, American Express, are supported. 

[Merchant pricing](https://sqidpayments.com.au/pricing/) includes plans with no monthly fees. [Apply to become a merchant here](https://sqidpayments.com.au/merchant_application/) and typical approval is in about 24 hours

Note: We really think you should have an SSL Certificate to be installed on your site to ensure your customer’s credit card details are safe.

* PHP 5.3 or higher
* WordPress 3.8.x or higher

= Supported Shops: =

* WooCommerce (2.3.x) 

= Supported subscriptions and recurring payments: =

* WooCommerce Subscriptions (1.5.x)	

= Team =

* Officially supported by [SQID Payments](https://sqidpayments.com.au)
* Developed and maintained by [SQID Payments](https://sqidpayments.com.au)

== Installation ==

= Minimum Requirements =

* WooCommerce 2.1.0 or later

= Automatic installation =
Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't need to leave your web browser. To do an automatic install of WooCommerce, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type “SQID Payments Woocommerce Gateway” and click Search Plugins. Once you've found the plugin you can install it by simply clicking “Install Now”.

__Create a page called Response and onto that page add the shortcode [response]__

= Manual installation =

Manual installation method involves downloading our the plugin and uploading it to your webserver via your favourite FTP application. The WordPress codex contains [instructions on how to do this here](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).
__Add a page called Response and onto that page add the shortcode [response]__

= What next” =

* Activate the plugin through the 'Plugins' menu in WordPress.
* Register for a merchant account on [SQID Payments](https://sqidpayments.com.au)
* Go to __Woocommerce > Settings>Checkout__ and at the bottom of the page drag SQID to the top of the gateways list and check __default__	
* Insert Api Keys and credentials and then enable test mode in plugin settings/checkout page that were sent to you.
* Run some test transactions and log into your [Merchant Portal](https://merchant.sqidpay.com) or [Virtual POS](https://virtualpos.sqidpay.com) to see that they are all correct.
* If you are happy how the plugin works, then enable your live account by deselecting the __Enable test mode__ and your cart is __live instantly__.
* We suggest you run a live transaction and check your merchant portal or Virtual POS (you can refund it in the Virtual POS screen when you are done).

You'll also need to force SSL on checkout in the WooCommerce settings and of course have an SSL certificate to ensure your customer’s credit card details are safe.

== Frequently Asked Questions ==

= Who’s is the acquiring bank? =

SQID Payments is a merchant aggregator with Westpac Bank in Australia.

= Do I need and SSL certificate? =

Yes you need an SSL Certificate to be installed on your site to ensure your customer’s credit card details are safe.

= Is this plugin for free? =

This plugin is for free and licensed to GPL.
It's open source following the GPL policy.

= Is there also an API available? =

Yes, __there is an API__ and details of the latest release are here for [Developers](https://sqidpayments.com.au/developers/)

= Are there any fees for payments? =

Merchants must create an account at [SQID Payments](https://sqidpayments.com.au) to use the payment service.
The TEST mode is for free, but there are "per payment" fees in LIVE mode, see [SQID Pricing](https://sqidpayments.com.au/pricing/)

= Do customers need to create an account for payment? =

No. SQID allows payments without annoying your customers creating an account.
They'll just fill out the payment fields on your checkout-page - that's all.

= Does this plugin redirects the users to SQID for payment? =

No. SQID allows payment directly through your website without any extra redirects etc.

= Which Credit Cards are supported? =

In Australia we support VISA, MasterCard and American Express.

= I get a 404 error when I submit test card data? =

Be sure that you have a created a page for us to send the response from the gateway.  Create a page called Response and put the shortcode [response] onto that page.

== Screenshots ==

1. WooCommerce checkout page settings page

2. SQID Payments Gateway Checkout Setting Page

3. Create a transactions results page called Response and insert the [response] shortcode.


== Changelog ==

= 1.0.2 =
* Various minor tweaks and speed improvements
* Minor bug fixes and revised receipt format

= 1.0.1 =
* Minor edits and improvements
* Added tokenisation for WooCommerce Subscriptions 1.5.x

= 1.0 =
* Initial release

== Upgrade Notice ==

= 0.9 =
* Beta release
