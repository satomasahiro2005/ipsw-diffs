## AXFloatingUIKeyboardUIServer

> `/System/Library/AccessibilityBundles/AXFloatingUIKeyboardUIServer.axuiservice/AXFloatingUIKeyboardUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf74` | `0x16b0` | **`+0x73c`** |
| `__TEXT.__cstring` | `0x93` | `0x123` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x340` | `0x3b0` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x1a8` | `0x1e0` | **`+0x38`** |
| `__DATA.__data` | `0x120` | `0x140` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__const` | `0x7a` | `0x92` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 29
-  Symbols:   69
-  CStrings:  87
+  Functions: 30
+  Symbols:   72
+  CStrings:  89
Symbols:
+ _objc_release_x19
+ _objc_release_x21
+ _swift_release_x22
+ _swift_release_x26
- _objc_release_x24
CStrings:
+ "textInputDidBegin from pid %d bundle %{public}@ scene %{public}@"
+ "textInputDidBegin missing pid, payload: %{public}@"
```
