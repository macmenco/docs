---
title: Product options
---

# Resources for Product options

### Product_option

|        Name        |    Format     | Required | Max size | Description |
| :----------------- | :------------ | :------: | -------: | :---------- |
| **associations**   |               | ❌        |          |             |
| **group_type**     |               | ✔️       |          |             |
| **is_color_group** | isBool        | ❌        |          |             |
| **name**           | isGenericName | ✔️       | 128      |             |
| **position**       | isInt         | ❌        |          |             |
| **public_name**    | isGenericName | ✔️       | 64       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <product_option>
    <group_type><![CDATA[]]></group_type>
    <id><![CDATA[]]></id>
    <is_color_group><![CDATA[]]></is_color_group>
    <position><![CDATA[]]></position>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
    <public_name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </public_name>
    <associations>
      <product_option_values>
        <product_option_value>
          <id><![CDATA[]]></id>
        </product_option_value>
      </product_option_values>
    </associations>
  </product_option>
</prestashop>
```

