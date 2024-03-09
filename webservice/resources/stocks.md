---
title: Stocks
---

# Resources for Stocks

### Stock

|           Name           |    Format     | Required | Writable | Not filterable |     Description      |
| :----------------------- | :------------ | :------: | :------: | :------------- | :------------------- |
| **ean13**                | isEan13       | ❌        | ✔️       |                |                      |
| **id_product_attribute** | isUnsignedId  | ✔️       | ✔️       |                | Product attribute ID |
| **id_product**           | isUnsignedId  | ✔️       | ✔️       |                | Product ID           |
| **id_warehouse**         | isUnsignedId  | ✔️       | ✔️       |                | Warehouse ID         |
| **isbn**                 | isIsbn        | ❌        | ✔️       |                |                      |
| **mpn**                  | isMpn         | ❌        | ✔️       |                |                      |
| **physical_quantity**    | isUnsignedInt | ✔️       | ✔️       |                |                      |
| **price_te**             | isPrice       | ✔️       | ✔️       |                |                      |
| **real_quantity**        |               | ❌        | ❌        | true           |                      |
| **reference**            | isReference   | ❌        | ✔️       |                |                      |
| **upc**                  | isUpc         | ❌        | ✔️       |                |                      |
| **usable_quantity**      | isInt         | ✔️       | ✔️       |                |                      |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <stock>
    <ean13><![CDATA[]]></ean13>
    <id_product_attribute><![CDATA[]]></id_product_attribute>
    <id_product><![CDATA[]]></id_product>
    <id_warehouse><![CDATA[]]></id_warehouse>
    <id><![CDATA[]]></id>
    <isbn><![CDATA[]]></isbn>
    <mpn><![CDATA[]]></mpn>
    <physical_quantity><![CDATA[]]></physical_quantity>
    <price_te><![CDATA[]]></price_te>
    <reference><![CDATA[]]></reference>
    <upc><![CDATA[]]></upc>
    <usable_quantity><![CDATA[]]></usable_quantity>
  </stock>
</prestashop>
```

