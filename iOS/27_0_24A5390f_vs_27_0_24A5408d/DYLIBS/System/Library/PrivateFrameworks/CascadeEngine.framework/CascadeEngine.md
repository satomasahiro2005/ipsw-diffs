## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6399c` | `0x645f0` | **`+0xc54`** |
| `__TEXT.__oslogstring` | `0x6a29` | `0x6b49` | **`+0x120`** |
| `__TEXT.__cstring` | `0x2a64` | `0x2b64` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x1980` | `0x1a20` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x50d8` | `0x5148` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a08` | `0x1a68` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xe88` | `0xee0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1eac` | `0x1ef4` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x6c0` | `0x6f4` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x1558` | `0x1588` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x2b8` | `0x2c4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xee0` | `0xee8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x678` | `0x680` | **`+0x8`** |
| `__TEXT.__ustring` | `0x7c` | `0x84` | **`+0x8`** |

### Other Changes

```diff

-247.0.1.0.0
+250.0.0.1.0

-  Functions: 2264
-  Symbols:   2056
-  CStrings:  822
+  Functions: 2278
+  Symbols:   2075
+  CStrings:  830
Symbols:
+ -[CCDonationItemComponents deletedFieldTypes]
+ -[CCDonationItemComponents initWithSetKey:content:metaContent:isPatch:deletedFieldTypes:]
+ -[CCDonationServiceConnection _beginSetDonationWithItemType:encodedDescriptors:sourceVersion:sourceValidity:options:reply:]
+ -[CCDonationServiceConnection _drainNextPendingDonation]
+ -[CCDonationServiceConnection abortInFlightDonationOnConnectionInvalidation]
+ -[CCRapportSyncEngine descriptorsMatchEngineDomain:]
+ -[CCRapportSyncEngine syncErrorCodeFromLocalDeviceSiteError:]
+ -[CCSetStoreUpdateServiceExported abortInFlightDonationOnInvalidation]
+ -[CCSetVersionedMergeable localDeviceSiteAddingExpirationDate:error:]
+ GCC_except_table16
+ GCC_except_table28
+ GCC_except_table37
+ GCC_except_table42
+ GCC_except_table6
+ GCC_except_table9
+ _CCSetErrorForDatabaseError
+ _OBJC_CLASS_$_CCItemDeletedFieldTypes
+ _OBJC_IVAR_$_CCDonationItemComponents._deletedFieldTypes
+ _OBJC_IVAR_$_CCDonationServiceConnection._connectionInvalidated
+ _OBJC_IVAR_$_CCDonationServiceConnection._pendingDonations
+ ___61-[CCDonationServiceConnection _finalizeForStatus:replyBlock:]_block_invoke
+ ___70-[CCSetStoreUpdateServiceExported abortInFlightDonationOnInvalidation]_block_invoke
+ ___76-[CCDonationServiceConnection abortInFlightDonationOnConnectionInvalidation]_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_76_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_84_e8_32s40s48s56s64bs72w_e5_v8?0lw72l8s64l8s32l8s40l8s48l8s56l8
- -[CCDonationItemComponents initWithSetKey:content:metaContent:isPatch:]
- -[CCSetVersionedMergeable localDeviceSiteAddingExpirationDate:]
- GCC_except_table14
- GCC_except_table24
- GCC_except_table35
- GCC_except_table41
- ___block_descriptor_76_e8_32s40s48s56s64bs_e5_v8?0ls32l8s64l8s40l8s48l8s56l8
CStrings:
+ "%@: Client connection invalidated with a donation in progress; aborting"
+ "%@: Donation already in progress; enqueuing behind %lu pending donation(s): %@"
+ "%@: Donation terminated; dequeuing next pending donation (%lu will remain queued behind it)"
+ "%@: Local source updating set with priors: %@"
+ "%@: Refusing donation: %@"
+ "Client XPC connection invalidated"
+ "Connection deallocated before queued donation could start: %@"
+ "Connection invalidated before donation could start: %@"
+ "Donation already in progress (%@) — refusing no-wait donation: %@"
+ "Requested set (%@) is not served by this sync engine's domain"
+ "Requested set's partition domain does not match this sync engine's domain"
- "%@: Local source updating set"
- "Donation already in progress (%@) — refusing new donation: %@"
- "Failed to get local device site"
```
