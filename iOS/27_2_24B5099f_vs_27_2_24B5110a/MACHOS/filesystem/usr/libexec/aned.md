## aned

> `/usr/libexec/aned`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d624` | `0x7cef4` | **`-0x730`** |
| `__TEXT.__gcc_except_tab` | `0x61b4` | `0x604c` | **`-0x168`** |
| `__TEXT.__oslogstring` | `0x6d61` | `0x6cd3` | **`-0x8e`** |
| `__DATA_CONST.__const` | `0x2b68` | `0x2b18` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x1bc0` | `0x1b90` | **`-0x30`** |
| `__TEXT.__cstring` | `0x5cfc` | `0x5cde` | **`-0x1e`** |
| `__TEXT.__auth_stubs` | `0xf90` | `0xf80` | **`-0x10`** |
| `__DATA.__bss` | `0xa8` | `0xa0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x7e0` | `0x7d8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-382.101.0.0.0
+382.101.2.0.0

-  Symbols:   4178
-  CStrings:  1757
+  Symbols:   4173
+  CStrings:  1752
Symbols:
- __43+[_ANEStorageHelper memoryMapWeightAtPath:]_block_invoke
- __72+[_ANEStorageHelper memoryMapModelAtPath:isPrecompiled:modelAttributes:]_block_invoke
- ___block_descriptor_192_e8_32r_e5_v8?0lr32l8
- ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
- _fcntl
CStrings:
- "%@: fcntl(F_RDADVISE). errno=%d : %s"
- "_ANED_MODEL_READ_ADVISE"
- "_ANED_WEIGHT_READ_ADVISE"
- "com.apple.aned.storageAsyncIO"
- "size=%d\n %{public, signpost.description:begin_time}llu "
```
