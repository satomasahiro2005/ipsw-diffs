## Nexus

> `/System/Library/PrivateFrameworks/Nexus.framework/Nexus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x111910` | `0x111ca8` | **`+0x398`** |
| `__DATA.__bss` | `0x13450` | `0x13750` | **`+0x300`** |
| `__AUTH_CONST.__const` | `0x9860` | `0x99e8` | **`+0x188`** |
| `__TEXT.__const` | `0xc0e8` | `0xc258` | **`+0x170`** |
| `__TEXT.__swift5_fieldmd` | `0x2cd0` | `0x2d20` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3a28` | `0x3a68` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1f90` | `0x1fc8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x3218` | `0x3248` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x22a3` | `0x22d3` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x30ee` | `0x310a` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x6c0` | `0x6d8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x9c4` | `0x9dc` | **`+0x18`** |
| `__DATA.__data` | `0x2490` | `0x24a0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Other Changes

```diff

-900.37.0.0.0
+900.48.0.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 4975
-  Symbols:   1473
-  CStrings:  769
+  Functions: 4999
+  Symbols:   1476
+  CStrings:  774
Symbols:
+ _associated conformance 5Nexus10NXFeaturesOSHAASQ
+ _associated conformance 5Nexus8NXTXTKeyOSHAASQ
+ _symbolic _____ 5Nexus10NXFeaturesO
+ _symbolic _____ 5Nexus8NXTXTKeyO
- _swift_willThrowTypedImpl
CStrings:
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "connectionRouting"
+ "fl"
+ "ri"
+ "si"
```
