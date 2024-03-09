---
title: Tax rule groups
---

# Resources for Tax rule groups

### Tax_rule_group

|     Name     |    Format     | Required | Max size | Description |
| :----------- | :------------ | :------: | -------: | :---------- |
| **active**   | isBool        | ❌        |          |             |
| **date_add** | isDate        | ❌        |          |             |
| **date_upd** | isDate        | ❌        |          |             |
| **deleted**  | isBool        | ❌        |          |             |
| **name**     | isGenericName | ✔️       | 64       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <tax_rule_group>
    <active><![CDATA[]]></active>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <deleted><![CDATA[]]></deleted>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
  </tax_rule_group>
</prestashop>
```

