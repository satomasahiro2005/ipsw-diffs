## com.apple.DiagnosticsSessionAvailibility

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/XPCServices/com.apple.DiagnosticsSessionAvailibility.xpc/com.apple.DiagnosticsSessionAvailibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbeb4` | `0xc040` | **`+0x18c`** |
| `__TEXT.__gcc_except_tab` | `0x460` | `0x508` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x468` | `0x4b0` | **`+0x48`** |
| `__DATA.__objc_const` | `0x3650` | `0x3670` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2120` | `0x2140` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x29ef` | `0x2a04` | **`+0x15`** |
| `__TEXT.__objc_methtype` | `0x76b` | `0x777` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xb48` | `0xb50` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x130` | `0x134` | **`+0x4`** |
| `__TEXT.__cstring` | `0xaea` | `0xaed` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1369.0.0.0.0
+1374.0.5.0.0

-  CStrings:  772
+  CStrings:  775
Functions:
~ sub_1000051ac : 436 -> 460
~ sub_100005460 -> sub_100005478 : 112 -> 184
~ sub_1000055bc -> sub_10000561c : 120 -> 180
~ sub_1000056e8 -> sub_100005784 : 136 -> 188
~ sub_100005b38 -> sub_100005c08 : 344 -> 372
~ sub_10000625c -> sub_100006348 : 1100 -> 1024
~ sub_1000066a8 -> sub_100006748 : 84 -> 180
~ sub_1000066fc -> sub_1000067fc : 392 -> 452
~ sub_100006884 -> sub_1000069c0 : 468 -> 540
~ sub_100006b68 -> sub_100006cec : 400 -> 396
~ sub_100006d84 -> sub_100006f04 : 116 -> 128
CStrings:
+ "@\"NSObject\""
+ "_stateLock"
+ "allValues"
```
