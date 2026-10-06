## coresymbolicationd

> `/System/Library/PrivateFrameworks/CoreSymbolication.framework/coresymbolicationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8508` | `0x8884` | **`+0x37c`** |
| `__TEXT.__cstring` | `0x5f1` | `0x656` | **`+0x65`** |
| `__TEXT.__gcc_except_tab` | `0x6f8` | `0x750` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x3f8` | `0x428` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x418` | `0x428` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__const`

### Other Changes

```diff

-64578.77.1.0.0
+64578.82.1.0.0

-  Functions: 171
-  Symbols:   421
-  CStrings:  59
+  Functions: 173
+  Symbols:   425
+  CStrings:  68
Symbols:
+ GCC_except_table49
+ GCC_except_table50
+ GCC_except_table55
+ GCC_except_table56
+ __Z28encode_mmap_archive_metadataPK12TMMapArchive
+ ____ZL45coresymbolicationd_read_mmap_archive_metadata13XPCDictionaryRS_ji_block_invoke
- GCC_except_table47
- GCC_except_table48
CStrings:
+ "cpu_subtype"
+ "cpu_type"
+ "flags"
+ "has_dsym"
+ "metadata"
+ "region_count"
+ "source_info_count"
+ "symbol_count"
+ "text_length"
```
