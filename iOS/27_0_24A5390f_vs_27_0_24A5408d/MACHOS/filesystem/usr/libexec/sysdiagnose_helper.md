## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2523c` | `0x252f4` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x97dd` | `0x9861` | **`+0x84`** |
| `__DATA_CONST.__cfstring` | `0x1da0` | `0x1e00` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x110` | `0x170` | **`+0x60`** |
| `__DATA_CONST.__objc_arrayobj` | `0x78` | `0xc0` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x17e0` | `0x17c0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x1744` | `0x1735` | **`-0xf`** |
| `__DATA.__objc_selrefs` | `0x660` | `0x658` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1598.0.4.0.0
+1598.0.6.0.0

-  CStrings:  2190
+  CStrings:  2194
Functions:
~ sub_10000852c : 880 -> 992
~ sub_1000120a8 -> sub_100012118 : 68076 -> 68148
CStrings:
+ "BatteryHealth"
+ "BatteryPacks"
+ "Power source %d health info:\n%@\n"
+ "Power source %u pack %u health info:\n%@\n"
+ "arrayByAddingObjectsFromArray:"
+ "dictionaryWithValuesForKeys:"
+ "gcSlowInlineWritesMigration"
+ "gcSlowInlineWritesTotal"
+ "objectAtIndexedSubscript:"
- "Battery %d health info:\n%@\n"
- "addObjectsFromArray:"
- "arrayWithObjects:"
- "dictionaryWithObjects:forKeys:"
- "objectsForKeys:notFoundMarker:"
```
