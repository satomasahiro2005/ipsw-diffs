## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e785c` | `0x1e7c00` | **`+0x3a4`** |
| `__AUTH_CONST.__cfstring` | `0xa840` | `0xa980` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x36b08` | `0x36c10` | **`+0x108`** |
| `__TEXT.__cstring` | `0x12bf4` | `0x12c74` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x1fd20` | `0x1fd98` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x73d0` | `0x7400` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e50` | `0x8e78` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x37b8` | `0x37d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x15f8` | `0x1608` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x16a0` | `0x16a4` | **`+0x4`** |

### Other Changes

```diff

-1329.0.0.0.0
+1334.0.0.0.0

-  Functions: 11850
-  Symbols:   18557
-  CStrings:  3722
+  Functions: 11863
+  Symbols:   18572
+  CStrings:  3732
Symbols:
+ +[NPKCommutePlanField supportsSecureCoding]
+ +[NPKDateRange supportsSecureCoding]
+ -[NPKCommutePlanField encodeWithCoder:]
+ -[NPKCommutePlanField initWithCoder:]
+ -[NPKDateRange encodeWithCoder:]
+ -[NPKDateRange initWithCoder:]
+ -[NPKExpressGymKitAvailabilityManager _conflictingPassUniqueID]
+ -[NPKExpressGymKitAvailabilityManager _isSimultaneousSinglePollingAndGymKitSupported]
+ -[NSArray(NanoPassKit) npk_isEqualToArray:comparingValuesFrom:]
+ -[PKPaymentTransaction(NanoPassKit) npk_isBillSplitPeerPaymentTransaction]
+ _OBJC_IVAR_$_NPKDateRange._dateStyle
+ __OBJC_$_CLASS_METHODS_NPKCommutePlanField
+ __OBJC_$_CLASS_PROP_LIST_NPKCommutePlanField
+ __OBJC_$_CLASS_PROP_LIST_NPKDateRange
+ ___54-[NPKExpressGymKitAvailabilityManager conflictingPass]_block_invoke
CStrings:
+ "dateStyle"
+ "detailLabel"
+ "details"
+ "expiryDate"
+ "hybridActivationInfo"
+ "isDeviceBound"
+ "isHybridPlan"
+ "rawCountValue"
+ "startDate"
+ "usageDateRange"
```
