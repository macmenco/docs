---
title: Products
---

# Resources for Products

### Product

|             Name              |       Format        | Required | Writable | Max size | Not filterable |    Description     |
| :---------------------------- | :------------------ | :------: | :------: | -------: | :------------- | :----------------- |
| **active**                    | isBool              | ❌        | ✔️       |          |                |                    |
| **additional_delivery_times** | isUnsignedId        | ❌        | ✔️       |          |                |                    |
| **additional_shipping_cost**  | isPrice             | ❌        | ✔️       |          |                |                    |
| **advanced_stock_management** | isBool              | ❌        | ✔️       |          |                |                    |
| **associations**              |                     | ❌        | ✔️       |          |                |                    |
| **available_date**            | isDateFormat        | ❌        | ✔️       |          |                |                    |
| **available_for_order**       | isBool              | ❌        | ✔️       |          |                |                    |
| **available_later**           | IsGenericName       | ❌        | ✔️       | 255      |                |                    |
| **available_now**             | isGenericName       | ❌        | ✔️       | 255      |                |                    |
| **cache_default_attribute**   |                     | ❌        | ✔️       |          |                |                    |
| **cache_has_attachments**     | isBool              | ❌        | ✔️       |          |                |                    |
| **cache_is_pack**             | isBool              | ❌        | ✔️       |          |                |                    |
| **condition**                 | isGenericName       | ❌        | ✔️       |          |                |                    |
| **customizable**              | isUnsignedInt       | ❌        | ✔️       |          |                |                    |
| **date_add**                  | isDate              | ❌        | ✔️       |          |                |                    |
| **date_upd**                  | isDate              | ❌        | ✔️       |          |                |                    |
| **delivery_in_stock**         | isGenericName       | ❌        | ✔️       | 255      |                |                    |
| **delivery_out_stock**        | isGenericName       | ❌        | ✔️       | 255      |                |                    |
| **depth**                     | isUnsignedFloat     | ❌        | ✔️       |          |                |                    |
| **description_short**         | isCleanHtml         | ❌        | ✔️       |          |                |                    |
| **description**               | isCleanHtml         | ❌        | ✔️       |          |                |                    |
| **ean13**                     | isEan13             | ❌        | ✔️       | 13       |                |                    |
| **ecotax**                    | isPrice             | ❌        | ✔️       |          |                |                    |
| **height**                    | isUnsignedFloat     | ❌        | ✔️       |          |                |                    |
| **id_category_default**       | isUnsignedId        | ❌        | ✔️       |          |                |                    |
| **id_default_combination**    |                     | ❌        | ✔️       |          | true           |                    |
| **id_default_image**          |                     | ❌        | ✔️       |          | true           |                    |
| **id_manufacturer**           | isUnsignedId        | ❌        | ✔️       |          |                | Manufacturer ID    |
| **id_shop_default**           | isUnsignedId        | ❌        | ✔️       |          |                | Default shop ID    |
| **id_supplier**               | isUnsignedId        | ❌        | ✔️       |          |                | Supplier ID        |
| **id_tax_rules_group**        | isUnsignedId        | ❌        | ✔️       |          |                | Tax rules group ID |
| **id_type_redirected**        | isUnsignedId        | ❌        | ✔️       |          |                |                    |
| **indexed**                   | isBool              | ❌        | ✔️       |          |                |                    |
| **is_virtual**                | isBool              | ❌        | ✔️       |          |                |                    |
| **isbn**                      | isIsbn              | ❌        | ✔️       | 32       |                |                    |
| **link_rewrite**              | isLinkRewrite       | ❌        | ✔️       | 128      |                |                    |
| **location**                  | isString            | ❌        | ✔️       | 255      |                |                    |
| **low_stock_alert**           | isBool              | ❌        | ✔️       |          |                |                    |
| **low_stock_threshold**       | isInt               | ❌        | ✔️       |          |                |                    |
| **manufacturer_name**         |                     | ❌        | ❌        |          | true           |                    |
| **meta_description**          | isGenericName       | ❌        | ✔️       | 512      |                |                    |
| **meta_keywords**             | isGenericName       | ❌        | ✔️       | 255      |                |                    |
| **meta_title**                | isGenericName       | ❌        | ✔️       | 255      |                |                    |
| **minimal_quantity**          | isUnsignedInt       | ❌        | ✔️       |          |                |                    |
| **mpn**                       | isMpn               | ❌        | ✔️       | 40       |                |                    |
| **name**                      | isCatalogName       | ❌        | ✔️       | 128      |                |                    |
| **new**                       |                     | ❌        | ✔️       |          |                |                    |
| **on_sale**                   | isBool              | ❌        | ✔️       |          |                |                    |
| **online_only**               | isBool              | ❌        | ✔️       |          |                |                    |
| **pack_stock_type**           | isUnsignedInt       | ❌        | ✔️       |          |                |                    |
| **position_in_category**      |                     | ❌        | ✔️       |          | true           |                    |
| **price**                     | isPrice             | ✔️       | ✔️       |          |                |                    |
| **quantity_discount**         | isBool              | ❌        | ✔️       |          |                |                    |
| **quantity**                  |                     | ❌        | ❌        |          | true           |                    |
| **redirect_type**             | isString            | ❌        | ✔️       |          |                |                    |
| **reference**                 | isReference         | ❌        | ✔️       | 64       |                |                    |
| **show_condition**            | isBool              | ❌        | ✔️       |          |                |                    |
| **show_price**                | isBool              | ❌        | ✔️       |          |                |                    |
| **state**                     | isUnsignedId        | ❌        | ✔️       |          |                |                    |
| **supplier_reference**        | isReference         | ❌        | ✔️       | 64       |                |                    |
| **text_fields**               | isUnsignedInt       | ❌        | ✔️       |          |                |                    |
| **type**                      |                     | ❌        | ✔️       |          | true           |                    |
| **unit_price_ratio**          |                     | ❌        | ✔️       |          |                |                    |
| **unity**                     | isString            | ❌        | ✔️       |          |                |                    |
| **upc**                       | isUpc               | ❌        | ✔️       | 12       |                |                    |
| **uploadable_files**          | isUnsignedInt       | ❌        | ✔️       |          |                |                    |
| **visibility**                | isProductVisibility | ❌        | ✔️       |          |                |                    |
| **weight**                    | isUnsignedFloat     | ❌        | ✔️       |          |                |                    |
| **wholesale_price**           | isPrice             | ❌        | ✔️       |          |                |                    |
| **width**                     | isUnsignedFloat     | ❌        | ✔️       |          |                |                    |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <product>
    <active><![CDATA[]]></active>
    <additional_delivery_times><![CDATA[]]></additional_delivery_times>
    <additional_shipping_cost><![CDATA[]]></additional_shipping_cost>
    <advanced_stock_management><![CDATA[]]></advanced_stock_management>
    <available_date><![CDATA[]]></available_date>
    <available_for_order><![CDATA[]]></available_for_order>
    <available_later>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </available_later>
    <available_now>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </available_now>
    <cache_default_attribute><![CDATA[]]></cache_default_attribute>
    <cache_has_attachments><![CDATA[]]></cache_has_attachments>
    <cache_is_pack><![CDATA[]]></cache_is_pack>
    <condition><![CDATA[]]></condition>
    <customizable><![CDATA[]]></customizable>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <delivery_in_stock>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </delivery_in_stock>
    <delivery_out_stock>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </delivery_out_stock>
    <depth><![CDATA[]]></depth>
    <description>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </description>
    <description_short>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </description_short>
    <ean13><![CDATA[]]></ean13>
    <ecotax><![CDATA[]]></ecotax>
    <height><![CDATA[]]></height>
    <id_category_default><![CDATA[]]></id_category_default>
    <id_default_combination><![CDATA[]]></id_default_combination>
    <id_default_image><![CDATA[]]></id_default_image>
    <id_manufacturer><![CDATA[]]></id_manufacturer>
    <id_shop_default><![CDATA[]]></id_shop_default>
    <id_supplier><![CDATA[]]></id_supplier>
    <id_tax_rules_group><![CDATA[]]></id_tax_rules_group>
    <id_type_redirected><![CDATA[]]></id_type_redirected>
    <id><![CDATA[]]></id>
    <indexed><![CDATA[]]></indexed>
    <is_virtual><![CDATA[]]></is_virtual>
    <isbn><![CDATA[]]></isbn>
    <link_rewrite>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </link_rewrite>
    <location><![CDATA[]]></location>
    <low_stock_alert><![CDATA[]]></low_stock_alert>
    <low_stock_threshold><![CDATA[]]></low_stock_threshold>
    <meta_description>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_description>
    <meta_keywords>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_keywords>
    <meta_title>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_title>
    <minimal_quantity><![CDATA[]]></minimal_quantity>
    <mpn><![CDATA[]]></mpn>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
    <new><![CDATA[]]></new>
    <on_sale><![CDATA[]]></on_sale>
    <online_only><![CDATA[]]></online_only>
    <pack_stock_type><![CDATA[]]></pack_stock_type>
    <position_in_category><![CDATA[]]></position_in_category>
    <price><![CDATA[]]></price>
    <quantity_discount><![CDATA[]]></quantity_discount>
    <redirect_type><![CDATA[]]></redirect_type>
    <reference><![CDATA[]]></reference>
    <show_condition><![CDATA[]]></show_condition>
    <show_price><![CDATA[]]></show_price>
    <state><![CDATA[]]></state>
    <supplier_reference><![CDATA[]]></supplier_reference>
    <text_fields><![CDATA[]]></text_fields>
    <type><![CDATA[]]></type>
    <unit_price_ratio><![CDATA[]]></unit_price_ratio>
    <unity><![CDATA[]]></unity>
    <upc><![CDATA[]]></upc>
    <uploadable_files><![CDATA[]]></uploadable_files>
    <visibility><![CDATA[]]></visibility>
    <weight><![CDATA[]]></weight>
    <wholesale_price><![CDATA[]]></wholesale_price>
    <width><![CDATA[]]></width>
    <associations>
      <categories>
        <category>
          <id><![CDATA[]]></id>
        </category>
      </categories>
      <images>
        <image>
          <id><![CDATA[]]></id>
        </image>
      </images>
      <combinations>
        <combination>
          <id><![CDATA[]]></id>
        </combination>
      </combinations>
      <product_option_values>
        <product_option_value>
          <id><![CDATA[]]></id>
        </product_option_value>
      </product_option_values>
      <product_features>
        <product_feature>
          <id><![CDATA[]]></id>
          <id_feature_value><![CDATA[]]></id_feature_value>
        </product_feature>
      </product_features>
      <tags>
        <tag>
          <id><![CDATA[]]></id>
        </tag>
      </tags>
      <stock_availables>
        <stock_available>
          <id><![CDATA[]]></id>
          <id_product_attribute><![CDATA[]]></id_product_attribute>
        </stock_available>
      </stock_availables>
      <attachments>
        <attachment>
          <id><![CDATA[]]></id>
        </attachment>
      </attachments>
      <accessories>
        <product>
          <id><![CDATA[]]></id>
        </product>
      </accessories>
      <product_bundle>
        <product>
          <id><![CDATA[]]></id>
          <id_product_attribute><![CDATA[]]></id_product_attribute>
          <quantity><![CDATA[]]></quantity>
        </product>
      </product_bundle>
    </associations>
  </product>
</prestashop>
```

