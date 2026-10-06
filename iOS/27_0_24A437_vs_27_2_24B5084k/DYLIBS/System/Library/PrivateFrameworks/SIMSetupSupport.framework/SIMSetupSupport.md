## SIMSetupSupport

> `/System/Library/PrivateFrameworks/SIMSetupSupport.framework/SIMSetupSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6494` | `0xe6b10` | **`+0x67c`** |
| `__TEXT.__cstring` | `0x17aa0` | `0x17a03` | **`-0x9d`** |
| `__AUTH_CONST.__cfstring` | `0xae60` | `0xae00` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x8c70` | `0x8ca3` | **`+0x33`** |
| `__TEXT.__objc_methlist` | `0xc7ec` | `0xc81c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3080` | `0x30a8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x4f8d8` | `0x4f8b8` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5f58` | `0x5f78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc10` | `0xc18` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1358` | `0x1354` | **`-0x4`** |

### Other Changes

```diff

-973.1.0.0.0
+979.0.0.0.0

-  Functions: 4970
-  Symbols:   7994
-  CStrings:  3151
+  Functions: 4977
+  Symbols:   7999
+  CStrings:  3149
Symbols:
+ -[TSDeviceInfoViewController viewWillAppear:]
+ -[TSPRXIdentityShareViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[TSPRXSIMTransferCompleteViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[TSSecureIntentGestureViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ _OBJC_CLASS_$_NSListFormatter
+ _OBJC_IVAR_$_SSVisitStoreViewController._carriers
+ ___87-[TSPRXIdentityShareViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___90-[TSSecureIntentGestureViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___93-[TSPRXSIMTransferCompleteViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
- GCC_except_table22
- GCC_except_table35
- _OBJC_IVAR_$_SSVisitStoreViewController._carrier
- _OBJC_IVAR_$_SSVisitStoreViewController._plan
CStrings:
+ "Not signed into iCloud. Skipping Quick Switch. @%s"
+ "QS_BLOCKER_SOFTWARE_UPDATE_DETAIL_OTHER"
+ "QS_BLOCKER_SOFTWARE_UPDATE_DETAIL_SELF"
+ "QS_TRANSPORT_FAILURE_DETAILS_BUDDY"
+ "QS_TRANSPORT_FAILURE_DETAILS_POSTBUDDY"
+ "QS_TRANSPORT_FAILURE_WLAN_DETAILS_BUDDY"
+ "QS_TRANSPORT_FAILURE_WLAN_DETAILS_POSTBUDDY"
- "QS_BLOCKER_SOFTWARE_UPDATE_DETAIL"
- "QS_TRANSPORT_FAILURE_DETAILS_BUDDY_%@"
- "QS_TRANSPORT_FAILURE_DETAILS_BUDDY_NO_NAME"
- "QS_TRANSPORT_FAILURE_DETAILS_POSTBUDDY_%@"
- "QS_TRANSPORT_FAILURE_DETAILS_POSTBUDDY_NO_NAME"
- "QS_TRANSPORT_FAILURE_WLAN_DETAILS_BUDDY_%@"
- "QS_TRANSPORT_FAILURE_WLAN_DETAILS_BUDDY_NO_NAME"
- "QS_TRANSPORT_FAILURE_WLAN_DETAILS_POSTBUDDY_%@"
- "QS_TRANSPORT_FAILURE_WLAN_DETAILS_POSTBUDDY_NO_NAME"
```
