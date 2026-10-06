## OBCEngagePlugin

> `/System/Library/ExtensionKit/Extensions/OBCEngagePlugin.appex/OBCEngagePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x119d0` | `0x11bb8` | **`+0x1e8`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xe80` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x778` | `0x7a0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x748` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x22` | `0x42` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x438` | `0x450` | **`+0x18`** |
| `__DATA.__data` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x190` | `0x198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-26.0.0.0.0
+31.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 293
-  Symbols:   120
-  CStrings:  90
+  Functions: 298
+  Symbols:   125
+  CStrings:  91
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ _objc_autoreleaseReturnValue
+ _objc_release_x28
+ _swift_getObjCClassMetadata
CStrings:
+ "@\"NSDictionary\"8@?0"
```
