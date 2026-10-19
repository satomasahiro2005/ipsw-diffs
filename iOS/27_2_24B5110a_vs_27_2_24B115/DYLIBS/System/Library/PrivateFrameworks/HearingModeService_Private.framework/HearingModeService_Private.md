## HearingModeService_Private

> `/System/Library/PrivateFrameworks/HearingModeService_Private.framework/HearingModeService_Private`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12cd8` | `0x12f98` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x51fa` | `0x5351` | **`+0x157`** |
| `__DATA_CONST.__const` | `0x858` | `0x878` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xed0` | `0xee8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc84` | `0xc8c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5e8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 462
-  Symbols:   664
-  CStrings:  458
+  Functions: 467
+  Symbols:   666
+  CStrings:  463
Symbols:
+ -[HMDeviceManager _hearingAssistEligibleViaTINDomain]
+ GCC_except_table108
+ _OBJC_CLASS_$_OSEligibilityQuery
- GCC_except_table107
CStrings:
+ "### OSEligibility TIN domain query failed: %@"
+ "-[HMDeviceManager _hearingAssistEligibleViaTINDomain]"
+ "HearingAidV2 region status upgraded to Supported via OSEligibility TIN domain (HealthKit reported %s)"
+ "HearingAssist region status upgraded to Supported via OSEligibility TIN domain (HealthKit reported %s)"
+ "OSEligibility TIN domain eligible: %d"
```
