---
title: Specific price rules
---

# Resources for Specific price rules

### Specific_price_rule

|        Name        |     Format      | Required | Description |
| :----------------- | :-------------- | :------: | :---------- |
| **from_quantity**  | isUnsignedInt   | ✔️       |             |
| **from**           | isDateFormat    | ❌        |             |
| **id_country**     | isUnsignedId    | ✔️       | Country ID  |
| **id_currency**    | isUnsignedId    | ✔️       | Currency ID |
| **id_group**       | isUnsignedId    | ✔️       |             |
| **id_shop**        | isUnsignedId    | ✔️       | Shop ID     |
| **name**           | isCleanHtml     | ✔️       |             |
| **price**          | isNegativePrice | ✔️       |             |
| **reduction_tax**  | isBool          | ✔️       |             |
| **reduction_type** | isReductionType | ✔️       |             |
| **reduction**      | isPrice         | ✔️       |             |
| **to**             | isDateFormat    | ❌        |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <specific_price_rule>
    <from_quantity><![CDATA[]]></from_quantity>
    <from><![CDATA[]]></from>
    <id_country><![CDATA[]]></id_country>
    <id_currency><![CDATA[]]></id_currency>
    <id_group><![CDATA[]]></id_group>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <price><![CDATA[]]></price>
    <reduction_tax><![CDATA[]]></reduction_tax>
    <reduction_type><![CDATA[]]></reduction_type>
    <reduction><![CDATA[]]></reduction>
    <to><![CDATA[]]></to>
  </specific_price_rule>
</prestashop>
```

