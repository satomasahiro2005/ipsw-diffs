## TouchSensitiveButtonHIDService

> `/System/Library/HIDPlugins/ServicePlugins/TouchSensitiveButtonHIDService.plugin/TouchSensitiveButtonHIDService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ef0` | `0x2fc4` | **`+0xd4`** |
| `__TEXT.__gcc_except_tab` | `0x33c` | `0x384` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x469` | `0x4a9` | **`+0x40`** |
| `__TEXT.__cstring` | `0x30c` | `0x336` | **`+0x2a`** |
| `__TEXT.__const` | `0xd0` | `0xe4` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.40.0.0.0
+10100.40.2.0.0

-  CStrings:  263
+  CStrings:  265
Symbols:
+ _MGIsDeviceOfType
+ _dispatch_queue_create
- _MGGetProductType
- _objc_release_x25
Functions:
~ -[TouchSensitiveButtonHIDService initWithLog:usagePage:usage:streamCallback:algsInterface:] : 1676 -> 1888
CStrings:
+ "TouchSensitiveButtonHIDService: Configured for async operations"
+ "com.apple.multitouch.touchSensitiveButton"
```
