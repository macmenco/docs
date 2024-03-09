---
title: Guests
---

# Resources for Guests

### Guest

|          Name           |    Format     | Required | Max size |     Description     |
| :---------------------- | :------------ | :------: | -------: | :------------------ |
| **accept_language**     | isGenericName | ❌        | 8        |                     |
| **adobe_director**      | isBool        | ❌        |          |                     |
| **adobe_flash**         | isBool        | ❌        |          |                     |
| **apple_quicktime**     | isBool        | ❌        |          |                     |
| **id_customer**         | isUnsignedId  | ❌        |          | Customer ID         |
| **id_operating_system** | isUnsignedId  | ❌        |          | Operating system ID |
| **id_web_browser**      | isUnsignedId  | ❌        |          | Web browser ID      |
| **javascript**          | isBool        | ❌        |          |                     |
| **mobile_theme**        | isBool        | ❌        |          |                     |
| **real_player**         | isBool        | ❌        |          |                     |
| **screen_color**        | isInt         | ❌        |          |                     |
| **screen_resolution_x** | isInt         | ❌        |          |                     |
| **screen_resolution_y** | isInt         | ❌        |          |                     |
| **sun_java**            | isBool        | ❌        |          |                     |
| **windows_media**       | isBool        | ❌        |          |                     |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <guest>
    <accept_language><![CDATA[]]></accept_language>
    <adobe_director><![CDATA[]]></adobe_director>
    <adobe_flash><![CDATA[]]></adobe_flash>
    <apple_quicktime><![CDATA[]]></apple_quicktime>
    <id_customer><![CDATA[]]></id_customer>
    <id_operating_system><![CDATA[]]></id_operating_system>
    <id_web_browser><![CDATA[]]></id_web_browser>
    <id><![CDATA[]]></id>
    <javascript><![CDATA[]]></javascript>
    <mobile_theme><![CDATA[]]></mobile_theme>
    <real_player><![CDATA[]]></real_player>
    <screen_color><![CDATA[]]></screen_color>
    <screen_resolution_x><![CDATA[]]></screen_resolution_x>
    <screen_resolution_y><![CDATA[]]></screen_resolution_y>
    <sun_java><![CDATA[]]></sun_java>
    <windows_media><![CDATA[]]></windows_media>
  </guest>
</prestashop>
```

