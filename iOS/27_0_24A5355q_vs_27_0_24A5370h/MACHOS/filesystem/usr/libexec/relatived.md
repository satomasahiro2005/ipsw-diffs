## relatived

> `/usr/libexec/relatived`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13db8` | `0x13e34` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x212c` | `0x218b` | **`+0x5f`** |
| `__TEXT.__objc_methname` | `0x3c67` | `0x3c88` | **`+0x21`** |
| `__TEXT.__objc_stubs` | `0x3200` | `0x3220` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1160` | `0x1178` | **`+0x18`** |
| `__DATA.__objc_const` | `0x2a48` | `0x2a58` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xdd0` | `0xdd8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x318` | `0x320` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x638` | `0x640` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1168` | `0x1169` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-375.0.0.0.0
+374.0.6.0.0

-  Functions: 580
-  Symbols:   266
-  CStrings:  1093
+  Functions: 583
+  Symbols:   267
+  CStrings:  1095
Symbols:
+ _kCMHeadphoneAvailableReferenceFramesKey
CStrings:
+ "[RMHeadphoneStatusProvider] connected=%{public}d, availableAttitudeReferenceFrames=%{public}lx"
+ "availableAttitudeReferenceFrames"
+ "kRMConnectionRequestStreamingKey"
- "kRMConnectionRequestSteamingKey"
```
