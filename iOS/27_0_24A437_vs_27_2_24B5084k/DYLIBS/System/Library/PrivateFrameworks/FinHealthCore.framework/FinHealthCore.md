## FinHealthCore

> `/System/Library/PrivateFrameworks/FinHealthCore.framework/FinHealthCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf4c94` | `0xf728c` | **`+0x25f8`** |
| `__TEXT.__eh_frame` | `0x55c8` | `0x5860` | **`+0x298`** |
| `__TEXT.__oslogstring` | `0x3f9e` | `0x3d3e` | **`-0x260`** |
| `__AUTH_CONST.__const` | `0x2a88` | `0x2c18` | **`+0x190`** |
| `__AUTH.__objc_data` | `0x1b0` | `0x2c0` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x2a48` | `0x2b30` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x6e18` | `0x6ef0` | **`+0xd8`** |
| `__TEXT.__swift5_capture` | `0x448` | `0x4e0` | **`+0x98`** |
| `__TEXT.__const` | `0x3b88` | `0x3c18` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x35e4` | `0x3674` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x19b2` | `0x1a36` | **`+0x84`** |
| `__TEXT.__constg_swiftt` | `0xf8c` | `0x1008` | **`+0x7c`** |
| `__TEXT.__gcc_except_tab` | `0xbe8` | `0xb78` | **`-0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x2110` | `0x2158` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xc33` | `0xc73` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xed0` | `0xf04` | **`+0x34`** |
| `__DATA.__data` | `0xd10` | `0xd40` | **`+0x30`** |
| `__AUTH.__data` | `0x4d8` | `0x500` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1590` | `0x15b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa26a` | `0xa28a` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x378` | `0x38c` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x1a8` | `0x1bc` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xad0` | `0xae0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1ab8` | `0x1ab0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x228` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x110` | `0x114` | **`+0x4`** |

### Other Changes

```diff

-1.9.1.30.0
+1.9.2.3.0

-  Functions: 3405
-  Symbols:   3428
-  CStrings:  1269
+  Functions: 3475
+  Symbols:   3446
+  CStrings:  1260
Symbols:
+ _FHBankConnectTransactionBatchSize
+ _OBJC_CLASS_$__TtC13FinHealthCore26FHTransactionSyncProcessor
+ _OBJC_METACLASS_$__TtC13FinHealthCore26FHTransactionSyncProcessor
+ __DATA__TtC13FinHealthCore26FHTransactionSyncProcessor
+ __INSTANCE_METHODS__TtC13FinHealthCore26FHTransactionSyncProcessor
+ __IVARS__TtC13FinHealthCore26FHTransactionSyncProcessor
+ __METACLASS_DATA__TtC13FinHealthCore26FHTransactionSyncProcessor
+ __OBJC_$_CLASS_METHODS_FinHealthBankConnectController(FinHealthCore)
+ __OBJC_$_INSTANCE_METHODS_FinHealthBankConnectController(FinHealthCore)
+ __PROPERTIES__TtC13FinHealthCore26FHTransactionSyncProcessor
+ ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.69Tm
+ __swift_implicitisolationactor_to_executor_cast
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic SbSo7NSErrorCSgIeyByy_
+ _symbolic SccySb______pG s5ErrorP
+ _symbolic So17FHDatabaseManagerC
+ _symbolic So30FinHealthBankConnectControllerC
+ _symbolic _____ 10ObjectiveC8ObjCBoolV
+ _symbolic _____ 13FinHealthCore26FHTransactionSyncProcessorC
+ _symbolic _____Sg 10FinanceKit0A5ErrorO
+ _symbolic _____Sg_ABt 10FinanceKit0A5ErrorO
- GCC_except_table6
- __OBJC_$_CLASS_METHODS_FinHealthBankConnectController
- __OBJC_$_INSTANCE_METHODS_FinHealthBankConnectController
- ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40r_e20_v20?0B8"NSArray"12lr40l8s32l8
- ___swift_closure_destructor.68Tm
CStrings:
+ "FinHealthCore.FHTransactionSyncProcessor"
+ "History token invalidated by FinanceKit, retrying with full re-sync"
+ "mergeTransactionsWithCompletion : history token invalidated, retrying with full re-sync"
+ "processTransactionBatch: processed=%ld inserts=%ld deletes=%ld failures=%ld"
- "Deleted bank connect transaction with financeTransactionIdentifier: %@"
- "Failed to delete account with accountID: %@ with error=%@"
- "Failed to delete bank connect transaction with financeTransactionIdentifier: %@"
- "Failed to insert initial bankConnect transaction with transaction identifier: %@"
- "Failed to remove financeTransactionIdentifier from card/cash transaction with financeTransactionIdentifier: %@"
- "Failed to update account with accountID: %@"
- "Failed to update transaction with financeTransactionIdentifier: %@"
- "No transaction service identifier for financeTransactionIdentifier %@ for Card/Cash  from FinanceKit source"
- "Removed financeTransactionIdentifier value of card/cash transaction with financeTransactionIdentifier: %@ from FinanceKit source"
- "Saving history token: %@"
- "Updating BC transaction %@"
- "Updating BC transaction %@ without recomputing insights"
- "v20@?0B8@\"NSArray\"12"
```
