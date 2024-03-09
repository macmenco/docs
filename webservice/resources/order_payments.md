---
title: Order payments
---

# Resources for Order payments

### Order_payment

|        Name         |    Format     | Required | Max size | Description |
| :------------------ | :------------ | :------: | -------: | :---------- |
| **amount**          | isPrice       | ✔️       |          |             |
| **card_brand**      | isAnything    | ❌        | 254      |             |
| **card_expiration** | isAnything    | ❌        | 254      |             |
| **card_holder**     | isAnything    | ❌        | 254      |             |
| **card_number**     | isAnything    | ❌        | 254      |             |
| **conversion_rate** | isFloat       | ❌        |          |             |
| **date_add**        | isDate        | ❌        |          |             |
| **id_currency**     | isUnsignedId  | ✔️       |          | Currency ID |
| **order_reference** | isAnything    | ❌        | 9        |             |
| **payment_method**  | isGenericName | ❌        |          |             |
| **transaction_id**  | isAnything    | ❌        | 254      |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_payment>
    <amount><![CDATA[]]></amount>
    <card_brand><![CDATA[]]></card_brand>
    <card_expiration><![CDATA[]]></card_expiration>
    <card_holder><![CDATA[]]></card_holder>
    <card_number><![CDATA[]]></card_number>
    <conversion_rate><![CDATA[]]></conversion_rate>
    <date_add><![CDATA[]]></date_add>
    <id_currency><![CDATA[]]></id_currency>
    <id><![CDATA[]]></id>
    <order_reference><![CDATA[]]></order_reference>
    <payment_method><![CDATA[]]></payment_method>
    <transaction_id><![CDATA[]]></transaction_id>
  </order_payment>
</prestashop>
```

