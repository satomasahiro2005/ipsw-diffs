## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x53a9` | `0x53d5` | **`+0x2c`** |
| `__TEXT.__objc_methtype` | `0x2483` | `0x24a3` | **`+0x20`** |
| `__TEXT.__text` | `0x96c0` | `0x96ac` | **`-0x14`** |
| `__DATA.__objc_const` | `0x1618` | `0x1620` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1170` | `0x1178` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1374` | `0x137c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.18.10.4
+7625.1.20.10.3

-  CStrings:  1015
+  CStrings:  1017
Functions:
~ sub_100004174 : 1036 -> 1032
~ sub_10000975c -> sub_100009758 : 344 -> 340
~ sub_1000098b4 -> sub_1000098ac : 344 -> 340
~ sub_100009a0c -> sub_100009a00 : 328 -> 324
~ sub_100009b54 -> sub_100009b44 : 288 -> 284
CStrings:
+ "B24@0:8@\"_SFReaderController\"16"
+ "allowsBrowsingAssistantForReaderController:"
```
