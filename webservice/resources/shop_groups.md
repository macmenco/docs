---
title: Shop groups
---

# Resources for Shop groups

### Shop_group

|        Name        |    Format     | Required | Max size | Description |
| :----------------- | :------------ | :------: | -------: | :---------- |
| **active**         | isBool        | ❌        |          |             |
| **color**          | isColor       | ❌        |          |             |
| **deleted**        | isBool        | ❌        |          |             |
| **name**           | isGenericName | ✔️       | 64       |             |
| **share_customer** | isBool        | ❌        |          |             |
| **share_order**    | isBool        | ❌        |          |             |
| **share_stock**    | isBool        | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <shop_group>
    <active><![CDATA[]]></active>
    <color><![CDATA[]]></color>
    <deleted><![CDATA[]]></deleted>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <share_customer><![CDATA[]]></share_customer>
    <share_order><![CDATA[]]></share_order>
    <share_stock><![CDATA[]]></share_stock>
  </shop_group>
</prestashop>
```

