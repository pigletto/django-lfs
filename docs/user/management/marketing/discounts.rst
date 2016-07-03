.. index:: Discount

.. _discounts_management:

=========
Discounts
=========

This section describes the management interface for discounts.

Site Actions
============

Add Discount
    Adds a new discount to the shop.

Delete Discount
    Deletes the currently display discount.

Data
====

Name
    The name of the discount, which is displayed as order item to the
    customer.

Value
    The value of the discount.

Type
    Absolute or percentaged. The type of the above entered value. If percentaged
    is selected the discount is based on the total price of all products within
    the cart.

Tax
    The included tax of the discount (optional)

SKU:
    The unique id of the discount.

Sums up:
     Determine if discount can be summed up with other discounts/voucher.
     To calculate final discount on order:
         * value of discounts/voucher able to sum up is calculated
         * value of highest discount/voucher that cannot be summed up is calculated
         * higher of two above values is used

Criteria
========

Within this tab you can assign criteria to the discount. The discount is only
given if a customer meets all criteria.

See Also
========

* :doc:`/user/concepts/criteria`
