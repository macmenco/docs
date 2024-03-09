---
title: Product customization fields
---

# Resources for Product customization fields

### Customization_field

|      Name      |    Format    | Required | Max size | Description |
| :------------- | :----------- | :------: | -------: | :---------- |
| **id_product** | isUnsignedId | ✔️       |          | Product ID  |
| **is_deleted** | isBool       | ❌        |          |             |
| **is_module**  | isBool       | ❌        |          |             |
| **name**       |              | ✔️       | 255      |             |
| **required**   | isBool       | ✔️       |          |             |
| **type**       | isUnsignedId | ✔️       |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <customization_field>
    <id_product><![CDATA[]]></id_product>
    <id><![CDATA[]]></id>
    <is_deleted><![CDATA[]]></is_deleted>
    <is_module><![CDATA[]]></is_module>
    <required><![CDATA[]]></required>
    <type><![CDATA[]]></type>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </customization_field>
</prestashop>
```

