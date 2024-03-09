---
title: Product feature values
---

# Resources for Product feature values

### Product_feature_value

|      Name      |    Format     | Required | Max size | Description |
| :------------- | :------------ | :------: | -------: | :---------- |
| **custom**     | isBool        | ❌        |          |             |
| **id_feature** | isUnsignedId  | ✔️       |          |             |
| **value**      | isGenericName | ✔️       | 255      |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <product_feature_value>
    <custom><![CDATA[]]></custom>
    <id_feature><![CDATA[]]></id_feature>
    <id><![CDATA[]]></id>
    <value>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </value>
  </product_feature_value>
</prestashop>
```

