=== Leumi Pay App for WooCommerce ===
Contributors: zorem
Donate link:https://www.zorem.com 
Tags: WooCommerce
Requires at least: 4.0
Requires PHP: 7.0
Tested up to: 5.4
Stable tag: 5.2
License: GPLv2 
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WooCommerce Payment Gateway Plugin for Pay app payment method, an Israeli money transfer service/app. 

== Description ==

Pay App Payment method, is a gateway that require no payment be made online, orders using Pay App Payment are set to Pay App Pending Payment status until payment clears outside of WooCommerce.
You, as the store owner, should confirm that payments have cleared with Pay app before processing orders in WooCommerce. It’s important to verify that you are paid before shipping an order and marking it as Processing or Complete.

== Features ==

* Receive offline Payments using Pay App Payment method
* Orders paid using Pay App Payment will get order status of “Pending Pay App” 
* Pay App Payment instructions will display on “order received” page and in order email to customer.
* Pay App Payment message will display in Admin new order email
* Set Custom email subject and Custom email heading for Pay app payment emails

== Installation ==

1. Upload the folder 'woo-pay-app-payment-gateway` to the `/wp-content/plugins/` folder
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enable Pay App Payment Gateway from WooCommerce payment settings

== Setup and Configuration ==

* Go to: WooCommerce > Settings > Payments.
* Use the toggle under Enable to select Pay App Payment.
* Select Set Up. You are taken to the Pay App Payment settings.
* Configure your settings:
Enable/Disable – Enable to use. Disable to turn off.
Title – This controls the title for the payment method the customer sees during checkout.
Description – Payment method description that the customer will see on your checkout.
Receiver Phone Number – Payments are sent to this number.
Instructions – Explain how to make payment using Pay App Payment.
Custom email subject for pay app payment orders.
Custom email heading  for pay app payment orders.


== Changelog ==

= 1.0 =
* Initial version.