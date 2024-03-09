---
title: Order carriers
---

# Resources for Order carriers

### Order_carrier

|            Name            |      Format      | Required |   Description    |
| :------------------------- | :--------------- | :------: | :--------------- |
| **date_add**               | isDate           | ❌        |                  |
| **id_carrier**             | isUnsignedId     | ✔️       | Carrier ID       |
| **id_order_invoice**       | isUnsignedId     | ❌        | Order invoice ID |
| **id_order**               | isUnsignedId     | ✔️       | Order ID         |
| **shipping_cost_tax_excl** | isFloat          | ❌        |                  |
| **shipping_cost_tax_incl** | isFloat          | ❌        |                  |
| **tracking_number**        | isTrackingNumber | ❌        |                  |
| **weight**                 | isFloat          | ❌        |                  |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_carrier>
    <date_add><![CDATA[]]></date_add>
    <id_carrier><![CDATA[]]></id_carrier>
    <id_order_invoice><![CDATA[]]></id_order_invoice>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
    <shipping_cost_tax_excl><![CDATA[]]></shipping_cost_tax_excl>
    <shipping_cost_tax_incl><![CDATA[]]></shipping_cost_tax_incl>
    <tracking_number><![CDATA[]]></tracking_number>
    <weight><![CDATA[]]></weight>
  </order_carrier>
</prestashop>
```

