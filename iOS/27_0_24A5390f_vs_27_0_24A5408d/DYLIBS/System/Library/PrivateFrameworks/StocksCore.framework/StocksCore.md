## StocksCore

> `/System/Library/PrivateFrameworks/StocksCore.framework/StocksCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x256844` | `0x257afc` | **`+0x12b8`** |
| `__TEXT.__oslogstring` | `0x3405` | `0x3665` | **`+0x260`** |
| `__TEXT.__gcc_except_tab` | `0x2b8` | `0x334` | **`+0x7c`** |
| `__TEXT.__cstring` | `0xffc0` | `0x10010` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1580` | `0x15c0` | **`+0x40`** |
| `__DATA.__data` | `0x43d0` | `0x4410` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x95f8` | `0x9630` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x6c04` | `0x6c2c` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0xb5e0` | `0xb5c0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x14260` | `0x14278` | **`+0x18`** |
| `__DATA.__common` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x12c0` | `0x12d8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3738` | `0x3750` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x208` | `0x1f0` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2470` | `0x2478` | **`+0x8`** |

### Other Changes

```diff

-2022.0.0.0.0
+2028.1.0.0.0

+  - /System/Library/PrivateFrameworks/AppPrivateData.framework/AppPrivateData

-  Functions: 13741
-  Symbols:   5583
-  CStrings:  1884
+  Functions: 13770
+  Symbols:   5590
+  CStrings:  1895
Symbols:
+ +[NSError(SCWAdditions) scw_databaseDecodeErrorWithUnderlyingError:]
+ +[NSError(SCWAdditions) scw_databaseReadErrorWithUnderlyingError:]
+ -[NSError(SCWAdditions) scw_isFileNotFoundError]
+ -[SCWDatabaseJSONStore _loadFromFileURL:error:]
+ -[SCWDatabaseJSONStore _reloadIfNeededFromFileURL:didReload:error:]
+ -[SCWDatabaseJSONStore readWithError:accessor:]
+ -[SCWDatabaseJSONStore readZone:error:accessor:]
+ -[SCWDatabaseJSONStore reloadWithError:accessor:]
+ -[SCWDatabaseJSONStore writeWithError:accessor:]
+ -[SCWDatabaseJSONStore writeZone:error:accessor:]
+ -[SCWFauxDatabaseStoreCoordinator readWithError:accessor:]
+ -[SCWFauxDatabaseStoreCoordinator readZone:error:accessor:]
+ -[SCWFauxDatabaseStoreCoordinator reloadWithError:accessor:]
+ -[SCWFauxDatabaseStoreCoordinator writeWithError:accessor:]
+ -[SCWFauxDatabaseStoreCoordinator writeZone:error:accessor:]
+ GCC_except_table100
+ GCC_except_table113
+ GCC_except_table117
+ GCC_except_table123
+ GCC_except_table14
+ GCC_except_table17
+ GCC_except_table36
+ GCC_except_table37
+ GCC_except_table91
+ GCC_except_table97
+ _NSCocoaErrorDomain
+ _NSLocalizedDescriptionKey
+ _NSPOSIXErrorDomain
+ __OBJC_$_CLASS_METHODS_NSError(SCWAdditions|SCWAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSError(SCWAdditions|SCWAdditions)
+ ___47-[SCWDatabaseJSONStore readWithError:accessor:]_block_invoke
+ ___47-[SCWDatabaseJSONStore readWithError:accessor:]_block_invoke_2
+ ___48-[SCWDatabaseJSONStore readZone:error:accessor:]_block_invoke
+ ___48-[SCWDatabaseJSONStore writeWithError:accessor:]_block_invoke
+ ___48-[SCWDatabaseJSONStore writeWithError:accessor:]_block_invoke_2
+ ___49-[SCWDatabaseJSONStore reloadWithError:accessor:]_block_invoke
+ ___49-[SCWDatabaseJSONStore reloadWithError:accessor:]_block_invoke_2
+ ___49-[SCWDatabaseJSONStore writeZone:error:accessor:]_block_invoke
+ ___58-[SCWFauxDatabaseStoreCoordinator readWithError:accessor:]_block_invoke
+ ___59-[SCWFauxDatabaseStoreCoordinator readZone:error:accessor:]_block_invoke
+ ___59-[SCWFauxDatabaseStoreCoordinator writeWithError:accessor:]_block_invoke
+ ___60-[SCWFauxDatabaseStoreCoordinator reloadWithError:accessor:]_block_invoke
+ ___60-[SCWFauxDatabaseStoreCoordinator writeZone:error:accessor:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e28_v16?0"<SCWDatabaseStore>"8ls40l8s32l8
+ ___block_descriptor_56_e8_32bs40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_56_e8_32s40bs48r_e15_v16?0"NSURL"8ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40bs48r_e5_v8?0ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e24_v16?0"<SCWZoneStore>"8lr48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56bs64r_e17_v16?0"NSError"8lr64l8s32l8s40l8s56l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56bs64r72r_e5_v8?0ls32l8s40l8r64l8r72l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80r_e74_v44?0"CKRecordZoneID"8"CKServerChangeToken"16"NSData"24B32"NSError"36ls32l8s40l8s48l8s56l8s64l8r80l8s72l8
+ _objc_autorelease
- -[SCWDatabaseJSONStore _loadFromFileURL:]
- -[SCWDatabaseJSONStore _reloadIfNeededFromFileURL:]
- -[SCWDatabaseJSONStore readWithAccessor:]
- -[SCWDatabaseJSONStore readZone:withAccessor:]
- -[SCWDatabaseJSONStore reloadWithAccessor:]
- -[SCWDatabaseJSONStore writeWithAccessor:]
- -[SCWDatabaseJSONStore writeZone:withAccessor:]
- -[SCWFauxDatabaseStoreCoordinator readWithAccessor:]
- -[SCWFauxDatabaseStoreCoordinator readZone:withAccessor:]
- -[SCWFauxDatabaseStoreCoordinator reloadWithAccessor:]
- -[SCWFauxDatabaseStoreCoordinator writeWithAccessor:]
- -[SCWFauxDatabaseStoreCoordinator writeZone:withAccessor:]
- GCC_except_table110
- GCC_except_table114
- GCC_except_table120
- GCC_except_table35
- GCC_except_table90
- GCC_except_table95
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSError_$_SCWAdditions
- ___41-[SCWDatabaseJSONStore readWithAccessor:]_block_invoke
- ___41-[SCWDatabaseJSONStore readWithAccessor:]_block_invoke_2
- ___41-[SCWDatabaseJSONStore readWithAccessor:]_block_invoke_3
- ___42-[SCWDatabaseJSONStore writeWithAccessor:]_block_invoke
- ___42-[SCWDatabaseJSONStore writeWithAccessor:]_block_invoke_2
- ___43-[SCWDatabaseJSONStore reloadWithAccessor:]_block_invoke
- ___43-[SCWDatabaseJSONStore reloadWithAccessor:]_block_invoke_2
- ___46-[SCWDatabaseJSONStore readZone:withAccessor:]_block_invoke
- ___47-[SCWDatabaseJSONStore writeZone:withAccessor:]_block_invoke
- ___48-[SCWDatabase modifyContentsOfZone:withCommand:]_block_invoke_4
- ___48-[SCWDatabase modifyContentsOfZone:withCommand:]_block_invoke_5
- ___52-[SCWFauxDatabaseStoreCoordinator readWithAccessor:]_block_invoke
- ___53-[SCWFauxDatabaseStoreCoordinator writeWithAccessor:]_block_invoke
- ___54-[SCWDatabase _recoverFromIdentityLossWithCompletion:]_block_invoke_4
- ___54-[SCWFauxDatabaseStoreCoordinator reloadWithAccessor:]_block_invoke
- ___57-[SCWFauxDatabaseStoreCoordinator readZone:withAccessor:]_block_invoke
- ___58-[SCWFauxDatabaseStoreCoordinator writeZone:withAccessor:]_block_invoke
- ___block_descriptor_48_e8_32bs40r_e5_v8?0ls32l8r40l8
- ___block_descriptor_48_e8_32s40bs_e15_v16?0"NSURL"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40bs_e28_v16?0"<SCWDatabaseStore>"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e28_v16?0"<SCWDatabaseStore>"8ls48l8s32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs56r_e24_v16?0"<SCWZoneStore>"8lr56l8s32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s56l8s48l8
- ___block_descriptor_72_e8_32s40s48s56bs64r_e5_v8?0ls32l8s40l8r64l8s48l8s56l8
- ___block_descriptor_80_e8_32s40s48s56s64s72bs_e74_v44?0"CKRecordZoneID"8"CKServerChangeToken"16"NSData"24B32"NSError"36ls32l8s40l8s48l8s56l8s64l8s72l8
- ___swift_closure_destructor.20Tm
CStrings:
+ "%p JSON store failed to decode JSON from disk with error: %{public}@"
+ "%p JSON store failed to load from disk with error: %{public}@"
+ "%p JSON store failed to read with error: %{public}@"
+ "%p JSON store failed to reload with error: %{public}@"
+ "%p JSON store failed to write with error: %{public}@"
+ "The on-disk database store could not be decoded."
+ "The on-disk database store could not be read."
+ "failed to load zones from disk at startup with error: %{public}@"
+ "ignoring empty watchlist zone due to error: %{public}@"
+ "skipping database changes fetch because the store could not be read: %{public}@"
+ "skipping identity-loss recovery because the store could not be written: %{public}@"
+ "skipping modification of zone %{public}@ because the store could not be written: %{public}@"
- "%p failed to decode database JSON with error: %{public}@"
```
