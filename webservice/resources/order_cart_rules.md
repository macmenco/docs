---
title: Order cart rules
---

# Resources for Order cart rules

### Order_cart_rule

|         Name         |    Format    | Required |   Description    |
| :------------------- | :----------- | :------: | :--------------- |
| **deleted**          | isBool       | ❌        |                  |
| **free_shipping**    | isBool       | ❌        |                  |
| **id_cart_rule**     | isUnsignedId | ✔️       |                  |
| **id_order_invoice** | isUnsignedId | ❌        | Order invoice ID |
| **id_order**         | isUnsignedId | ✔️       | Order ID         |
| **name**             | isCleanHtml  | ✔️       |                  |
| **value_tax_excl**   | isFloat      | ✔️       |                  |
| **value**            | isFloat      | ✔️       |                  |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_cart_rule>
    <deleted><![CDATA[]]></deleted>
    <free_shipping><![CDATA[]]></free_shipping>
    <id_cart_rule><![CDATA[]]></id_cart_rule>
    <id_order_invoice><![CDATA[]]></id_order_invoice>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <value_tax_excl><![CDATA[]]></value_tax_excl>
    <value><![CDATA[]]></value>
  </order_cart_rule>
</prestashop>
```

