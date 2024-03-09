---
title: Customer threads
---

# Resources for Customer threads

### Customer_thread

|       Name       |    Format     | Required | Max size | Description |
| :--------------- | :------------ | :------: | -------: | :---------- |
| **associations** |               | ❌        |          |             |
| **date_add**     | isDate        | ❌        |          |             |
| **date_upd**     | isDate        | ❌        |          |             |
| **email**        | isEmail       | ❌        | 255      |             |
| **id_contact**   | isUnsignedId  | ✔️       |          | Contact ID  |
| **id_customer**  | isUnsignedId  | ❌        |          | Customer ID |
| **id_lang**      | isUnsignedId  | ✔️       |          | Lang ID     |
| **id_order**     | isUnsignedId  | ❌        |          | Order ID    |
| **id_product**   | isUnsignedId  | ❌        |          | Product ID  |
| **id_shop**      | isUnsignedId  | ❌        |          | Shop ID     |
| **status**       |               | ❌        |          |             |
| **token**        | isGenericName | ✔️       |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <customer_thread>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <email><![CDATA[]]></email>
    <id_contact><![CDATA[]]></id_contact>
    <id_customer><![CDATA[]]></id_customer>
    <id_lang><![CDATA[]]></id_lang>
    <id_order><![CDATA[]]></id_order>
    <id_product><![CDATA[]]></id_product>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <status><![CDATA[]]></status>
    <token><![CDATA[]]></token>
    <associations>
      <customer_messages>
        <customer_message>
          <id><![CDATA[]]></id>
        </customer_message>
      </customer_messages>
    </associations>
  </customer_thread>
</prestashop>
```

