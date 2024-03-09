---
title: Taxes
---

# Resources for Taxes

### Tax

|    Name     |    Format     | Required | Max size | Description |
| :---------- | :------------ | :------: | -------: | :---------- |
| **active**  |               | ❌        |          |             |
| **deleted** |               | ❌        |          |             |
| **name**    | isGenericName | ✔️       | 32       |             |
| **rate**    | isFloat       | ✔️       |          |             |


### Blank schema

```xml
<prestashop xmlns:xlink="http://www.w3.org/1999/xlink">
  <tax>
    <active><![CDATA[]]></active>
    <deleted><![CDATA[]]></deleted>
    <id><![CDATA[]]></id>
    <rate><![CDATA[]]></rate>
    <name>
      <language id="1"><![CDATA[]]></language>
      <language id="2"><![CDATA[]]></language>
    </name>
  </tax>
</prestashop>
```

