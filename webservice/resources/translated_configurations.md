---
title: Translated configurations
---

# Resources for Translated configurations

### Translated_configuration

|       Name        |    Format    | Required | Max size |  Description  |
| :---------------- | :----------- | :------: | -------: | :------------ |
| **date_add**      | isDate       | ❌        |          |               |
| **date_upd**      | isDate       | ❌        |          |               |
| **id_shop_group** | isUnsignedId | ❌        |          | Shop group ID |
| **id_shop**       | isUnsignedId | ❌        |          | Shop ID       |
| **name**          | isConfigName | ✔️       | 32       |               |
| **value**         |              | ❌        |          |               |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <translated_configuration>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <value>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </value>
  </translated_configuration>
</prestashop>
```

