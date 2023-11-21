---
'@urql/exchange-graphcache': major
---

Use Map over plain JS object in StorageAdapter. Any custom StorageAdapter will have to update to
support `readData` and `writeData` as a Map.
