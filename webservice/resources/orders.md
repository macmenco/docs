---
title: Orders
---

# Resources for Orders

### Order

|             Name             |      Format      | Required | Not filterable |     Description     |
| :--------------------------- | :--------------- | :------: | :------------- | :------------------ |
| **associations**             |                  | ❌        |                |                     |
| **carrier_tax_rate**         | isFloat          | ❌        |                |                     |
| **conversion_rate**          | isFloat          | ✔️       |                |                     |
| **current_state**            | isUnsignedId     | ❌        |                |                     |
| **date_add**                 | isDate           | ❌        |                |                     |
| **date_upd**                 | isDate           | ❌        |                |                     |
| **delivery_date**            |                  | ❌        |                |                     |
| **delivery_number**          |                  | ❌        |                |                     |
| **gift_message**             | isMessage        | ❌        |                |                     |
| **gift**                     | isBool           | ❌        |                |                     |
| **id_address_delivery**      | isUnsignedId     | ✔️       |                | Delivery address ID |
| **id_address_invoice**       | isUnsignedId     | ✔️       |                | Invoice address ID  |
| **id_carrier**               | isUnsignedId     | ✔️       |                | Carrier ID          |
| **id_cart**                  | isUnsignedId     | ✔️       |                | Cart ID             |
| **id_currency**              | isUnsignedId     | ✔️       |                | Currency ID         |
| **id_customer**              | isUnsignedId     | ✔️       |                | Customer ID         |
| **id_lang**                  | isUnsignedId     | ✔️       |                | Lang ID             |
| **id_shop_group**            | isUnsignedId     | ❌        |                | Shop group ID       |
| **id_shop**                  | isUnsignedId     | ❌        |                | Shop ID             |
| **invoice_date**             |                  | ❌        |                |                     |
| **invoice_number**           |                  | ❌        |                |                     |
| **mobile_theme**             | isBool           | ❌        |                |                     |
| **module**                   | isModuleName     | ✔️       |                |                     |
| **note**                     | isCleanHtml      | ❌        |                |                     |
| **payment**                  | isGenericName    | ✔️       |                |                     |
| **recyclable**               | isBool           | ❌        |                |                     |
| **reference**                |                  | ❌        |                |                     |
| **round_mode**               | isUnsignedId     | ❌        |                |                     |
| **round_type**               | isUnsignedId     | ❌        |                |                     |
| **secure_key**               | isMd5            | ❌        |                |                     |
| **shipping_number**          | isTrackingNumber | ❌        | true           |                     |
| **total_discounts_tax_excl** | isPrice          | ❌        |                |                     |
| **total_discounts_tax_incl** | isPrice          | ❌        |                |                     |
| **total_discounts**          | isPrice          | ❌        |                |                     |
| **total_paid_real**          | isPrice          | ✔️       |                |                     |
| **total_paid_tax_excl**      | isPrice          | ❌        |                |                     |
| **total_paid_tax_incl**      | isPrice          | ❌        |                |                     |
| **total_paid**               | isPrice          | ✔️       |                |                     |
| **total_products_wt**        | isPrice          | ✔️       |                |                     |
| **total_products**           | isPrice          | ✔️       |                |                     |
| **total_shipping_tax_excl**  | isPrice          | ❌        |                |                     |
| **total_shipping_tax_incl**  | isPrice          | ❌        |                |                     |
| **total_shipping**           | isPrice          | ❌        |                |                     |
| **total_wrapping_tax_excl**  | isPrice          | ❌        |                |                     |
| **total_wrapping_tax_incl**  | isPrice          | ❌        |                |                     |
| **total_wrapping**           | isPrice          | ❌        |                |                     |
| **valid**                    |                  | ❌        |                |                     |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order>
    <carrier_tax_rate><![CDATA[]]></carrier_tax_rate>
    <conversion_rate><![CDATA[]]></conversion_rate>
    <current_state><![CDATA[]]></current_state>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <delivery_date><![CDATA[]]></delivery_date>
    <delivery_number><![CDATA[]]></delivery_number>
    <gift_message><![CDATA[]]></gift_message>
    <gift><![CDATA[]]></gift>
    <id_address_delivery><![CDATA[]]></id_address_delivery>
    <id_address_invoice><![CDATA[]]></id_address_invoice>
    <id_carrier><![CDATA[]]></id_carrier>
    <id_cart><![CDATA[]]></id_cart>
    <id_currency><![CDATA[]]></id_currency>
    <id_customer><![CDATA[]]></id_customer>
    <id_lang><![CDATA[]]></id_lang>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <invoice_date><![CDATA[]]></invoice_date>
    <invoice_number><![CDATA[]]></invoice_number>
    <mobile_theme><![CDATA[]]></mobile_theme>
    <module><![CDATA[]]></module>
    <note><![CDATA[]]></note>
    <payment><![CDATA[]]></payment>
    <recyclable><![CDATA[]]></recyclable>
    <reference><![CDATA[]]></reference>
    <round_mode><![CDATA[]]></round_mode>
    <round_type><![CDATA[]]></round_type>
    <secure_key><![CDATA[]]></secure_key>
    <shipping_number><![CDATA[]]></shipping_number>
    <total_discounts_tax_excl><![CDATA[]]></total_discounts_tax_excl>
    <total_discounts_tax_incl><![CDATA[]]></total_discounts_tax_incl>
    <total_discounts><![CDATA[]]></total_discounts>
    <total_paid_real><![CDATA[]]></total_paid_real>
    <total_paid_tax_excl><![CDATA[]]></total_paid_tax_excl>
    <total_paid_tax_incl><![CDATA[]]></total_paid_tax_incl>
    <total_paid><![CDATA[]]></total_paid>
    <total_products_wt><![CDATA[]]></total_products_wt>
    <total_products><![CDATA[]]></total_products>
    <total_shipping_tax_excl><![CDATA[]]></total_shipping_tax_excl>
    <total_shipping_tax_incl><![CDATA[]]></total_shipping_tax_incl>
    <total_shipping><![CDATA[]]></total_shipping>
    <total_wrapping_tax_excl><![CDATA[]]></total_wrapping_tax_excl>
    <total_wrapping_tax_incl><![CDATA[]]></total_wrapping_tax_incl>
    <total_wrapping><![CDATA[]]></total_wrapping>
    <valid><![CDATA[]]></valid>
    <associations>
      <order_rows>
        <order_row>
          <id_customization><![CDATA[]]></id_customization>
          <id><![CDATA[]]></id>
          <product_attribute_id><![CDATA[]]></product_attribute_id>
          <product_ean13><![CDATA[]]></product_ean13>
          <product_id><![CDATA[]]></product_id>
          <product_isbn><![CDATA[]]></product_isbn>
          <product_name><![CDATA[]]></product_name>
          <product_price><![CDATA[]]></product_price>
          <product_quantity><![CDATA[]]></product_quantity>
          <product_reference><![CDATA[]]></product_reference>
          <product_upc><![CDATA[]]></product_upc>
          <unit_price_tax_excl><![CDATA[]]></unit_price_tax_excl>
          <unit_price_tax_incl><![CDATA[]]></unit_price_tax_incl>
        </order_row>
      </order_rows>
    </associations>
  </order>
</prestashop>
```

