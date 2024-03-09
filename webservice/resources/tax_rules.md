---
title: Tax rules
---

# Resources for Tax rules

### Tax_rule

|          Name          |    Format     | Required |    Description     |
| :--------------------- | :------------ | :------: | :----------------- |
| **behavior**           | isUnsignedInt | ❌        |                    |
| **description**        | isString      | ❌        |                    |
| **id_country**         | isUnsignedId  | ✔️       | Country ID         |
| **id_state**           | isUnsignedId  | ❌        | State ID           |
| **id_tax_rules_group** | isUnsignedId  | ✔️       | Tax rules group ID |
| **id_tax**             | isUnsignedId  | ✔️       |                    |
| **zipcode_from**       | isPostCode    | ❌        |                    |
| **zipcode_to**         | isPostCode    | ❌        |                    |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <tax_rule>
    <behavior><![CDATA[]]></behavior>
    <description><![CDATA[]]></description>
    <id_country><![CDATA[]]></id_country>
    <id_state><![CDATA[]]></id_state>
    <id_tax_rules_group><![CDATA[]]></id_tax_rules_group>
    <id_tax><![CDATA[]]></id_tax>
    <id><![CDATA[]]></id>
    <zipcode_from><![CDATA[]]></zipcode_from>
    <zipcode_to><![CDATA[]]></zipcode_to>
  </tax_rule>
</prestashop>
```

