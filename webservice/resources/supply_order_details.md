---
title: Supply order details
---

# Resources for Supply order details

### Supply_order_detail

|               Name                |    Format     | Required |     Description      |
| :-------------------------------- | :------------ | :------: | :------------------- |
| **discount_rate**                 | isFloat       | ✔️       |                      |
| **discount_value_te**             | isPrice       | ✔️       |                      |
| **ean13**                         | isEan13       | ❌        |                      |
| **exchange_rate**                 | isFloat       | ✔️       |                      |
| **id_product_attribute**          | isUnsignedId  | ✔️       | Product attribute ID |
| **id_product**                    | isUnsignedId  | ✔️       | Product ID           |
| **id_supply_order**               | isUnsignedId  | ✔️       |                      |
| **isbn**                          | isIsbn        | ❌        |                      |
| **mpn**                           | isMpn         | ❌        |                      |
| **name**                          | isGenericName | ✔️       |                      |
| **price_te**                      | isPrice       | ✔️       |                      |
| **price_ti**                      | isPrice       | ✔️       |                      |
| **price_with_discount_te**        | isPrice       | ✔️       |                      |
| **price_with_order_discount_te**  | isPrice       | ✔️       |                      |
| **quantity_expected**             | isUnsignedInt | ✔️       |                      |
| **quantity_received**             | isUnsignedInt | ❌        |                      |
| **reference**                     | isReference   | ❌        |                      |
| **supplier_reference**            | isReference   | ❌        |                      |
| **tax_rate**                      | isFloat       | ✔️       |                      |
| **tax_value_with_order_discount** | isFloat       | ✔️       |                      |
| **tax_value**                     | isPrice       | ✔️       |                      |
| **unit_price_te**                 | isPrice       | ✔️       |                      |
| **upc**                           | isUpc         | ❌        |                      |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <supply_order_detail>
    <discount_rate><![CDATA[]]></discount_rate>
    <discount_value_te><![CDATA[]]></discount_value_te>
    <ean13><![CDATA[]]></ean13>
    <exchange_rate><![CDATA[]]></exchange_rate>
    <id_product_attribute><![CDATA[]]></id_product_attribute>
    <id_product><![CDATA[]]></id_product>
    <id_supply_order><![CDATA[]]></id_supply_order>
    <id><![CDATA[]]></id>
    <isbn><![CDATA[]]></isbn>
    <mpn><![CDATA[]]></mpn>
    <name><![CDATA[]]></name>
    <price_te><![CDATA[]]></price_te>
    <price_ti><![CDATA[]]></price_ti>
    <price_with_discount_te><![CDATA[]]></price_with_discount_te>
    <price_with_order_discount_te><![CDATA[]]></price_with_order_discount_te>
    <quantity_expected><![CDATA[]]></quantity_expected>
    <quantity_received><![CDATA[]]></quantity_received>
    <reference><![CDATA[]]></reference>
    <supplier_reference><![CDATA[]]></supplier_reference>
    <tax_rate><![CDATA[]]></tax_rate>
    <tax_value_with_order_discount><![CDATA[]]></tax_value_with_order_discount>
    <tax_value><![CDATA[]]></tax_value>
    <unit_price_te><![CDATA[]]></unit_price_te>
    <upc><![CDATA[]]></upc>
  </supply_order_detail>
</prestashop>
```

