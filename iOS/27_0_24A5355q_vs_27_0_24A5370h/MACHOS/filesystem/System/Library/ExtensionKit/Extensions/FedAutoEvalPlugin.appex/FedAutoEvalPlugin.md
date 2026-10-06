## FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/FedAutoEvalPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x104d4` | `0x106e8` | **`+0x214`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xf30` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x7a0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x370` | `0x398` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x408` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x15` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA.__data` | `0x498` | `0x4a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
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

-  Functions: 220
-  Symbols:   113
-  CStrings:  38
+  Functions: 225
+  Symbols:   123
+  CStrings:  39
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_NSObject
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ _objc_autoreleaseReturnValue
+ _objc_release_x21
+ _swift_getObjCClassMetadata
+ _swift_retain_x19
+ _swift_retain_x2
CStrings:
+ "@\"NSDictionary\"8@?0"
```
