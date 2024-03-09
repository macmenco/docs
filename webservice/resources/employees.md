---
title: Employees
---

# Resources for Employees

### Employee

|             Name             |    Format     | Required | Writable | Max size |       Description        |
| :--------------------------- | :------------ | :------: | :------: | -------: | :----------------------- |
| **active**                   | isBool        | ❌        | ✔️       |          |                          |
| **bo_color**                 | isColor       | ❌        | ✔️       | 32       |                          |
| **bo_css**                   | isGenericName | ❌        | ✔️       | 64       |                          |
| **bo_menu**                  | isBool        | ❌        | ✔️       |          |                          |
| **bo_theme**                 | isGenericName | ❌        | ✔️       | 32       |                          |
| **bo_width**                 | isUnsignedInt | ❌        | ✔️       |          |                          |
| **default_tab**              | isInt         | ❌        | ✔️       |          |                          |
| **email**                    | isEmail       | ✔️       | ✔️       | 255      |                          |
| **firstname**                | isName        | ✔️       | ✔️       | 255      |                          |
| **has_enabled_gravatar**     | isBool        | ❌        | ✔️       |          |                          |
| **id_lang**                  | isUnsignedInt | ✔️       | ✔️       |          | Lang ID                  |
| **id_last_customer_message** | isUnsignedInt | ❌        | ✔️       |          | Last customer message ID |
| **id_last_customer**         | isUnsignedInt | ❌        | ✔️       |          | Last customer ID         |
| **id_last_order**            | isUnsignedInt | ❌        | ✔️       |          | Last order ID            |
| **id_profile**               | isInt         | ✔️       | ✔️       |          | Profile ID               |
| **last_passwd_gen**          |               | ❌        | ❌        |          |                          |
| **lastname**                 | isName        | ✔️       | ✔️       | 255      |                          |
| **passwd**                   | isPasswd      | ✔️       | ✔️       | 255      |                          |
| **preselect_date_range**     |               | ❌        | ✔️       | 32       |                          |
| **reset_password_token**     | isSha1        | ❌        | ✔️       | 40       |                          |
| **reset_password_validity**  | isDateOrNull  | ❌        | ✔️       |          |                          |
| **stats_compare_from**       | isDate        | ❌        | ❌        |          |                          |
| **stats_compare_option**     | isUnsignedInt | ❌        | ✔️       |          |                          |
| **stats_compare_to**         | isDate        | ❌        | ❌        |          |                          |
| **stats_date_from**          | isDate        | ❌        | ❌        |          |                          |
| **stats_date_to**            | isDate        | ❌        | ❌        |          |                          |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <employee>
    <active><![CDATA[]]></active>
    <bo_color><![CDATA[]]></bo_color>
    <bo_css><![CDATA[]]></bo_css>
    <bo_menu><![CDATA[]]></bo_menu>
    <bo_theme><![CDATA[]]></bo_theme>
    <bo_width><![CDATA[]]></bo_width>
    <default_tab><![CDATA[]]></default_tab>
    <email><![CDATA[]]></email>
    <firstname><![CDATA[]]></firstname>
    <has_enabled_gravatar><![CDATA[]]></has_enabled_gravatar>
    <id_lang><![CDATA[]]></id_lang>
    <id_last_customer_message><![CDATA[]]></id_last_customer_message>
    <id_last_customer><![CDATA[]]></id_last_customer>
    <id_last_order><![CDATA[]]></id_last_order>
    <id_profile><![CDATA[]]></id_profile>
    <id><![CDATA[]]></id>
    <last_passwd_gen><![CDATA[]]></last_passwd_gen>
    <lastname><![CDATA[]]></lastname>
    <passwd><![CDATA[]]></passwd>
    <preselect_date_range><![CDATA[]]></preselect_date_range>
    <reset_password_token><![CDATA[]]></reset_password_token>
    <reset_password_validity><![CDATA[]]></reset_password_validity>
    <stats_compare_from><![CDATA[]]></stats_compare_from>
    <stats_compare_option><![CDATA[]]></stats_compare_option>
    <stats_compare_to><![CDATA[]]></stats_compare_to>
    <stats_date_from><![CDATA[]]></stats_date_from>
    <stats_date_to><![CDATA[]]></stats_date_to>
  </employee>
</prestashop>
```

