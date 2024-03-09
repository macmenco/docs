---
title: Shops
---

# Resources for Shops

### Shop

|       Name        |    Format     | Required | Max size |  Description  |
| :---------------- | :------------ | :------: | -------: | :------------ |
| **active**        | isBool        | ❌        |          |               |
| **color**         | isColor       | ❌        |          |               |
| **deleted**       | isBool        | ❌        |          |               |
| **id_category**   |               | ✔️       |          |               |
| **id_shop_group** |               | ✔️       |          | Shop group ID |
| **name**          | isGenericName | ✔️       | 64       |               |
| **theme_name**    | isThemeName   | ❌        |          |               |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <shop>
    <active><![CDATA[]]></active>
    <color><![CDATA[]]></color>
    <deleted><![CDATA[]]></deleted>
    <id_category><![CDATA[]]></id_category>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <theme_name><![CDATA[]]></theme_name>
  </shop>
</prestashop>
```

