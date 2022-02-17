## Introduction

WooCommerce Redirect To Page or URL on Add To Cart - Direct Checkout or Skip Cart plugin lets you redirect the user to a page on your website or internal/external URL on add-to-cart button. You can enable this redirection for all or selected products. You can also control add-to-cart button behavior - whether it adds product to cart or not, whether it shows "product has been added to cart" message or not. You can also change the add-to-cart button label for all or selected products for both archive (e.g. shop page) and single product pages regardless of whether redirection is turned on for it or not.

### Some use cases:

1. The default WooCommerce checkout flow expects user to navigate from shop/single-product page to cart page to checkout page. This navigation results in a slow and cumbersome checkout experience for the user and often makes the user leave your site without any purchase (a.k.a. abandoned cart). For these reason, you want to provide a faster checkout experience to your users by automatically redirecting them to the checkout page after the product is added to cart.
2. You want user to fill out a form or read terms&conditions before/after the product is added to cart. You want to achieve it by redirecting the user to a purpose-built page on your website after add-to-cart button is clicked.
3. You want to use an external checkout service - may be, you own multiple stores and want to redirect the user to the other store or you are an affiliate and want to earn commission on variable/grouped products by redirecting the user to external website.

### Features

- For all or selected products
  - Enable redirection on add-to-cart button
  - Set custom label for add-to-cart button
- Redirection
  - Redirect to a page on your website
  - Redirect to any URL - an internal or external URL
  - Skip addition to cart (helpful when you redirect the user to an external URL)
  - Hide "product has been added to cart message" (helpful when you redirect the user to checkout page)
  - Works when WooCommer setting "Enable AJAX add to cart buttons on archives" is enabled.
  - Works when WooCommerce setting "Redirect to the cart page after successful addition" is enabled.
- Global and Product level settings
    - Override global settings at product level or just configure at product level

## Installation

### Minimum Requirements

- PHP 5.6 or greater is recommended
- Wordpress 5.0 or greater
- Woocommerce 4.1 or greater

### Manual installation

Manual installation method requires downloading this plugin and uploading it to your web server via your favorite FTP application. The WordPress codex contains [instructions on how to do this here](https://wordpress.org/support/article/managing-plugins/#manual-plugin-installation).

### Updating

Please use [Evneto Market WordPress](https://envato.com/market-plugin/) plugin to update the plugin. If you need help in using this plugin, please read [Update themes automatically using Envato Market plugin](https://seventhqueen.com/support/general/article/update-themes-automatically-using-envato-market-plugin).

## Configuration

Plugin provides global and product level settings.

### Global Level

- There are two ways to open it:
  1. Open "WooCommerce Settings" page in Dashboard (Dashboard -> WooCommerce -> Settings). Switch to "Products" tab and then open "Redirect on add-to-cart" sub-tab.
  2. Open "Plugins" page in Dashboard (Dashboard -> Plugins). Scroll down to reach "WooCommerce Redirect To Page or URL on Add To Cart" entry. Click "Settings" link in this entry to to open global settings.
![alt WooCommerce Redirect To Page or URL on Add To Cart - Direct Checkout or Skip Cart plugin settings - global level](images/global-settings-v1.png)

### Product Level

- Open "Product List" page in Dashboard (Dashboard -> Products).
- Open the product you want to edit from the product list.
- Scroll down to data panels and open "Redirect on add-to-cart" data panel.
![alt WooCommerce Redirect To Page or URL on Add To Cart - Direct Checkout or Skip Cart plugin settings - product level](images/product-settings-v1.png)

## Usage

- **Configure all products**
  - Open global settings as descirbed in [configuration](#global-level).
  - Enable configuration to configure all products of your store and based on your requirements:
    - Enable redirection to redirect the user to a page or URL on add-to-cart button.
    &nbsp;&nbsp;- Select a page of your website or input URL as the target of add-to-cart button.
    &nbsp;&nbsp;- Select whether to add the product to cart or not on add-to-cart button. You may like to not add the product to cart when redirecting to an external URL.
    &nbsp;&nbsp;- Hide the notice WooCommerce shows to confirm product addition to cart. You may want to hide this notice if you are redirecting the user to the checkout page for an immediate checkout.
    - Set a custom label for add-to-cart button. You can leave this input blank to use the default label that WooCommerce gives to add-to-cart button.
  - Save changes.

- **Configure individual product or override global settings for that product**
  - Open product settings as descirbed in [configuration](#product-level)
  - Same settings as at global level.
  - Save product.

**Note**, External products can not be added to cart. That's why both global and product level settings will not be applied to them.

## FAQS

- **What if settings of a Grouped product are different from the settings of its child product(s)?**
Grouped product settings will be used.

- **Does settings of a Variable product apply to all of its variation?**
Yes.

## Changelog

**2022-02-15 - Version 1.0.0**
  - Initial Release
