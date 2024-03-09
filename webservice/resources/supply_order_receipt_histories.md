---
title: Supply order receipt histories
---

# Resources for Supply order receipt histories

### Supply_order_receipt_history

|            Name            |    Format     | Required | Description |
| :------------------------- | :------------ | :------: | :---------- |
| **date_add**               | isDate        | ❌        |             |
| **employee_firstname**     | isName        | ❌        |             |
| **employee_lastname**      | isName        | ❌        |             |
| **id_employee**            | isUnsignedId  | ✔️       | Employee ID |
| **id_supply_order_detail** | isUnsignedId  | ✔️       |             |
| **id_supply_order_state**  | isUnsignedId  | ✔️       |             |
| **quantity**               | isUnsignedInt | ✔️       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <supply_order_receipt_history>
    <date_add><![CDATA[]]></date_add>
    <employee_firstname><![CDATA[]]></employee_firstname>
    <employee_lastname><![CDATA[]]></employee_lastname>
    <id_employee><![CDATA[]]></id_employee>
    <id_supply_order_detail><![CDATA[]]></id_supply_order_detail>
    <id_supply_order_state><![CDATA[]]></id_supply_order_state>
    <id><![CDATA[]]></id>
    <quantity><![CDATA[]]></quantity>
  </supply_order_receipt_history>
</prestashop>
```

