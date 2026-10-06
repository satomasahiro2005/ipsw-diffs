## DormancyCore

> `/System/Library/PrivateFrameworks/DormancyCore.framework/DormancyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a70c` | `0x2b4d8` | **`+0xdcc`** |
| `__DATA.__bss` | `0x6700` | `0x6880` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x5c1` | `0x741` | **`+0x180`** |
| `__TEXT.__const` | `0x3c1c` | `0x3d8c` | **`+0x170`** |
| `__TEXT.__swift5_fieldmd` | `0xc10` | `0xd08` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0x2570` | `0x2638` | **`+0xc8`** |
| `__AUTH.__data` | `0x6b8` | `0x750` | **`+0x98`** |
| `__TEXT.__cstring` | `0x7c2` | `0x842` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xbd0` | `0xc20` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0xd28` | `0xd6c` | **`+0x44`** |
| `__AUTH_CONST.__objc_const` | `0x8f0` | `0x930` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x820` | `0x850` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xdef` | `0xe0d` | **`+0x1e`** |
| `__DATA.__data` | `0x950` | `0x968` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x168` | `0x180` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1a8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x364` | `0x374` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x10c` | `0x114` | **`+0x8`** |

### Other Changes

```diff

-27.0.50.0.0
+27.0.54.0.0

-  Functions: 1183
-  Symbols:   581
-  CStrings:  114
+  Functions: 1209
+  Symbols:   588
+  CStrings:  118
Symbols:
+ ___swift_memcpy152_8
+ ___swift_memcpy248_8
+ _associated conformance 12DormancyCore0A7MonitorC6StatusO0B14AnalyticsValueOSHAASQ
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_retain_x8
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic _____ 12DormancyCore0A7MonitorC6StatusO0B14AnalyticsValueO
+ _symbolic _____ 12DormancyCore33FeatureReactivationAnalyticsEventV
+ _symbolic y______pc 12DormancyCore0A14AnalyticsEventP
- ___swift_memcpy144_8
- ___swift_memcpy240_8
- _swift_willThrowTypedImpl
CStrings:
+ "com.apple.dormancy.feature.reactivated"
+ "days_since_inactive"
+ "original_inactive_state"
+ "relativeBatteryImpact"
```
