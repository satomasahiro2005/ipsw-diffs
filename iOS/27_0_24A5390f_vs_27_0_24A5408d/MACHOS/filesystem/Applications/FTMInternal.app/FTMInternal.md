## FTMInternal

> `/Applications/FTMInternal.app/FTMInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b4f5c` | `0x2b8c00` | **`+0x3ca4`** |
| `__DATA_CONST.__const` | `0xb0a8` | `0xb368` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x10fc0` | `0x11220` | **`+0x260`** |
| `__TEXT.__eh_frame` | `0x2e28` | `0x2f00` | **`+0xd8`** |
| `__TEXT.__objc_stubs` | `0x8920` | `0x8980` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x5718` | `0x5760` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x10c0` | `0x1100` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x34c0` | `0x34e0` | **`+0x20`** |
| `__DATA.__common` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA.__data` | `0x6a38` | `0x6a48` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1a70` | `0x1a80` | **`+0x10`** |
| `__TEXT.__const` | `0x91e4` | `0x91d4` | **`-0x10`** |
| `__DATA.__objc_data` | `0x69a0` | `0x69a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xb68` | `0xb70` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x404c` | `0x4054` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-39.1.0.0.0
+39.2.0.0.0

-  Functions: 13957
-  Symbols:   1455
-  CStrings:  11439
+  Functions: 13979
+  Symbols:   1458
+  CStrings:  11447
Symbols:
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ __swiftEmptySetSingleton
+ _swift_release_x3
CStrings:
+ "AWD RSRQ populated: LTE subsId=%d attr=%{public}s value=%{public}s"
+ "AWD populated: 5G subsId=%d attr=%{public}s value=%{public}s"
+ "Appdelegate - applicationDidEnterBackground ABMWrapper.sharedInstance  returned nil"
+ "SwiftUI Scene Phase - Background ABMWrapper.sharedInstance  returned nil"
+ "SwiftUI Scene Phase - Background successfully removed AWDConfig"
+ "SwiftUI Scene Phase - Inactive ABMWrapper.sharedInstance  returned nil"
+ "SwiftUI Scene Phase - Inactive successfully removed AWDConfig"
+ "successfully started listening ABM applicationDidBecomeActive"
+ "syncMetricModels removeAll2: remaining count=%d awdPreserved=%d"
- "syncMetricModels removeAll2: remaining count=%d"
```
