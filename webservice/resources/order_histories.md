---
title: Order histories
---

# Resources for Order histories

### Order_history

|        Name        |    Format    | Required | Description |
| :----------------- | :----------- | :------: | :---------- |
| **date_add**       | isDate       | ❌        |             |
| **id_employee**    | isUnsignedId | ❌        | Employee ID |
| **id_order_state** | isUnsignedId | ✔️       |             |
| **id_order**       | isUnsignedId | ✔️       | Order ID    |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_history>
    <date_add><![CDATA[]]></date_add>
    <id_employee><![CDATA[]]></id_employee>
    <id_order_state><![CDATA[]]></id_order_state>
    <id_order><![CDATA[]]></id_order>
    <id><![CDATA[]]></id>
  </order_history>
</prestashop>
```

