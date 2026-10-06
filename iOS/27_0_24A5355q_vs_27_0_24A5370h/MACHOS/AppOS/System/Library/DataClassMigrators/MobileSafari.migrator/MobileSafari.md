## MobileSafari

> `/System/Library/DataClassMigrators/MobileSafari.migrator/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5dec` | `0x5e44` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x11bb` | `0x120e` | **`+0x53`** |
| `__DATA_CONST.__cfstring` | `0xfe0` | `0xfc0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x14c0` | `0x14e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x14b4` | `0x14cc` | **`+0x18`** |
| `__TEXT.__cstring` | `0xd8a` | `0xd77` | **`-0x13`** |
| `__DATA.__objc_selrefs` | `0x638` | `0x640` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x340` | `0x338` | **`-0x8`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  Symbols:   219
-  CStrings:  444
+  Symbols:   218
+  CStrings:  445
Symbols:
- _showRecentSearchesDefaultsKey
Functions:
~ sub_134c : 988 -> 984
~ sub_1a54 -> sub_1a50 : 340 -> 336
~ sub_1f14 -> sub_1f0c : 656 -> 652
~ sub_2310 -> sub_2304 : 456 -> 452
~ sub_2710 -> sub_2700 : 520 -> 516
~ sub_34e8 -> sub_34d4 : 976 -> 972
~ sub_3b78 -> sub_3b60 : 1612 -> 1608
~ sub_41c4 -> sub_41a8 : 324 -> 400
~ sub_4414 -> sub_4444 : 172 -> 212
~ sub_44c0 -> sub_4518 : 344 -> 340
~ sub_4730 -> sub_4784 : 400 -> 396
~ sub_4cf8 -> sub_4d48 : 532 -> 528
~ sub_54c0 -> sub_550c : 848 -> 844
~ sub_6384 -> sub_63cc : 1124 -> 1140
CStrings:
+ "Finished history migration: deleted %zu items, %zu visits"
+ "Skipping history migration: endless history enabled"
+ "isEndlessHistoryEnabled"
- "Finished history migration"
- "ShowRecentSearches"
```
