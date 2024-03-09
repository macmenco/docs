---
title: Manufacturers
---

# Resources for Manufacturers

### Manufacturer

|         Name          |    Format     | Required | Writable | Max size | Not filterable | Description |
| :-------------------- | :------------ | :------: | :------: | -------: | :------------- | :---------- |
| **active**            |               | ❌        | ✔️       |          |                |             |
| **associations**      |               | ❌        | ✔️       |          |                |             |
| **date_add**          |               | ❌        | ✔️       |          |                |             |
| **date_upd**          |               | ❌        | ✔️       |          |                |             |
| **description**       | isCleanHtml   | ❌        | ✔️       |          |                |             |
| **link_rewrite**      |               | ❌        | ❌        |          | true           |             |
| **meta_description**  | isGenericName | ❌        | ✔️       | 512      |                |             |
| **meta_keywords**     | isGenericName | ❌        | ✔️       |          |                |             |
| **meta_title**        | isGenericName | ❌        | ✔️       | 255      |                |             |
| **name**              | isCatalogName | ✔️       | ✔️       | 64       |                |             |
| **short_description** | isCleanHtml   | ❌        | ✔️       |          |                |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <manufacturer>
    <active><![CDATA[]]></active>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <id><![CDATA[]]></id>
    <name><![CDATA[]]></name>
    <description>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </description>
    <short_description>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </short_description>
    <meta_title>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_title>
    <meta_description>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_description>
    <meta_keywords>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </meta_keywords>
    <associations>
      <addresses>
        <address>
          <id><![CDATA[]]></id>
        </address>
      </addresses>
    </associations>
  </manufacturer>
</prestashop>
```

