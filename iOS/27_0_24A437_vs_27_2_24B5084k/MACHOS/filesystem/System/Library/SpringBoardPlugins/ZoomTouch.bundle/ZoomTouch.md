## ZoomTouch

> `/System/Library/SpringBoardPlugins/ZoomTouch.bundle/ZoomTouch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40a4` | `0x41a4` | **`+0x100`** |
| `__TEXT.__oslogstring` | `—` | `0x72` | **`+0x72`** |
| `__TEXT.__auth_stubs` | `0x490` | `0x4c0` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xdc0` | `0xde0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x270` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x508` | `0x510` | **`+0x8`** |
| `__TEXT.__const` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x10b4` | `0x10bb` | **`+0x7`** |
| `__TEXT.__cstring` | `0x38f` | `0x394` | **`+0x5`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-909.1.0.0.0
+913.3.0.0.0

-  Functions: 109
-  Symbols:   424
-  CStrings:  286
+  Functions: 110
+  Symbols:   429
+  CStrings:  289
Symbols:
+ _ZOOMLogEvents
+ _ZOTReportUnresolvedDisplay
+ __os_log_error_impl
+ _objc_msgSend$length
+ _os_log_type_enabled
Functions:
+ _ZOTReportUnresolvedDisplay
CStrings:
+ "%{public}@: no delegate for displayID %u, so zoom can't act on gestures from that display. Registered: %{public}@"
+ "length"
+ "none"
```
