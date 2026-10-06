## CloudTabsMigrator

> `/System/Library/DataClassMigrators/CloudTabsMigrator.migrator/CloudTabsMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x6e0` | `0x6c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x67b` | `0x668` | **`-0x13`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x1a0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   73
-  CStrings:  69
+  Symbols:   72
+  CStrings:  68
Symbols:
- _showRecentSearchesDefaultsKey
CStrings:
- "ShowRecentSearches"
```
