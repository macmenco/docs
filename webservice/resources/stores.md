---
title: Stores
---

# Resources for Stores

### Store

|      Name      |       Format       | Required | Max size | Description |
| :------------- | :----------------- | :------: | -------: | :---------- |
| **active**     | isBool             | ✔️       |          |             |
| **address1**   | isAddress          | ✔️       | 255      |             |
| **address2**   | isAddress          | ❌        | 255      |             |
| **city**       | isCityName         | ✔️       | 64       |             |
| **date_add**   | isDate             | ❌        |          |             |
| **date_upd**   | isDate             | ❌        |          |             |
| **email**      | isEmail            | ❌        | 255      |             |
| **fax**        | isPhoneNumber      | ❌        | 16       |             |
| **hours**      | isJson             | ❌        | 65000    |             |
| **id_country** | isUnsignedId       | ✔️       |          | Country ID  |
| **id_state**   | isNullOrUnsignedId | ❌        |          | State ID    |
| **latitude**   | isCoordinate       | ❌        | 13       |             |
| **longitude**  | isCoordinate       | ❌        | 13       |             |
| **name**       | isGenericName      | ✔️       | 255      |             |
| **note**       | isCleanHtml        | ❌        | 65000    |             |
| **phone**      | isPhoneNumber      | ❌        | 16       |             |
| **postcode**   |                    | ❌        | 12       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <store>
    <active><![CDATA[]]></active>
    <city><![CDATA[]]></city>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <email><![CDATA[]]></email>
    <fax><![CDATA[]]></fax>
    <id_country><![CDATA[]]></id_country>
    <id_state><![CDATA[]]></id_state>
    <id><![CDATA[]]></id>
    <latitude><![CDATA[]]></latitude>
    <longitude><![CDATA[]]></longitude>
    <phone><![CDATA[]]></phone>
    <postcode><![CDATA[]]></postcode>
    <hours>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </hours>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
    <address1>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </address1>
    <address2>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </address2>
    <note>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </note>
  </store>
</prestashop>
```

