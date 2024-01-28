# 240128 - Sample DB table structure

...for online market

## Naming Conventions

- Fields that are computed caches, depending on other fields, should have names ending with 'Cache'.
- String fields containing a JSON object of a specific type should have names ending with 'Json'.
  - same rule is applied for bbcode,