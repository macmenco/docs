---
title: Image types
---

# Resources for Image types

### Image_type

|       Name        |     Format      | Required | Max size | Description |
| :---------------- | :-------------- | :------: | -------: | :---------- |
| **categories**    | isBool          | ❌        |          |             |
| **height**        | isImageSize     | ✔️       |          |             |
| **manufacturers** | isBool          | ❌        |          |             |
| **name**          | isImageTypeName | ✔️       | 64       |             |
| **products**      | isBool          | ❌        |          |             |
| **stores**        | isBool          | ❌        |          |             |
| **suppliers**     | isBool          | ❌        |          |             |
| **width**         | isImageSize     | ✔️       |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <image_type>
    <categories><![CDATA[]]></categories>
    <height><![CDATA[]]></height>
    <id><![CDATA[]]></id>
    <manufacturers><![CDATA[]]></manufacturers>
    <name><![CDATA[]]></name>
    <products><![CDATA[]]></products>
    <stores><![CDATA[]]></stores>
    <suppliers><![CDATA[]]></suppliers>
    <width><![CDATA[]]></width>
  </image_type>
</prestashop>
```

