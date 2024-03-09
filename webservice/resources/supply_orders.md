---
title: Supply orders
---

# Resources for Supply orders

### Supply_order

|            Name            |    Format     | Required | Description  |
| :------------------------- | :------------ | :------: | :----------- |
| **associations**           |               | ❌        |              |
| **date_add**               | isDate        | ❌        |              |
| **date_delivery_expected** | isDate        | ✔️       |              |
| **date_upd**               | isDate        | ❌        |              |
| **discount_rate**          | isFloat       | ❌        |              |
| **discount_value_te**      | isPrice       | ❌        |              |
| **id_currency**            | isUnsignedId  | ✔️       | Currency ID  |
| **id_lang**                | isUnsignedId  | ✔️       | Lang ID      |
| **id_supplier**            | isUnsignedId  | ✔️       | Supplier ID  |
| **id_supply_order_state**  | isUnsignedId  | ✔️       |              |
| **id_warehouse**           | isUnsignedId  | ✔️       | Warehouse ID |
| **is_template**            | isBool        | ❌        |              |
| **reference**              | isGenericName | ✔️       |              |
| **supplier_name**          | isCatalogName | ❌        |              |
| **total_tax**              | isPrice       | ❌        |              |
| **total_te**               | isPrice       | ❌        |              |
| **total_ti**               | isPrice       | ❌        |              |
| **total_with_discount_te** | isPrice       | ❌        |              |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <supply_order>
    <date_add><![CDATA[]]></date_add>
    <date_delivery_expected><![CDATA[]]></date_delivery_expected>
    <date_upd><![CDATA[]]></date_upd>
    <discount_rate><![CDATA[]]></discount_rate>
    <discount_value_te><![CDATA[]]></discount_value_te>
    <id_currency><![CDATA[]]></id_currency>
    <id_lang><![CDATA[]]></id_lang>
    <id_supplier><![CDATA[]]></id_supplier>
    <id_supply_order_state><![CDATA[]]></id_supply_order_state>
    <id_warehouse><![CDATA[]]></id_warehouse>
    <id><![CDATA[]]></id>
    <is_template><![CDATA[]]></is_template>
    <reference><![CDATA[]]></reference>
    <supplier_name><![CDATA[]]></supplier_name>
    <total_tax><![CDATA[]]></total_tax>
    <total_te><![CDATA[]]></total_te>
    <total_ti><![CDATA[]]></total_ti>
    <total_with_discount_te><![CDATA[]]></total_with_discount_te>
    <associations>
      <supply_order_details>
        <supply_order_detail>
          <id_product_attribute><![CDATA[]]></id_product_attribute>
          <id_product><![CDATA[]]></id_product>
          <id><![CDATA[]]></id>
          <product_name><![CDATA[]]></product_name>
          <supplier_reference><![CDATA[]]></supplier_reference>
        </supply_order_detail>
      </supply_order_details>
    </associations>
  </supply_order>
</prestashop>
```

