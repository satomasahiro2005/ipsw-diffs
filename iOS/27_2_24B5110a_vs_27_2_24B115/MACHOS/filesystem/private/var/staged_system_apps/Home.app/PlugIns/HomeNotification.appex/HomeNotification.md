## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x267a0` | `0x2690c` | **`+0x16c`** |
| `__TEXT.__auth_stubs` | `0x1750` | `0x1770` | **`+0x20`** |
| `__TEXT.__cstring` | `0x17e0` | `0x1800` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xbb8` | `0xbc8` | **`+0x10`** |
| `__TEXT.__const` | `0x8f8` | `0x908` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1269.2.5.1.4
+1269.2.5.1.5

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   336
-  CStrings:  967
+  Symbols:   338
+  CStrings:  968
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_internalBuild
Functions:
~ sub_100026518 -> sub_100026558 : 824 -> 1188
CStrings:
+ "exclamationmark.bubble"
```
