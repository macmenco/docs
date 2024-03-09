---
title: Warehouses
---

# Resources for Warehouses

### Warehouse

|        Name         |      Format       | Required | Writable | Max size | Not filterable | Description |
| :------------------ | :---------------- | :------: | :------: | -------: | :------------- | :---------- |
| **associations**    |                   | ❌        | ✔️       |          |                |             |
| **deleted**         |                   | ❌        | ✔️       |          |                |             |
| **id_address**      | isUnsignedId      | ✔️       | ✔️       |          |                |             |
| **id_currency**     | isUnsignedId      | ✔️       | ✔️       |          |                | Currency ID |
| **id_employee**     | isUnsignedId      | ✔️       | ✔️       |          |                | Employee ID |
| **management_type** | isStockManagement | ✔️       | ✔️       |          |                |             |
| **name**            | isString          | ✔️       | ✔️       | 45       |                |             |
| **reference**       | isString          | ✔️       | ✔️       | 64       |                |             |
| **valuation**       |                   | ❌        | ❌        |          | true           |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <warehouse>
    <deleted><![CDATA[]]></deleted>
    <id_address><![CDATA[]]></id_address>
    <id_currency><![CDATA[]]></id_currency>
    <id_employee><![CDATA[]]></id_employee>
    <id><![CDATA[]]></id>
    <management_type><![CDATA[]]></management_type>
    <name><![CDATA[]]></name>
    <reference><![CDATA[]]></reference>
    <associations>
      <stocks>
        <stock>
          <id><![CDATA[]]></id>
        </stock>
      </stocks>
      <carriers>
        <carrier>
          <id><![CDATA[]]></id>
        </carrier>
      </carriers>
      <shops>
        <shop>
          <id><![CDATA[]]></id>
          <name><![CDATA[]]></name>
        </shop>
      </shops>
    </associations>
  </warehouse>
</prestashop>
```

