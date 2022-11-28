# Ubercart Restrict Quantity

Ubercart Restrict Quantity lets you add a very basic quantity restriction to a
product in your Ubercart store. One use-case is to allow for single purchase
products or for other instances where users may purchase only up to a maximum
quantity of the product.

Due to the way products are added to the cart, customers can add multiple
variations of the same product to their carts (i.e. different attribute/option
combinations) but never more than one of any given variation.

## Installation

 - Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Usage

 - As an administrator, browse to the product page.
 - Click on the product's `Edit` tab and then its `Features` secondary task tab.
 - Choose `Restrict Quantity` from the select box and click `Add`.
 - Fill in the details of the restriction (quantity limit, lifetime option).
 - Test it out by adding the product to your cart! (Note: If you already had a
   copy of that product in your shopping cart, you should empty your cart and
   add it again. Due to the way the module works, it won't restrict quantities
   on products already in customers' shopping carts.

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/uc_restrict_qty/issues)

## Current Maintainers

 - [Laryn Kragt Bakker](https://github.com/laryn)
 - [argiepiano](https://github.com/argiepiano)
 - Collaboration and co-maintainers are welcome.

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn).
- Initial port sponsored by [CEDC.org](https://CEDC.org).
- Maintained and developed for Drupal over the years by
  [rszrama](https://www.drupal.org/u/rszrama),
  [RaulMuroc](https://www.drupal.org/u/RaulMuroc),
  [mrfelton](https://www.drupal.org/u/mrfelton), and
  [webservant316](https://www.drupal.org/u/webservant316).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
