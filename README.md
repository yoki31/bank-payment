
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/bank-payment&target_branch=14.0)
[![Pre-commit Status](https://github.com/OCA/bank-payment/actions/workflows/pre-commit.yml/badge.svg?branch=14.0)](https://github.com/OCA/bank-payment/actions/workflows/pre-commit.yml?query=branch%3A14.0)
[![Build Status](https://github.com/OCA/bank-payment/actions/workflows/test.yml/badge.svg?branch=14.0)](https://github.com/OCA/bank-payment/actions/workflows/test.yml?query=branch%3A14.0)
[![codecov](https://codecov.io/gh/OCA/bank-payment/branch/14.0/graph/badge.svg)](https://codecov.io/gh/OCA/bank-payment)
[![Translation Status](https://translation.odoo-community.org/widgets/bank-payment-14-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/bank-payment-14-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# OCA banking payment addons for Odoo

This project focus on payment interface

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_banking_mandate](account_banking_mandate/) | 14.0.2.1.0 |  | Banking mandates
[account_banking_mandate_contact](account_banking_mandate_contact/) | 14.0.1.0.0 |  | Assign specific banking mandates in contact level
[account_banking_mandate_sale](account_banking_mandate_sale/) | 14.0.1.0.0 |  | Adds mandates on sale orders
[account_banking_pain_base](account_banking_pain_base/) | 14.0.2.1.1 |  | Base module for PAIN file generation
[account_banking_sepa_credit_transfer](account_banking_sepa_credit_transfer/) | 14.0.2.0.2 |  | Create SEPA XML files for Credit Transfers
[account_banking_sepa_direct_debit](account_banking_sepa_direct_debit/) | 14.0.2.1.1 |  | Create SEPA files for Direct Debit
[account_invoice_select_for_payment](account_invoice_select_for_payment/) | 14.0.1.1.0 |  | Account Invoice Select for Payment
[account_payment_mode](account_payment_mode/) | 14.0.1.1.0 |  | Account Payment Mode
[account_payment_mode_default_account](account_payment_mode_default_account/) | 14.0.1.0.0 |  | Set Receivable or Payable account according to payment mode
[account_payment_order](account_payment_order/) | 14.0.2.5.6 |  | Account Payment Order
[account_payment_order_grouped_output](account_payment_order_grouped_output/) | 14.0.1.0.1 |  | Account Payment Order - Generate grouped moves
[account_payment_order_lock_draft](account_payment_order_lock_draft/) | 14.0.1.0.0 | [![marcelsavegnago](https://github.com/marcelsavegnago.png?size=30px)](https://github.com/marcelsavegnago) [![kaynnan](https://github.com/kaynnan.png?size=30px)](https://github.com/kaynnan) | Account Payment Order Lock Draft
[account_payment_order_notification](account_payment_order_notification/) | 14.0.1.6.0 | [![victoralmau](https://github.com/victoralmau.png?size=30px)](https://github.com/victoralmau) | Account Payment Order Notification
[account_payment_order_return](account_payment_order_return/) | 14.0.1.0.2 |  | Account Payment Order Return
[account_payment_order_sequence_payment_mode](account_payment_order_sequence_payment_mode/) | 14.0.1.0.0 |  | Account Payment Order Sequence Payment Mode
[account_payment_order_tier_validation](account_payment_order_tier_validation/) | 14.0.1.0.0 | [![marcelsavegnago](https://github.com/marcelsavegnago.png?size=30px)](https://github.com/marcelsavegnago) | Extends the functionality of Payment Orders to support a tier validation process.
[account_payment_order_vendor_email](account_payment_order_vendor_email/) | 14.0.2.0.0 |  | Account Payment Order Email
[account_payment_partner](account_payment_partner/) | 14.0.1.7.2 |  | Adds payment mode on partners and invoices
[account_payment_purchase](account_payment_purchase/) | 14.0.1.0.5 |  | Adds Bank Account and Payment Mode on Purchase Orders
[account_payment_purchase_stock](account_payment_purchase_stock/) | 14.0.1.0.1 |  | Integrate Account Payment Purchase with Stock
[account_payment_sale](account_payment_sale/) | 14.0.1.1.0 |  | Adds payment mode on sale orders

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
