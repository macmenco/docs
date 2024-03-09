---
title: Order invoices
---

# Resources for Order invoices

### Order_invoice

|                Name                 |    Format    | Required | Max size | Description |
| :---------------------------------- | :----------- | :------: | -------: | :---------- |
| **date_add**                        | isDate       | ❌        |          |             |
| **delivery_date**                   | isDateFormat | ❌        |          |             |
| **delivery_number**                 | isUnsignedId | ❌        |          |             |
| **id_order**                        | isUnsignedId | ✔️       |          | Order ID    |
| **note**                            | isCleanHtml  | ❌        | 65000    |             |
| **number**                          | isUnsignedId | ✔️       |          |             |
| **shipping_tax_computation_method** |              | ❌        |          |             |
| **shop_address**                    | isCleanHtml  | ❌        | 1000     |             |
| **total_discount_tax_excl**         |              | ❌        |          |             |
| **total_discount_tax_incl**         |              | ❌        |          |             |
| **total_paid_tax_excl**             |              | ❌        |          |             |
| **total_paid_tax_incl**             |              | ❌        |          |             |
| **total_products_wt**               |              | ❌        |          |             |
| **total_products**                  |              | ❌        |          |             |
| **total_shipping_tax_excl**         |              | ❌        |          |             |
| **total_shipping_tax_incl**         |              | ❌        |          |             |
| **total_wrapping_tax_excl**         |              | ❌        |          |             |
| **total_wrapping_tax_incl**         |              | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_invoice>
    <date_add><![CDATA[]]></date_add>
    <delivery_date><![CDATA[]]></delivery_date>
    <delivery_number><![CDATA[]]></delivery_number>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
    <note><![CDATA[]]></note>
    <number><![CDATA[]]></number>
    <shipping_tax_computation_method><![CDATA[]]></shipping_tax_computation_method>
    <shop_address><![CDATA[]]></shop_address>
    <total_discount_tax_excl><![CDATA[]]></total_discount_tax_excl>
    <total_discount_tax_incl><![CDATA[]]></total_discount_tax_incl>
    <total_paid_tax_excl><![CDATA[]]></total_paid_tax_excl>
    <total_paid_tax_incl><![CDATA[]]></total_paid_tax_incl>
    <total_products_wt><![CDATA[]]></total_products_wt>
    <total_products><![CDATA[]]></total_products>
    <total_shipping_tax_excl><![CDATA[]]></total_shipping_tax_excl>
    <total_shipping_tax_incl><![CDATA[]]></total_shipping_tax_incl>
    <total_wrapping_tax_excl><![CDATA[]]></total_wrapping_tax_excl>
    <total_wrapping_tax_incl><![CDATA[]]></total_wrapping_tax_incl>
  </order_invoice>
</prestashop>
```

