---
title: States
---

# Resources for States

### State

|      Name      |     Format     | Required | Max size | Description |
| :------------- | :------------- | :------: | -------: | :---------- |
| **active**     | isBool         | ❌        |          |             |
| **id_country** | isUnsignedId   | ✔️       |          | Country ID  |
| **id_zone**    | isUnsignedId   | ✔️       |          | Zone ID     |
| **iso_code**   | isStateIsoCode | ✔️       | 7        |             |
| **name**       | isGenericName  | ✔️       | 32       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <state>
    <active><![CDATA[]]></active>
    <id_country><![CDATA[]]></id_country>
    <id_zone><![CDATA[]]></id_zone>
    <id><![CDATA[]]></id>
    <iso_code><![CDATA[]]></iso_code>
    <name><![CDATA[]]></name>
  </state>
</prestashop>
```

