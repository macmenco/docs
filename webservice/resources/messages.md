---
title: Messages
---

# Resources for Messages

### Message

|      Name       |    Format    | Required | Max size | Description |
| :-------------- | :----------- | :------: | -------: | :---------- |
| **date_add**    | isDate       | ❌        |          |             |
| **id_cart**     | isUnsignedId | ❌        |          | Cart ID     |
| **id_customer** | isUnsignedId | ❌        |          | Customer ID |
| **id_employee** | isUnsignedId | ❌        |          | Employee ID |
| **id_order**    | isUnsignedId | ❌        |          | Order ID    |
| **message**     | isCleanHtml  | ✔️       | 1600     |             |
| **private**     | isBool       | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <message>
    <date_add><![CDATA[]]></date_add>
    <id_cart><![CDATA[]]></id_cart>
    <id_customer><![CDATA[]]></id_customer>
    <id_employee><![CDATA[]]></id_employee>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
    <message><![CDATA[]]></message>
    <private><![CDATA[]]></private>
  </message>
</prestashop>
```

