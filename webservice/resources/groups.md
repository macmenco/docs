---
title: Groups
---

# Resources for Groups

### Group

|           Name           |        Format        | Required | Max size | Description |
| :----------------------- | :------------------- | :------: | -------: | :---------- |
| **date_add**             | isDate               | ❌        |          |             |
| **date_upd**             | isDate               | ❌        |          |             |
| **name**                 | isGenericName        | ✔️       | 32       |             |
| **price_display_method** | isPriceDisplayMethod | ✔️       |          |             |
| **reduction**            | isFloat              | ❌        |          |             |
| **show_prices**          | isBool               | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <group>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <id><![CDATA[]]></id>
    <price_display_method><![CDATA[]]></price_display_method>
    <reduction><![CDATA[]]></reduction>
    <show_prices><![CDATA[]]></show_prices>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </group>
</prestashop>
```

