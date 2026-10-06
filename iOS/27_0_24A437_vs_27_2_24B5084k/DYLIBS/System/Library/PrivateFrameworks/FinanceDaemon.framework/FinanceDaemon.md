## FinanceDaemon

> `/System/Library/PrivateFrameworks/FinanceDaemon.framework/FinanceDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48c3ac` | `0x490700` | **`+0x4354`** |
| `__TEXT.__oslogstring` | `0x14592` | `0x149e2` | **`+0x450`** |
| `__AUTH.__data` | `0x8d60` | `0x8fc0` | **`+0x260`** |
| `__AUTH_CONST.__const` | `0x10888` | `0x10768` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x263f0` | `0x26504` | **`+0x114`** |
| `__DATA.__bss` | `0x142e0` | `0x143e0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x7118` | `0x71f0` | **`+0xd8`** |
| `__TEXT.__const` | `0x17cf2` | `0x17dc2` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x9450` | `0x94f8` | **`+0xa8`** |
| `__DATA.__data` | `0x5170` | `0x5210` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x817c` | `0x8218` | **`+0x9c`** |
| `__TEXT.__unwind_info` | `0xc240` | `0xc2c8` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x837c` | `0x8400` | **`+0x84`** |
| `__TEXT.__cstring` | `0xcc55` | `0xccc5` | **`+0x70`** |
| `__DATA_DIRTY.__data` | `0x6508` | `0x6568` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x6a08` | `0x6a50` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xa494` | `0xa4d4` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2d70` | `0x2da8` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0xef8` | `0xf18` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f60` | `0x1f78` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x25e8` | `0x25d8` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x988` | `0x994` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x348` | `0x350` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xd80` | `0xd88` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8a4` | `0x8ac` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xad0` | `0xad8` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `0x4` | `0x8` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x1518` | `0x151c` | **`+0x4`** |

### Other Changes

```diff

-376.0.1.0.0
+376.1.3.0.0

-  Functions: 12193
-  Symbols:   3915
-  CStrings:  2519
+  Functions: 12228
+  Symbols:   3932
+  CStrings:  2536
Symbols:
+ __DATA__TtCV13FinanceDaemon27ReceiptPhotoLibraryProvider9Ownership
+ __IVARS__TtCV13FinanceDaemon27ReceiptPhotoLibraryProvider9Ownership
+ __METACLASS_DATA__TtCV13FinanceDaemon27ReceiptPhotoLibraryProvider9Ownership
+ ___swift_closure_destructor.159Tm
+ ___swift_deallocate_boxed_opaque_existential_1
+ ___swift_exist.box.addr_destructor.162Tm
+ ___swift_exist.box.addr_destructor.166Tm
+ _associated conformance 13FinanceDaemon9WallClockVs0D0AA7InstantsADP_s0E8Protocol
+ _flat unique 13FinanceDaemon5Clock_px7InstantsABPRts_XP
+ _objc_release_x10
+ _swift_initStructMetadata
+ _symbolic $ss5ClockP
+ _symbolic 7Instant_____Qyd__ s5ClockP
+ _symbolic _____ 13FinanceDaemon27ReceiptPhotoLibraryProviderV9OwnershipC
+ _symbolic _____ 13FinanceDaemon27ReceiptPhotoLibraryProviderV9OwnershipC5TokenV
+ _symbolic _____ 13FinanceDaemon9WallClockV
+ _symbolic _____Sg 13FinanceDaemon27ReceiptPhotoLibraryProviderV9OwnershipC5TokenV
+ _symbolic _____Sg_ABt 10FinanceKit22BankConnectConsentTypeO
+ _symbolic _____Sg_ABt 10FinanceKit25BankConnectRefreshFailureO
+ _symbolic __________Xj l13FinanceDaemon5Clock_px7InstantRts_XPXG AaCV
+ _symbolic _____ySiG 15Synchronization5MutexVAARi_zrlE
+ _symbolic y_____Ybc 10Foundation3URLV
- ___swift_closure_destructor.162Tm
- ___swift_exist.box.addr_destructor.165Tm
- ___swift_exist.box.addr_destructor.169Tm
- ___swift_memcpy344_8
- _type_layout_string 13FinanceDaemon17ReceiptWorkSourceV
CStrings:
+ "%ld photo library claim(s) live, deferring shutdown."
+ "Account %s is granted by non-issuer consent %s; leaving it in place."
+ "Cannot initiate connection authorization for a placeholder institution."
+ "Consent %s grants no accounts; revoking it."
+ "Failed to revoke vacated consent %s: %@"
+ "Last photo library claim released, library shut down."
+ "Line item image withheld as sensitive"
+ "Migrating account %s from superseded issuer consent %s to %s."
+ "No photo library changes to process, scheduling check for %{public}s."
+ "Photo library needs setup or has changes, scheduling immediately."
+ "Refusing to fetch placeholder institution during consent exchange: %s."
+ "Refusing to initiate connection authorization for placeholder institutionID: %s."
+ "Rolling back consent %s also deletes its granted account(s): %s"
+ "Skipping institution data fetch for placeholder institutionID: %s."
+ "Skipping pending consent processing for placeholder institutionID: %s. Deleting the pending consent."
+ "Upcoming Transactions Metrics Tracking: skipping stale account ledger"
+ "Work engine loop detection is DISABLED via internal settings."
+ "disableWorkEngineLoopDetection"
- "Failed to open system photo library: %@"
```
