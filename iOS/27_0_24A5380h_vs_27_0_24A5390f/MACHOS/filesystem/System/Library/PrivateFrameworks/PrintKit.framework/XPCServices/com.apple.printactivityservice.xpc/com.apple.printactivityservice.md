## com.apple.printactivityservice

> `/System/Library/PrivateFrameworks/PrintKit.framework/XPCServices/com.apple.printactivityservice.xpc/com.apple.printactivityservice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x8cc` | `0x92c` | **`+0x60`** |
| `__TEXT.__text` | `0xb284` | `0xb2cc` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x29d` | `0x2ad` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x38c` | `0x398` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x600` | `0x608` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-44.1.0.0.0
+45.0.0.0.0

-  CStrings:  216
+  CStrings:  218
Functions:
~ sub_100002d60 : 692 -> 712
~ sub_100003014 -> sub_100003028 : 128 -> 132
~ sub_1000048c0 -> sub_1000048d8 : 1712 -> 1756
~ sub_100005174 -> sub_1000051b8 : 128 -> 132
CStrings:
+ "The printer software is not compatible with this device."
+ "com.apple.badarch-error"
```
