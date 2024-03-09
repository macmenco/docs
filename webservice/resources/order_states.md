---
title: Order states
---

# Resources for Order states

### Order_state

|       Name       |    Format     | Required | Max size | Description |
| :--------------- | :------------ | :------: | -------: | :---------- |
| **color**        | isColor       | ❌        |          |             |
| **deleted**      | isBool        | ❌        |          |             |
| **delivery**     | isBool        | ❌        |          |             |
| **hidden**       | isBool        | ❌        |          |             |
| **invoice**      | isBool        | ❌        |          |             |
| **logable**      | isBool        | ❌        |          |             |
| **module_name**  | isModuleName  | ❌        |          |             |
| **name**         | isGenericName | ✔️       | 64       |             |
| **paid**         | isBool        | ❌        |          |             |
| **pdf_delivery** | isBool        | ❌        |          |             |
| **pdf_invoice**  | isBool        | ❌        |          |             |
| **send_email**   | isBool        | ❌        |          |             |
| **shipped**      | isBool        | ❌        |          |             |
| **template**     | isTplName     | ❌        | 64       |             |
| **unremovable**  | isBool        | ❌        |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <order_state>
    <color><![CDATA[]]></color>
    <deleted><![CDATA[]]></deleted>
    <delivery><![CDATA[]]></delivery>
    <hidden><![CDATA[]]></hidden>
    <id><![CDATA[]]></id>
    <invoice><![CDATA[]]></invoice>
    <logable><![CDATA[]]></logable>
    <module_name><![CDATA[]]></module_name>
    <paid><![CDATA[]]></paid>
    <pdf_delivery><![CDATA[]]></pdf_delivery>
    <pdf_invoice><![CDATA[]]></pdf_invoice>
    <send_email><![CDATA[]]></send_email>
    <shipped><![CDATA[]]></shipped>
    <unremovable><![CDATA[]]></unremovable>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
    <template>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </template>
  </order_state>
</prestashop>
```

