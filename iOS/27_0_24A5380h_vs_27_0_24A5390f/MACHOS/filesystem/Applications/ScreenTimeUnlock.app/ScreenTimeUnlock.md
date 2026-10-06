## ScreenTimeUnlock

> `/Applications/ScreenTimeUnlock.app/ScreenTimeUnlock`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2084` | `0x21bc` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0xf59` | `0xff4` | **`+0x9b`** |
| `__TEXT.__objc_stubs` | `0xb40` | `0xba0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2f7` | `0x336` | **`+0x3f`** |
| `__DATA.__objc_const` | `0x668` | `0x698` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x290` | `0x2b0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4a0` | `0x4b8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x524` | `0x53c` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x28` | `0x2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 77
-  Symbols:   79
-  CStrings:  270
+  Functions: 79
+  Symbols:   82
+  CStrings:  276
Symbols:
+ _STRemoteAlertConfigurationContextKeyUserInterfaceStyle
+ _objc_opt_isKindOfClass
+ _objc_release_x27
CStrings:
+ "Applying requested user interface style %ld to passcode window"
+ "Tq,N,V_requestedUserInterfaceStyle"
+ "_requestedUserInterfaceStyle"
+ "requestedUserInterfaceStyle"
+ "setOverrideUserInterfaceStyle:"
+ "setRequestedUserInterfaceStyle:"
```
