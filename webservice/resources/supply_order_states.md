---
title: Supply order states
---

# Resources for Supply order states

### Supply_order_state

|        Name         |    Format     | Required | Max size | Description |
| :------------------ | :------------ | :------: | -------: | :---------- |
| **color**           | isColor       | ❌        |          |             |
| **delivery_note**   | isBool        | ❌        |          |             |
| **editable**        | isBool        | ❌        |          |             |
| **enclosed**        | isBool        | ❌        |          |             |
| **name**            | isGenericName | ✔️       | 128      |             |
| **pending_receipt** | isBool        | ❌        |          |             |
| **receipt_state**   | isBool        | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <supply_order_state>
    <color><![CDATA[]]></color>
    <delivery_note><![CDATA[]]></delivery_note>
    <editable><![CDATA[]]></editable>
    <enclosed><![CDATA[]]></enclosed>
    <id><![CDATA[]]></id>
    <pending_receipt><![CDATA[]]></pending_receipt>
    <receipt_state><![CDATA[]]></receipt_state>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </supply_order_state>
</prestashop>
```

