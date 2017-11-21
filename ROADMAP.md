Current goal is to support as the whole [reference test suite][1].

[1]: https://github.com/SparrowDevelopment/sparrow-api-curl/blob/master/api


## [sale](tests/test_sale.py)

- [x] simple_sale
- [x] simple_sale_decline
- [x] simple_sale_invalid_card
- [x] simple_sale_avs_mismatch
- [x] advanced_sale
- [ ] passenger_sale

## [auth](tests/test_auth.py)

- [x] simple_authorization
- [x] advanced_auth
- [x] simple_capture
- [ ] simple_offline_capture

## [refund](tests/test_refund.py)

- [x] simple_refund
- [x] advanced_refund
- [x] simple_void
- [x] advanced_void
- [ ] chargeback_entry

## [ach](tests/test_ach.py)

- [x] simple_ach
- [x] simple_ach_refund
- [x] simple_ach_credit
- [x] advanced_ach

## [star](tests/test_star.py)

- [x] simple_star_card
- [x] advanced_star_card

## ewallet

- [ ] e_wallet_simple_credit
- [ ] fiserv_simple_sale

## [customers](tests/test_customers.py)

- [x] adding_a_customer
- [x] add_customer_credit_card_simple
- [x] add_customer_ach_simple
- [x] add_customer_e_wallet_simple
- [ ] update_payment_type
- [x] delete_payment_type
- [x] delete_data_vault_customer

## [invoices](tests/test_invoices.py)

- [x] creating_an_invoice
- [x] creating_active_invoice
- [x] update_invoice
- [x] retrieve_invoice
- [x] cancel_invoice
- [x] cancel_invoice_by_customer
- [x] paying_an_invoice_with_a_credit_card
- [x] paying_an_invoice_with_a_bank_account

## plans

- [ ] creating_a_payment_plan
- [ ] updating_a_payment_plan
- [ ] deleting_a_plan
- [ ] assigning_a_payment_plan_to_a_customer
- [ ] update_payment_plan_assignment
- [ ] cancel_plan_assignment

---

- [ ] advanced_fiserv_sale
- [ ] retrieve_card_balance
- [ ] decrypting_custom_fields
- [ ] account_verification