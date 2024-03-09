---
title: Stock movement reasons
---

# Resources for Stock movement reasons

### Stock_movement_reason

|     Name     |    Format     | Required | Max size | Description |
| :----------- | :------------ | :------: | -------: | :---------- |
| **date_add** | isDate        | ❌        |          |             |
| **date_upd** | isDate        | ❌        |          |             |
| **deleted**  |               | ❌        |          |             |
| **name**     | isGenericName | ✔️       | 255      |             |
| **sign**     |               | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <stock_movement_reason>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <deleted><![CDATA[]]></deleted>
    <id><![CDATA[]]></id>
    <sign><![CDATA[]]></sign>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </stock_movement_reason>
</prestashop>
```

