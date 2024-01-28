# 240128 - Sample DB table structure

...for online market

## Naming Conventions

- Fields that are computed caches, depending on other fields, should have names ending with '_cache'.
- String fields containing a JSON object of a specific type should have names ending with '_json'.
  - same rule is applied for bbcode,
