## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/GameCenterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171ea8` | `0x172424` | **`+0x57c`** |
| `__AUTH_CONST.__cfstring` | `0x11260` | `0x114e0` | **`+0x280`** |
| `__TEXT.__cstring` | `0x18cd0` | `0x18ec0` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0xdcfb` | `0xde1b` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x5a30` | `0x5968` | **`-0xc8`** |
| `__DATA_DIRTY.__bss` | `0xda0` | `0xe20` | **`+0x80`** |
| `__DATA.__bss` | `0x81c0` | `0x8150` | **`-0x70`** |
| `__TEXT.__gcc_except_tab` | `0x123c` | `0x12a0` | **`+0x64`** |
| `__DATA_CONST.__const` | `0x6108` | `0x6158` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x6c18` | `0x6c58` | **`+0x40`** |
| `__TEXT.__const` | `0x6568` | `0x6548` | **`-0x20`** |
| `__DATA.__data` | `0x3a68` | `0x3a50` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x10e0` | `0x10f8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1540` | `0x1550` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x738` | `0x748` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6790` | `0x67a0` | **`+0x10`** |

### Other Changes

```diff

-821.0.16.0.0
+821.0.18.0.0

-  - /System/Library/Frameworks/ReplayKit.framework/ReplayKit

+  - /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration

-  Functions: 11198
-  Symbols:   12288
-  CStrings:  4165
+  Functions: 11204
+  Symbols:   12298
+  CStrings:  4190
Symbols:
+ _DMIsMigrationNeeded
+ _DMPerformMigrationReturningAfterPlugin
+ _GKKickoffAccountsMigrationGate.once
+ _OUTLINED_FUNCTION_267
+ _OUTLINED_FUNCTION_268
+ _OUTLINED_FUNCTION_269
+ ___54-[ACAccountStore(GameCenter) _gkMapAccountsWithBlock:]_block_invoke_3
+ ___GKKickoffAccountsMigrationGate_block_invoke
+ ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8ls32l8
+ ___block_descriptor_64_e8_32s40s48bs56bs_e14_v16?0?<v?>8ls48l8s32l8s56l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e34_v32?0"NSNumber"8"NSArray"16^B24ls56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48bs56bs64bs_e35_v24?0"ACAccountType"8"NSError"16ls48l8s56l8s32l8s64l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56bs64bs72bs_e20_v20?0B8"NSError"12ls56l8s32l8s40l8s64l8s48l8s72l8
+ __gkAccountsMigrationDone
- GCC_except_table33
- ___block_descriptor_56_e8_32s40s48s_e34_v32?0"NSNumber"8"NSArray"16^B24ls32l8s40l8s48l8
- ___block_descriptor_64_e8_32s40s48bs56bs_e35_v24?0"ACAccountType"8"NSError"16ls48l8s32l8s56l8s40l8
- ___block_descriptor_72_e8_32s40s48s56bs64bs_e20_v20?0B8"NSError"12ls32l8s40l8s56l8s48l8s64l8
CStrings:
+ "\n"
+ "  +%7.3fs %@ (%.1fms)"
+ "  +%7.3fs %@ (PENDING %.3fs)"
+ "AK.setAppleIDWithAltDSID.duplicate"
+ "AK.setAppleIDWithAltDSID.legacy"
+ "Waiting for com.apple.accounts.migrator before serving accountsd queries"
+ "_gkMapAccountsWithBlock: returning nil. com.apple.accounts.migrator has not finished yet"
+ "_gkMapAccountsWithBlock: timed out after %ds. Stages:\n%@"
+ "accountTypeWithIdentifier"
+ "accountsWithAccountType"
+ "block.perAccount"
+ "com.apple.accounts.migrator"
+ "com.apple.accounts.migrator finished; accountsd queries enabled"
+ "com.apple.gamed.accountsMigrationGate"
+ "dedup.AKAppleID.init"
+ "dedup.byUsername"
+ "dedup.removeAccount.duplicate"
+ "dedup.removeAccount.older"
+ "done.aboutToCall"
+ "done.errorBranch"
+ "perform.entered"
+ "removeAccount.duplicateAppleID"
+ "removeAccount.legacyMalformed"
+ "requestAccessToAccountsWithType"
+ "start"
```
