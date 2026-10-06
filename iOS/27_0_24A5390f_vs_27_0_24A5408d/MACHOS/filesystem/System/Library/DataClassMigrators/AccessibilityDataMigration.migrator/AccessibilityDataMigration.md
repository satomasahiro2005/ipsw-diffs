## AccessibilityDataMigration

> `/System/Library/DataClassMigrators/AccessibilityDataMigration.migrator/AccessibilityDataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2860` | `0x291c` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0x12a` | `0x17d` | **`+0x53`** |
| `__TEXT.__auth_stubs` | `0x2e0` | `0x2f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__const` | `0x38` | `0x40` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Symbols:   87
-  CStrings:  229
+  Symbols:   88
+  CStrings:  231
Symbols:
+ __AXSTripleClickCopyOptions
Functions:
~ sub_12a0 : 208 -> 396
CStrings:
+ "Triple click options after migration: %@"
+ "Triple click options before migration: %@"
```
