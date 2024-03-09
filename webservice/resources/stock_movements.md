---
title: Stock movements
---

# Resources for Stock movements

### Stock_mvt

|           Name           |    Format     | Required |     Description      |
| :----------------------- | :------------ | :------: | :------------------- |
| **current_wa**           | isPrice       | ❌        |                      |
| **date_add**             | isDate        | ✔️       |                      |
| **ean13**                |               | ❌        |                      |
| **id_currency**          |               | ❌        | Currency ID          |
| **id_employee**          | isUnsignedId  | ✔️       | Employee ID          |
| **id_order**             | isUnsignedId  | ❌        | Order ID             |
| **id_product_attribute** |               | ❌        | Product attribute ID |
| **id_product**           |               | ❌        | Product ID           |
| **id_stock_mvt_reason**  | isUnsignedId  | ✔️       |                      |
| **id_stock**             | isUnsignedId  | ✔️       |                      |
| **id_supply_order**      | isUnsignedId  | ❌        |                      |
| **id_warehouse**         |               | ❌        | Warehouse ID         |
| **last_wa**              | isPrice       | ❌        |                      |
| **management_type**      |               | ❌        |                      |
| **mpn**                  |               | ❌        |                      |
| **physical_quantity**    | isUnsignedInt | ✔️       |                      |
| **price_te**             | isPrice       | ✔️       |                      |
| **product_name**         |               | ❌        |                      |
| **reference**            |               | ❌        |                      |
| **sign**                 | isInt         | ✔️       |                      |
| **upc**                  |               | ❌        |                      |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <stock_mvt>
    <current_wa><![CDATA[]]></current_wa>
    <date_add><![CDATA[]]></date_add>
    <ean13><![CDATA[]]></ean13>
    <id_currency><![CDATA[]]></id_currency>
    <id_employee><![CDATA[]]></id_employee>
    <id_order><![CDATA[]]></id_order>
    <id_product_attribute><![CDATA[]]></id_product_attribute>
    <id_product><![CDATA[]]></id_product>
    <id_stock_mvt_reason><![CDATA[]]></id_stock_mvt_reason>
    <id_stock><![CDATA[]]></id_stock>
    <id_supply_order><![CDATA[]]></id_supply_order>
    <id_warehouse><![CDATA[]]></id_warehouse>
    <id><![CDATA[]]></id>
    <last_wa><![CDATA[]]></last_wa>
    <management_type><![CDATA[]]></management_type>
    <mpn><![CDATA[]]></mpn>
    <physical_quantity><![CDATA[]]></physical_quantity>
    <price_te><![CDATA[]]></price_te>
    <product_name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </product_name>
    <reference><![CDATA[]]></reference>
    <sign><![CDATA[]]></sign>
    <upc><![CDATA[]]></upc>
  </stock_mvt>
</prestashop>
```

