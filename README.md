product_extended_report_order_lines
===================================

Adds extra functionality to report order lines (ie. printed/saved). This will be designed to work in conjunction with other modules using t-if statements. This module will work as a standalone module so as not to introduce unecessary dependencies if not needed.

* Modifies Documents:
  * Sales
    * Quotation
    * Sale Order
    * Invoice
  * Purchasing
    * Request For Quotation
    * Purchase Order
    * Incoming Products
  * Warehouse
    * Stock Moves
  

TODO (master):
===============
* Add image to quotation/sale order lines
* Add support for github.com/oca/product-attribute/tree/8.0/__unported__/product_customer_code to allow for the display of the customer's product code/SKU on report order lines if the module is installed.
* Add support for order line comments
  * For customer's self-service order line comments in shopping cart, portal, quotation builder, etc.
  * For salesperson to add when preparing/editing a document
* Default alerts to be allow to be added to order lines
