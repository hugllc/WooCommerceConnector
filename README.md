## ERPNext WooCommerce Connector

WooCommerce connector for ERPNext

This connector allows the synchronisation of items, stock, customers, addresses, sales orders, sales invoices and payment entries to a WooCommerce instance.

It requires the Frappe Framework and [ERPNext](https://erpnext.org).

#### License

AGPL

#### Installation

On the ERPNext server, run

    $ cd /home/frappe/frappe-bench
	$ bench get-app https://github.com/libracore/woocommerceconnector.git
	$ bench install-app woocommerceconnector
## Notes

This is a copy of https://github.com/libracore/WooCommerceConnector.  It is not a 'fork' in github because we are customizing this for our needs, with changes
will never be a pull request.  Being a copy instead of a fork makes a cleaner break from the original.  We want to acknowledge all the work done by the 
libracore/woocommerceconnector project.  Thank you!
