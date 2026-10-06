## NightingaleTraining

> `/System/Library/PrivateFrameworks/NightingaleTraining.framework/NightingaleTraining`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdb2b4` | `0xdbc24` | **`+0x970`** |
| `__TEXT.__eh_frame` | `0x37dc` | `0x3cdc` | **`+0x500`** |
| `__TEXT.__unwind_info` | `0x2ba0` | `0x2cb8` | **`+0x118`** |
| `__TEXT.__const` | `0x26ed` | `0x27dd` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x120` | `0x1a8` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x3428` | `0x33b0` | **`-0x78`** |
| `__TEXT.__swift5_typeref` | `0x1261` | `0x12c1` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x784` | `0x73c` | **`-0x48`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xdc` | **`+0x34`** |
| `__DATA.__data` | `0xa00` | `0xa30` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0xa0` | `0xcc` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0xcf8` | `0xce8` | **`-0x10`** |
| `__DATA.__bss` | `0x1510` | `0x1520` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4c0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x138` | `0x130` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb78` | `0xb70` | **`-0x8`** |

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 2904
-  Symbols:   2841
+  Functions: 2961
+  Symbols:   2843
Symbols:
+ _keypath_get_selector_startDate
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_getKeyPath
+ _symbolic SfSg_A2At
+ _symbolic So8HKSampleC
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ySo8HKSampleCG 10Foundation14SortDescriptorV
+ _symbolic _____ySo8HKSampleCG 9HealthKit17HKSamplePredicateV
+ _symbolic _____ySo8HKSampleCG 9HealthKit23HKSampleQueryDescriptorV
+ _symbolic _____y_____ySo8HKSampleCGG s23_ContiguousArrayStorageC 10Foundation14SortDescriptorV
+ _symbolic _____y_____ySo8HKSampleCGG s23_ContiguousArrayStorageC 9HealthKit17HKSamplePredicateV
- _HKSampleSortIdentifierStartDate
- _OBJC_CLASS_$_NSSortDescriptor
- ___swift__destructor
- __swift_FORCE_LOAD_$_swiftAppleArchive
- __swift_FORCE_LOAD_$_swiftAppleArchive_$_NightingaleTraining
- _dispatch_group_create
- _dispatch_group_enter
- _dispatch_group_leave
- _objc_retain_x28
- _symbolic So17OS_dispatch_groupC
- _symbolic ______pSg______pSgIegng_ 19NightingaleTraining21HealthDataQueryResultP s5ErrorP
```
