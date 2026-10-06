## SOSBuddy

> `/Applications/SOSBuddy.app/SOSBuddy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2af02c` | `0x2af074` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1178` | `0x1168` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x43a0` | `0x4390` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x21d8` | `0x21d0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3520.0.0.0.0
+3522.0.0.0.0

-  Symbols:   2062
+  Symbols:   2059
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
Functions:
~ sub_10007b7c0 : 344 -> 340
~ sub_1000e002c -> sub_1000e0028 : 1504 -> 1492
~ sub_100114f90 -> sub_100114f80 : 580 -> 576
~ sub_100115a34 -> sub_100115a20 : 412 -> 408
~ sub_10012db58 -> sub_10012db40 : 1400 -> 1380
~ sub_10012f08c -> sub_10012f060 : 620 -> 616
~ sub_1001cc190 -> sub_1001cc160 : 960 -> 956
~ sub_1001ccb50 -> sub_1001ccb1c : 344 -> 324
~ sub_1001cce90 -> sub_1001cce48 : 284 -> 364
~ sub_100231bdc -> sub_100231be4 : 5300 -> 5292
~ sub_10024063c : 1816 -> 1888
~ sub_10028dc40 -> sub_10028dc88 : 132 -> 984
~ sub_10028dcc4 -> sub_10028e060 : 512 -> 132
~ sub_10028dec4 -> sub_10028e0e4 : 984 -> 512
```
