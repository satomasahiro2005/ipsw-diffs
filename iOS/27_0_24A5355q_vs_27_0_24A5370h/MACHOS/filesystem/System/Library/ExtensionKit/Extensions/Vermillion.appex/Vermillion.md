## Vermillion

> `/System/Library/ExtensionKit/Extensions/Vermillion.appex/Vermillion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x109f8` | `0x10a40` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x731` | `0x759` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xcd8` | `0xcb0` | **`-0x28`** |
| `__TEXT.__objc_methtype` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xfc0` | `0xfb0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x7e8` | `0x7e0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4e8` | `0x4f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-26.0.0.0.0
+31.0.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 314
-  Symbols:   133
-  CStrings:  58
+  Functions: 317
+  Symbols:   135
+  CStrings:  59
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ _objc_autoreleaseReturnValue
- _OBJC_CLASS_$_HKUnit
CStrings:
+ "@\"NSDictionary\"8@?0"
```
