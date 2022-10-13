# grammar-corrections-json-format
Use JSON files to see and fix grammar errors.

[Click to view the file](./main.jsonc)

<!-- Badges -->
![License: GPL-3.0](https://img.shields.io/github/license/softcode589/grammar-corrections-json-format?style=for-the-badge)
![Help wanted issues](https://img.shields.io/github/issues/softcode589/grammar-corrections-json-format/help%20wanted?label=help%20wanted%20issues&logo=github&style=for-the-badge)

## Format
Let's explain the format of the json files.

**What are the properties and values used for?**

- properties are the spelling mistakes
- values are the fixes

So assuming we have a json file with that criteria here is it:

```json
{
  "acceppt": "accept"
}
```

You could see that `acceppt` (the property name) is spelled incorrectly.  
You could also see that `accept` (the value) is spelled correctly.
