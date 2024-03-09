---
title: Languages
---

# Resources for Languages

### Language

|         Name         |      Format       | Required | Max size | Description |
| :------------------- | :---------------- | :------: | -------: | :---------- |
| **active**           | isBool            | ❌        |          |             |
| **date_format_full** | isPhpDateFormat   | ✔️       | 32       |             |
| **date_format_lite** | isPhpDateFormat   | ✔️       | 32       |             |
| **is_rtl**           | isBool            | ❌        |          |             |
| **iso_code**         | isLanguageIsoCode | ✔️       | 2        |             |
| **language_code**    | isLanguageCode    | ❌        | 5        |             |
| **locale**           | isLocale          | ❌        | 5        |             |
| **name**             | isGenericName     | ✔️       | 32       |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <language>
    <active><![CDATA[]]></active>
    <date_format_full><![CDATA[]]></date_format_full>
    <date_format_lite><![CDATA[]]></date_format_lite>
    <id><![CDATA[]]></id>
    <is_rtl><![CDATA[]]></is_rtl>
    <iso_code><![CDATA[]]></iso_code>
    <language_code><![CDATA[]]></language_code>
    <locale><![CDATA[]]></locale>
    <name><![CDATA[]]></name>
  </language>
</prestashop>
```

