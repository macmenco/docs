---
title: Deliveries
---

# Resources for Deliveries

### Delivery

|        Name         |    Format    | Required |  Description   |
| :------------------ | :----------- | :------: | :------------- |
| **id_carrier**      | isUnsignedId | ✔️       | Carrier ID     |
| **id_range_price**  | isUnsignedId | ✔️       | Range price ID |
| **id_range_weight** | isUnsignedId | ✔️       |                |
| **id_shop_group**   |              | ❌        | Shop group ID  |
| **id_shop**         |              | ❌        | Shop ID        |
| **id_zone**         | isUnsignedId | ✔️       | Zone ID        |
| **price**           | isPrice      | ✔️       |                |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <delivery>
    <id_carrier><![CDATA[]]></id_carrier>
    <id_range_price><![CDATA[]]></id_range_price>
    <id_range_weight><![CDATA[]]></id_range_weight>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id_shop><![CDATA[]]></id_shop>
    <id_zone><![CDATA[]]></id_zone>
    <id><![CDATA[]]></id>
    <price><![CDATA[]]></price>
  </delivery>
</prestashop>
```

