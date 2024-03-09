---
title: Shop urls
---

# Resources for Shop urls

### Shop_url

|       Name       |   Format    | Required | Max size | Description |
| :--------------- | :---------- | :------: | -------: | :---------- |
| **active**       | isBool      | ❌        |          |             |
| **domain_ssl**   | isCleanHtml | ❌        | 255      |             |
| **domain**       | isCleanHtml | ✔️       | 255      |             |
| **id_shop**      |             | ✔️       |          | Shop ID     |
| **main**         | isBool      | ❌        |          |             |
| **physical_uri** |             | ❌        | 64       |             |
| **virtual_uri**  |             | ❌        | 64       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <shop_url>
    <active><![CDATA[]]></active>
    <domain_ssl><![CDATA[]]></domain_ssl>
    <domain><![CDATA[]]></domain>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <main><![CDATA[]]></main>
    <physical_uri><![CDATA[]]></physical_uri>
    <virtual_uri><![CDATA[]]></virtual_uri>
  </shop_url>
</prestashop>
```

