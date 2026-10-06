## PlugInKitDaemon

> `/System/Library/PrivateFrameworks/PlugInKitDaemon.framework/PlugInKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17848` | `0x17b20` | **`+0x2d8`** |
| `__TEXT.__cstring` | `0x138c` | `0x13f9` | **`+0x6d`** |
| `__TEXT.__oslogstring` | `0x2c24` | `0x2c73` | **`+0x4f`** |
| `__DATA_CONST.__const` | `0x578` | `0x5a0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x480` | `0x488` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4c0` | `0x4c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-512.0.0.0.0
+513.0.0.0.0

-  Functions: 437
-  Symbols:   1368
-  CStrings:  1105
+  Functions: 439
+  Symbols:   1370
+  CStrings:  1108
Symbols:
+ GCC_except_table38
+ _PKDExcludedExtensionPointsKey
+ ___block_descriptor_40_e8_32s_e26_B32?0"PKDPlugIn"8Q16^B24ls32l8
- GCC_except_table34
CStrings:
+ "B32@?0@\"PKDPlugIn\"8Q16^B24"
+ "excludedExtensionPoints is only supported for application-scope lockdown requests"
+ "sparing %lu plug-in(s) from lockdown for excluded extension points: %{public}@"
```
