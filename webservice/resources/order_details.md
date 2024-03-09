---
title: Order details
---

# Resources for Order details

### Order_detail

|               Name                |    Format     | Required |     Description      |
| :-------------------------------- | :------------ | :------: | :------------------- |
| **associations**                  |               | ❌        |                      |
| **discount_quantity_applied**     | isInt         | ❌        |                      |
| **download_deadline**             | isDateFormat  | ❌        |                      |
| **download_hash**                 | isGenericName | ❌        |                      |
| **download_nb**                   | isInt         | ❌        |                      |
| **ecotax_tax_rate**               | isFloat       | ❌        |                      |
| **ecotax**                        | isFloat       | ❌        |                      |
| **group_reduction**               | isFloat       | ❌        |                      |
| **id_customization**              | isUnsignedId  | ❌        | Customization ID     |
| **id_order_invoice**              | isUnsignedId  | ❌        | Order invoice ID     |
| **id_order**                      | isUnsignedId  | ✔️       | Order ID             |
| **id_shop**                       | isUnsignedId  | ✔️       | Shop ID              |
| **id_tax_rules_group**            | isInt         | ❌        | Tax rules group ID   |
| **id_warehouse**                  | isUnsignedId  | ✔️       | Warehouse ID         |
| **original_product_price**        | isPrice       | ❌        |                      |
| **original_wholesale_price**      | isPrice       | ❌        |                      |
| **product_attribute_id**          | isUnsignedId  | ❌        | Product attribute ID |
| **product_ean13**                 | isEan13       | ❌        |                      |
| **product_id**                    | isUnsignedId  | ❌        | Product ID           |
| **product_isbn**                  | isIsbn        | ❌        |                      |
| **product_mpn**                   | isMpn         | ❌        |                      |
| **product_name**                  | isGenericName | ✔️       |                      |
| **product_price**                 | isPrice       | ✔️       |                      |
| **product_quantity_discount**     | isFloat       | ❌        |                      |
| **product_quantity_in_stock**     | isInt         | ❌        |                      |
| **product_quantity_refunded**     | isUnsignedInt | ❌        |                      |
| **product_quantity_reinjected**   | isUnsignedInt | ❌        |                      |
| **product_quantity_return**       | isUnsignedInt | ❌        |                      |
| **product_quantity**              | isInt         | ✔️       |                      |
| **product_reference**             | isReference   | ❌        |                      |
| **product_supplier_reference**    | isReference   | ❌        |                      |
| **product_upc**                   | isUpc         | ❌        |                      |
| **product_weight**                | isFloat       | ❌        |                      |
| **purchase_supplier_price**       | isPrice       | ❌        |                      |
| **reduction_amount_tax_excl**     | isPrice       | ❌        |                      |
| **reduction_amount_tax_incl**     | isPrice       | ❌        |                      |
| **reduction_amount**              | isPrice       | ❌        |                      |
| **reduction_percent**             | isFloat       | ❌        |                      |
| **tax_computation_method**        | isUnsignedId  | ❌        |                      |
| **total_price_tax_excl**          | isPrice       | ❌        |                      |
| **total_price_tax_incl**          | isPrice       | ❌        |                      |
| **total_refunded_tax_excl**       | isPrice       | ❌        |                      |
| **total_refunded_tax_incl**       | isPrice       | ❌        |                      |
| **total_shipping_price_tax_excl** | isPrice       | ❌        |                      |
| **total_shipping_price_tax_incl** | isPrice       | ❌        |                      |
| **unit_price_tax_excl**           | isPrice       | ❌        |                      |
| **unit_price_tax_incl**           | isPrice       | ❌        |                      |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_detail>
    <discount_quantity_applied><![CDATA[]]></discount_quantity_applied>
    <download_deadline><![CDATA[]]></download_deadline>
    <download_hash><![CDATA[]]></download_hash>
    <download_nb><![CDATA[]]></download_nb>
    <ecotax_tax_rate><![CDATA[]]></ecotax_tax_rate>
    <ecotax><![CDATA[]]></ecotax>
    <group_reduction><![CDATA[]]></group_reduction>
    <id_customization><![CDATA[]]></id_customization>
    <id_order_invoice><![CDATA[]]></id_order_invoice>
    <id_order><![CDATA[]]></id_order>
    <id_shop><![CDATA[]]></id_shop>
    <id_tax_rules_group><![CDATA[]]></id_tax_rules_group>
    <id_warehouse><![CDATA[]]></id_warehouse>
    <id><![CDATA[]]></id>
    <original_product_price><![CDATA[]]></original_product_price>
    <original_wholesale_price><![CDATA[]]></original_wholesale_price>
    <product_attribute_id><![CDATA[]]></product_attribute_id>
    <product_ean13><![CDATA[]]></product_ean13>
    <product_id><![CDATA[]]></product_id>
    <product_isbn><![CDATA[]]></product_isbn>
    <product_mpn><![CDATA[]]></product_mpn>
    <product_name><![CDATA[]]></product_name>
    <product_price><![CDATA[]]></product_price>
    <product_quantity_discount><![CDATA[]]></product_quantity_discount>
    <product_quantity_in_stock><![CDATA[]]></product_quantity_in_stock>
    <product_quantity_refunded><![CDATA[]]></product_quantity_refunded>
    <product_quantity_reinjected><![CDATA[]]></product_quantity_reinjected>
    <product_quantity_return><![CDATA[]]></product_quantity_return>
    <product_quantity><![CDATA[]]></product_quantity>
    <product_reference><![CDATA[]]></product_reference>
    <product_supplier_reference><![CDATA[]]></product_supplier_reference>
    <product_upc><![CDATA[]]></product_upc>
    <product_weight><![CDATA[]]></product_weight>
    <purchase_supplier_price><![CDATA[]]></purchase_supplier_price>
    <reduction_amount_tax_excl><![CDATA[]]></reduction_amount_tax_excl>
    <reduction_amount_tax_incl><![CDATA[]]></reduction_amount_tax_incl>
    <reduction_amount><![CDATA[]]></reduction_amount>
    <reduction_percent><![CDATA[]]></reduction_percent>
    <tax_computation_method><![CDATA[]]></tax_computation_method>
    <total_price_tax_excl><![CDATA[]]></total_price_tax_excl>
    <total_price_tax_incl><![CDATA[]]></total_price_tax_incl>
    <total_refunded_tax_excl><![CDATA[]]></total_refunded_tax_excl>
    <total_refunded_tax_incl><![CDATA[]]></total_refunded_tax_incl>
    <total_shipping_price_tax_excl><![CDATA[]]></total_shipping_price_tax_excl>
    <total_shipping_price_tax_incl><![CDATA[]]></total_shipping_price_tax_incl>
    <unit_price_tax_excl><![CDATA[]]></unit_price_tax_excl>
    <unit_price_tax_incl><![CDATA[]]></unit_price_tax_incl>
    <associations>
      <taxes>
        <tax>
          <id><![CDATA[]]></id>
        </tax>
      </taxes>
    </associations>
  </order_detail>
</prestashop>
```

