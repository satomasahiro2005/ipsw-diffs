## SleepLockScreen

> `/Applications/SleepLockScreen.app/SleepLockScreen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe398` | `0xe374` | **`-0x24`** |
| `__DATA_CONST.__const` | `0x6a0` | `0x6b0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0xd60` | **`-0x10`** |
| `__DATA.__objc_data` | `0x498` | `0x490` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x6c0` | `0x6b8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x454` | `0x44c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

-  Symbols:   336
+  Symbols:   337
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftMLCompute
- _$s13SleepHealthUI22LockScreenContentModelC20didInteractWithAlarmyyAA0K0VSgFTj
Functions:
~ sub_1000028b0 -> sub_100002940 : 552 -> 516
```
