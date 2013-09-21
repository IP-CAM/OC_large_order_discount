Large Order Discount
=====================================================

This extensoin adds discount based on the cart total.
Multiple thresholds are supported.

Tested for opencart 1.5.4.1.

Comments are welcome!

=====================================================
[+] Installation
=====================================================
Copy the admin and catalog directories to your store. There should be no overwritten files.
That's all!

=====================================================
[+] Setup
=====================================================
1) Add access rights: Select System - > Users -> Users groups. 
Choose Top Administrators -> Edit. 
Add access and modify permissions for total/large_order_discount

2) Go to Extension -> Order totals.
Install and configure "Large Order Discount" module.
The discount can be configured as a certain amount or as a percent of the subtotals.
One or several (up to 10) thresholds of the subtotals can be configured.

The highest matching threshold is used to identify the discount.
The configured thresholds are compared against the subtotals in the cart depending on the totals sort order.
For example, if you have the following configuration of totals order:
Shipping  - 10
Large Order Discount - 20
Taxes - 30
Then the large order discount will take for comparison subtotals as "products totals" + "shipping", but not the taxes.

=====================================================
[+] Usage
=====================================================
Add a large order into the cart and check that all discounts are shown.
Make sure, that your clients will get a discount for a large order.
Place a banner somewhere on front or add an information article about the wholesale.

=====================================================
[+] Language
=====================================================
English and russian are already in place.
To add another language: 
1) copy admin\language\english
to
admin\language\[other language]
Then modify 
admin\language\[other language]\total\large_order_discount.php

2) copy catalog\language\english
to
catalog\language\[other language]
Then modify 
catalog\language\[other language]\total\large_order_discount.php

=====================================================
[+] Need Help?
=====================================================
Please get in touch with me in comment

=====================================================
[+] ChangeLog
=====================================================
Current version: 1.0.0

1.0.0
-initial release

