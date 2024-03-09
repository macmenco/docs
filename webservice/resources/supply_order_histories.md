---
title: Supply order histories
---

# Resources for Supply order histories

### Supply_order_history

|          Name          |    Format    | Required | Description |
| :--------------------- | :----------- | :------: | :---------- |
| **date_add**           | isDate       | ✔️       |             |
| **employee_firstname** | isName       | ❌        |             |
| **employee_lastname**  | isName       | ❌        |             |
| **id_employee**        | isUnsignedId | ✔️       | Employee ID |
| **id_state**           | isUnsignedId | ✔️       | State ID    |
| **id_supply_order**    | isUnsignedId | ✔️       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <supply_order_history>
    <date_add><![CDATA[]]></date_add>
    <employee_firstname><![CDATA[]]></employee_firstname>
    <employee_lastname><![CDATA[]]></employee_lastname>
    <id_employee><![CDATA[]]></id_employee>
    <id_state><![CDATA[]]></id_state>
    <id_supply_order><![CDATA[]]></id_supply_order>
    <id><![CDATA[]]></id>
  </supply_order_history>
</prestashop>
```

