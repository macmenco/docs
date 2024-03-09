---
title: Order slip
---

# Resources for Order slip

### Order_slip

|            Name             |    Format    | Required | Description |
| :-------------------------- | :----------- | :------: | :---------- |
| **amount**                  | isFloat      | ❌        |             |
| **associations**            |              | ❌        |             |
| **conversion_rate**         | isFloat      | ✔️       |             |
| **date_add**                | isDate       | ❌        |             |
| **date_upd**                | isDate       | ❌        |             |
| **id_customer**             | isUnsignedId | ✔️       | Customer ID |
| **id_order**                | isUnsignedId | ✔️       | Order ID    |
| **order_slip_type**         | isInt        | ❌        |             |
| **partial**                 |              | ❌        |             |
| **shipping_cost_amount**    | isFloat      | ❌        |             |
| **shipping_cost**           |              | ❌        |             |
| **total_products_tax_excl** | isFloat      | ✔️       |             |
| **total_products_tax_incl** | isFloat      | ✔️       |             |
| **total_shipping_tax_excl** | isFloat      | ✔️       |             |
| **total_shipping_tax_incl** | isFloat      | ✔️       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_slip>
    <amount><![CDATA[]]></amount>
    <conversion_rate><![CDATA[]]></conversion_rate>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <id_customer><![CDATA[]]></id_customer>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
    <order_slip_type><![CDATA[]]></order_slip_type>
    <partial><![CDATA[]]></partial>
    <shipping_cost_amount><![CDATA[]]></shipping_cost_amount>
    <shipping_cost><![CDATA[]]></shipping_cost>
    <total_products_tax_excl><![CDATA[]]></total_products_tax_excl>
    <total_products_tax_incl><![CDATA[]]></total_products_tax_incl>
    <total_shipping_tax_excl><![CDATA[]]></total_shipping_tax_excl>
    <total_shipping_tax_incl><![CDATA[]]></total_shipping_tax_incl>
    <associations>
      <order_slip_details>
        <order_slip_detail>
          <id><![CDATA[]]></id>
          <id_order_detail><![CDATA[]]></id_order_detail>
          <product_quantity><![CDATA[]]></product_quantity>
          <amount_tax_excl><![CDATA[]]></amount_tax_excl>
          <amount_tax_incl><![CDATA[]]></amount_tax_incl>
        </order_slip_detail>
      </order_slip_details>
    </associations>
  </order_slip>
</prestashop>
```

