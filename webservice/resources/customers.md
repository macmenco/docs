---
title: Customers
---

# Resources for Customers

### Customer

|              Name              |     Format     | Required | Writable | Max size |   Description    |
| :----------------------------- | :------------- | :------: | :------: | -------: | :--------------- |
| **active**                     | isBool         | ❌        | ✔️       |          |                  |
| **ape**                        | isApe          | ❌        | ✔️       |          |                  |
| **associations**               |                | ❌        | ✔️       |          |                  |
| **birthday**                   | isBirthDate    | ❌        | ✔️       |          |                  |
| **company**                    | isGenericName  | ❌        | ✔️       |          |                  |
| **date_add**                   | isDate         | ❌        | ✔️       |          |                  |
| **date_upd**                   | isDate         | ❌        | ✔️       |          |                  |
| **deleted**                    | isBool         | ❌        | ✔️       |          |                  |
| **email**                      | isEmail        | ✔️       | ✔️       | 255      |                  |
| **firstname**                  | isCustomerName | ✔️       | ✔️       | 255      |                  |
| **id_default_group**           |                | ❌        | ✔️       |          | Default group ID |
| **id_gender**                  | isUnsignedId   | ❌        | ✔️       |          | Gender ID        |
| **id_lang**                    | isUnsignedId   | ❌        | ✔️       |          | Lang ID          |
| **id_risk**                    | isUnsignedInt  | ❌        | ✔️       |          | Risk ID          |
| **id_shop_group**              | isUnsignedId   | ❌        | ✔️       |          | Shop group ID    |
| **id_shop**                    | isUnsignedId   | ❌        | ✔️       |          | Shop ID          |
| **ip_registration_newsletter** |                | ❌        | ✔️       |          |                  |
| **is_guest**                   | isBool         | ❌        | ✔️       |          |                  |
| **last_passwd_gen**            |                | ❌        | ❌        |          |                  |
| **lastname**                   | isCustomerName | ✔️       | ✔️       | 255      |                  |
| **max_payment_days**           | isUnsignedInt  | ❌        | ✔️       |          |                  |
| **newsletter_date_add**        |                | ❌        | ✔️       |          |                  |
| **newsletter**                 | isBool         | ❌        | ✔️       |          |                  |
| **note**                       |                | ❌        | ✔️       | 65000    |                  |
| **optin**                      | isBool         | ❌        | ✔️       |          |                  |
| **outstanding_allow_amount**   | isFloat        | ❌        | ✔️       |          |                  |
| **passwd**                     | isPasswd       | ✔️       | ✔️       | 255      |                  |
| **reset_password_token**       | isSha1         | ❌        | ✔️       | 40       |                  |
| **reset_password_validity**    | isDateOrNull   | ❌        | ✔️       |          |                  |
| **secure_key**                 | isMd5          | ❌        | ❌        |          |                  |
| **show_public_prices**         | isBool         | ❌        | ✔️       |          |                  |
| **siret**                      | isGenericName  | ❌        | ✔️       |          |                  |
| **website**                    | isUrl          | ❌        | ✔️       |          |                  |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <customer>
    <active><![CDATA[]]></active>
    <ape><![CDATA[]]></ape>
    <birthday><![CDATA[]]></birthday>
    <company><![CDATA[]]></company>
    <date_add><![CDATA[]]></date_add>
    <date_upd><![CDATA[]]></date_upd>
    <deleted><![CDATA[]]></deleted>
    <email><![CDATA[]]></email>
    <firstname><![CDATA[]]></firstname>
    <id_default_group><![CDATA[]]></id_default_group>
    <id_gender><![CDATA[]]></id_gender>
    <id_lang><![CDATA[]]></id_lang>
    <id_risk><![CDATA[]]></id_risk>
    <id_shop_group><![CDATA[]]></id_shop_group>
    <id_shop><![CDATA[]]></id_shop>
    <id><![CDATA[]]></id>
    <ip_registration_newsletter><![CDATA[]]></ip_registration_newsletter>
    <is_guest><![CDATA[]]></is_guest>
    <last_passwd_gen><![CDATA[]]></last_passwd_gen>
    <lastname><![CDATA[]]></lastname>
    <max_payment_days><![CDATA[]]></max_payment_days>
    <newsletter_date_add><![CDATA[]]></newsletter_date_add>
    <newsletter><![CDATA[]]></newsletter>
    <note><![CDATA[]]></note>
    <optin><![CDATA[]]></optin>
    <outstanding_allow_amount><![CDATA[]]></outstanding_allow_amount>
    <passwd><![CDATA[]]></passwd>
    <reset_password_token><![CDATA[]]></reset_password_token>
    <reset_password_validity><![CDATA[]]></reset_password_validity>
    <secure_key><![CDATA[]]></secure_key>
    <show_public_prices><![CDATA[]]></show_public_prices>
    <siret><![CDATA[]]></siret>
    <website><![CDATA[]]></website>
    <associations>
      <groups>
        <group>
          <id><![CDATA[]]></id>
        </group>
      </groups>
    </associations>
  </customer>
</prestashop>
```

