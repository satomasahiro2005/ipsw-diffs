## AXWatchRemoteScreenUIServer

> `/System/Library/AccessibilityBundles/AXWatchRemoteScreenUIServer.axuiservice/AXWatchRemoteScreenUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x915` | `0x975` | **`+0x60`** |
| `__TEXT.__text` | `0x2a60` | `0x2a94` | **`+0x34`** |
| `__TEXT.__cstring` | `0x13f` | `0x169` | **`+0x2a`** |
| `__DATA_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x138` | `0x140` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Symbols:   111
-  CStrings:  135
+  Symbols:   112
+  CStrings:  137
Symbols:
+ ___CFConstantStringClassReference
Functions:
~ sub_16a8 -> sub_1758 : 184 -> 236
CStrings:
+ "addContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:completion:"
+ "kAXTwiceRemoteScreenSceneClientIdentifier"
+ "setActiveSceneTrackingEnabled:forSceneClientIdentifier:"
- "addContentViewController:withUserInteractionEnabled:forService:context:userInterfaceStyle:completion:"
```
