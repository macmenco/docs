---
title: Product option values
---

# Resources for Product option values

### Product_option_value

|          Name          |    Format     | Required | Max size | Description |
| :--------------------- | :------------ | :------: | -------: | :---------- |
| **color**              | isColor       | ❌        |          |             |
| **id_attribute_group** | isUnsignedId  | ✔️       |          |             |
| **name**               | isGenericName | ✔️       | 128      |             |
| **position**           | isInt         | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <product_option_value>
    <color><![CDATA[]]></color>
    <id_attribute_group><![CDATA[]]></id_attribute_group>
    <id><![CDATA[]]></id>
    <position><![CDATA[]]></position>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </product_option_value>
</prestashop>
```

