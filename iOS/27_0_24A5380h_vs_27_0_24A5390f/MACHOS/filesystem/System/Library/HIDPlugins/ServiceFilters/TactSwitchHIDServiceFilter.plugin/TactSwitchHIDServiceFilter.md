## TactSwitchHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/TactSwitchHIDServiceFilter.plugin/TactSwitchHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29cc` | `0x2b54` | **`+0x188`** |
| `__TEXT.__oslogstring` | `0x415` | `0x482` | **`+0x6d`** |
| `__TEXT.__gcc_except_tab` | `0x334` | `0x37c` | **`+0x48`** |
| `__TEXT.__cstring` | `0x360` | `0x38a` | **`+0x2a`** |
| `__TEXT.__auth_stubs` | `0x340` | `0x350` | **`+0x10`** |
| `__TEXT.__const` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.40.0.0.0
+10100.40.2.0.0

-  Symbols:   275
-  CStrings:  266
+  Symbols:   276
+  CStrings:  269
Symbols:
+ _MGIsDeviceOfType
+ _MGIsDeviceOneOfType
+ _dispatch_queue_create
- _MGGetProductType
- _objc_release_x25
Functions:
~ +[TactSwitchHIDServiceFilter matchService:options:score:] : 204 -> 384
~ -[TouchSensitiveButtonHIDService initWithLog:usagePage:usage:streamCallback:algsInterface:] : 1676 -> 1888
CStrings:
+ "Matched TactSwitchServiceFilter successfully"
+ "TouchSensitiveButtonHIDService: Configured for async operations"
+ "com.apple.multitouch.touchSensitiveButton"
```
