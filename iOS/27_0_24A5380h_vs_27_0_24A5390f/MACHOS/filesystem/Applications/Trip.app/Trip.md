## Trip

> `/Applications/Trip.app/Trip`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bcdc` | `0x3c15c` | **`+0x480`** |
| `__TEXT.__swift5_typeref` | `0x76ba` | `0x758e` | **`-0x12c`** |
| `__TEXT.__auth_stubs` | `0x1f00` | `0x1f30` | **`+0x30`** |
| `__TEXT.__cstring` | `0xe77` | `0xea7` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1590` | `0x15b8` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1614` | `0x1634` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xf88` | `0xfa0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x430` | `0x448` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xb68` | `0xb80` | **`+0x18`** |
| `__DATA.__data` | `0x3370` | `0x3380` | **`+0x10`** |
| `__TEXT.__const` | `0x32d4` | `0x32c4` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-337.2.0.0.0
+340.0.0.0.0

-  Functions: 1144
-  Symbols:   929
-  CStrings:  461
+  Functions: 1147
+  Symbols:   932
+  CStrings:  462
Symbols:
+ _$s10CAFCombine13CAFObservablePAAE9publisher7Combine12AnyPublisherVyxs5NeverOGvg
+ _$s10CAFCombine17CAFTripObservableCAA13CAFObservableAAMc
+ _$s7SwiftUI4FontV11subheadlineACvgZ
+ _$s7SwiftUI4FontV6WeightV6mediumAEvgZ
+ _$s7SwiftUI4FontV6weightyA2C6WeightVF
+ _$sSo17OS_dispatch_queueC8DispatchE17SchedulerTimeTypeV6StrideV12millisecondsyAGSiFZ
+ _$sSo17OS_dispatch_queueC8DispatchE17SchedulerTimeTypeV6StrideVMa
- _$s10CAFCombine17CAFTripObservableC7Combine0C6ObjectAAMc
- _$s7Combine25ObservableObjectPublisherCMa
- _$sSo9NSRunLoopC10FoundationE17SchedulerTimeTypeV6StrideV12millisecondsyAGSiFZ
- _$sSo9NSRunLoopC10FoundationE17SchedulerTimeTypeV6StrideVMa
CStrings:
+ "[TripCard] - update skipped, missing CAFDimensionObservable"
+ "[Trip] clearing cardmodels."
- "[Trip] Not ready for carousel - 0 cards."
```
