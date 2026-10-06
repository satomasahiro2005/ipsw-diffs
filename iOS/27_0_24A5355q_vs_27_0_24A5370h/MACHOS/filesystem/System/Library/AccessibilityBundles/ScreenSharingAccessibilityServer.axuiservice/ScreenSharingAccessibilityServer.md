## ScreenSharingAccessibilityServer

> `/System/Library/AccessibilityBundles/ScreenSharingAccessibilityServer.axuiservice/ScreenSharingAccessibilityServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e28` | `0x3dc0` | **`-0x68`** |
| `__TEXT.__auth_stubs` | `0x680` | `0x640` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x148` | `0x120` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x348` | `0x328` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x28` | `0x18` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x180` | `0x170` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x143` | `0x13b` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-114.38.11.1.0
+114.44.0.0.0

-  Functions: 65
-  Symbols:   92
+  Functions: 62
+  Symbols:   88
Symbols:
+ _objc_retain_x20
- _objc_release_x21
- _objc_retain_x28
- _swift_unknownObjectUnownedDestroy
- _swift_unknownObjectUnownedInit
- _swift_unknownObjectUnownedLoadStrong
```
