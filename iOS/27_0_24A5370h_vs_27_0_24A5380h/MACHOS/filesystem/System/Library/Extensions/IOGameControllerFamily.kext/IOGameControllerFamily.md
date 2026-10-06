## IOGameControllerFamily

> `/System/Library/Extensions/IOGameControllerFamily.kext/IOGameControllerFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1abac` | `0x1ada8` | **`+0x1fc`** |
| `__TEXT.__os_log` | `0x1c4a` | `0x1c18` | **`-0x32`** |
| `__TEXT.__cstring` | `0x101c` | `0x104c` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-14.0.17.0.0
-  Functions: 672
-  Symbols:   779
-  CStrings:  298
+14.0.19.0.0
+  Functions: 673
+  Symbols:   780
+  CStrings:  299
Symbols:
+ __ZN17IOHIDEventService9metaClassE
+ __ZN22IOGCDynamicDeviceProbe9preflightEP11IOHIDDevice
- __ZZN22IOGCDynamicDeviceProbe5startEP9IOServiceE11_os_log_fmt_0
CStrings:
+ "GameControllerCategory"
+ "GameControllerEligible"
+ "GameControllerSupport"
- "GameControllerClass"
- "[%#010llx] <IOHIDDevice %#010llx> already probed."
```
