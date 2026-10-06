## SILManager

> `/System/Library/PrivateFrameworks/SILManager.framework/SILManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d52c` | `0x5e210` | **`+0xce4`** |
| `__TEXT.__oslogstring` | `0x2264` | `0x23a4` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x2490` | `0x24d0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2098` | `0x20c8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2577` | `0x2597` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x10b7` | `0x10d7` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1578` | `0x1590` | **`+0x18`** |
| `__TEXT.__const` | `0x4bbc` | `0x4bac` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x728` | `0x738` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x130` | `0x140` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xcc0` | `0xcc8` | **`+0x8`** |
| `__DATA.__data` | `0x548` | `0x550` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x470` | `0x478` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0xa78` | `0xa80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1368` | `0x1370` | **`+0x8`** |

### Other Changes

```diff

-67.5.0.0.0
+67.7.0.0.0

-  Functions: 1665
-  Symbols:   4100
-  CStrings:  476
+  Functions: 1667
+  Symbols:   4103
+  CStrings:  480
Symbols:
+ _$s10SILManager14SILConstraintsC20unsteadyRampSegmentss5UInt8VvgTo
+ _$s10SILManager14SILConstraintsC20unsteadyRampSegmentss5UInt8VvpWvd
+ _$ss22KeyedDecodingContainerV15decodeIfPresent_6forKeys5UInt8VSgAFm_xtKF
CStrings:
+ "  unsteadyRampSegments: %hhu"
+ "SILManager ID %hhu: Indicator %ld region %ld below %ld%% ramp-progress floor at %ss (opacity %f < %f || size %f < %f)"
+ "SILManager ID %hhu: Indicator %ld region %ld ramp progress: segment %ld/%hhu (%ld%%) at %ss — opacity %f (floor %f, goal %f), size %f (floor %f, goal %f)"
+ "unsteadyRampSegments"
```
