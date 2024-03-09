---
title: Stock availables
---

# Resources for Stock availables

### Stock_available

|           Name           |    Format    | Required | Max size |     Description      |
| :----------------------- | :----------- | :------: | -------: | :------------------- |
| **depends_on_stock**     | isBool       | ✔️       |          |                      |
| **id_product_attribute** | isUnsignedId | ✔️       |          | Product attribute ID |
| **id_product**           | isUnsignedId | ✔️       |          | Product ID           |
| **id_shop_group**        | isUnsignedId | ❌        |          | Shop group ID        |
| **id_shop**              | isUnsignedId | ❌        |          | Shop ID              |
| **location**             | isString     | ❌        | 255      |                      |
| **out_of_stock**         | isInt        | ✔️       |          |                      |
| **quantity**             | isInt        | ✔️       | 10       |                      |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <stock_available>
    <depends_on_stock><![CDATA[]]></depends_on_stock>
    <id_product_attribute><![CDATA[]]></id_product_attribute>
    <id_product><![CDATA[]]></id_product>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <location><![CDATA[]]></location>
    <out_of_stock><![CDATA[]]></out_of_stock>
    <quantity><![CDATA[]]></quantity>
  </stock_available>
</prestashop>
```

