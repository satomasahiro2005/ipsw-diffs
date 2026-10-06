## Compass

> `/private/var/staged_system_apps/Compass.app/Compass`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce20` | `0xd098` | **`+0x278`** |
| `__TEXT.__objc_stubs` | `0x2ae0` | `0x2b60` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x3a2c` | `0x3a9c` | **`+0x70`** |
| `__DATA.__objc_const` | `0x2b50` | `0x2b90` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xff0` | `0x1010` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1442` | `0x1453` | **`+0x11`** |
| `__DATA.__objc_ivar` | `0x144` | `0x14c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x298` | `0x2a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-366.30.6.4.1
+367.30.6.12.6

-  Symbols:   260
-  CStrings:  892
+  Symbols:   261
+  CStrings:  899
Symbols:
+ _OBJC_CLASS_$_UILayoutGuide
Functions:
~ sub_100002fcc : 2756 -> 2800
~ sub_1000040d8 -> sub_100004104 : 1492 -> 2040
~ sub_10000b1cc -> sub_10000b41c : 544 -> 584
CStrings:
+ "@\"UILayoutGuide\""
+ "_contentLayoutGuide"
+ "_numericGroup"
+ "addLayoutGuide:"
+ "effectiveUserInterfaceLayoutDirection"
+ "leftAnchor"
+ "rightAnchor"
```
