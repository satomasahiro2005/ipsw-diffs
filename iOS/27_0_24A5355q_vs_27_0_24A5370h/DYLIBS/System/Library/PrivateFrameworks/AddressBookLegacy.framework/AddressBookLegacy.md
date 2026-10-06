## AddressBookLegacy

> `/System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x777a8` | `0x7787c` | **`+0xd4`** |
| `__AUTH_CONST.__const` | `0xec0` | `0xee0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2550` | `0x2570` | **`+0x20`** |
| `__TEXT.__cstring` | `0x26e67` | `0x26e78` | **`+0x11`** |
| `__DATA.__bss` | `0x398` | `0x3a8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3064` | `0x3074` | **`+0x10`** |

### Other Changes

```diff

-12872.100.1.0.0
+12874.100.1.0.0

-  Functions: 2612
-  Symbols:   4418
+  Functions: 2616
+  Symbols:   4424
Symbols:
+ -[ABVCardCardDAVParser preservesPhotoURIValues]
+ -[ABVCardParser preservesPhotoURIValues]
+ GCC_except_table104
+ GCC_except_table105
+ _ABVCardFilterIfNoVisibleContent
+ _ABVCardFilterIfNoVisibleContent.sOnce
+ _ABVCardFilterIfNoVisibleContent.sVisible
+ ___ABVCardFilterIfNoVisibleContent_block_invoke
- GCC_except_table101
- GCC_except_table99
CStrings:
+ " ), all_person_ids(rowid%@) AS NOT MATERIALIZED (SELECT pm.rowid%@ FROM preferredmatched pm WHERE pm.PersonLink = -1 UNION ALL SELECT abp.rowid%@ FROM preferredmatched pm JOIN ABPerson abp ON abp.PersonLink = pm.PersonLink WHERE pm.PersonLink != -1 ) "
- " ), all_person_ids(rowid%@) AS (SELECT pm.rowid%@ FROM preferredmatched pm WHERE pm.PersonLink = -1 UNION ALL SELECT abp.rowid%@ FROM preferredmatched pm JOIN ABPerson abp ON abp.PersonLink = pm.PersonLink WHERE pm.PersonLink != -1 ) "
```
