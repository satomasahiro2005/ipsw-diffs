## AVCPlugin

> `/System/Library/ExtensionKit/Extensions/AVCPlugin.appex/AVCPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15818` | `0x15a74` | **`+0x25c`** |
| `__TEXT.__auth_stubs` | `0x1130` | `0x11a0` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x8a0` | `0x8d8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x960` | `0x988` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x24` | **`+0x23`** |
| `__TEXT.__eh_frame` | `0xeb8` | `0xed8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5f0` | `0x608` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x230` | `0x240` | **`+0x10`** |
| `__TEXT.__const` | `0xe38` | `0xe48` | **`+0x10`** |
| `__DATA.__data` | `0x610` | `0x618` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
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

-  Functions: 388
-  Symbols:   132
-  CStrings:  49
+  Functions: 393
+  Symbols:   141
+  CStrings:  50
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ _objc_autoreleaseReturnValue
+ _objc_release_x21
+ _swift_retain_x19
+ _swift_retain_x2
CStrings:
+ "@\"NSDictionary\"8@?0"
```
