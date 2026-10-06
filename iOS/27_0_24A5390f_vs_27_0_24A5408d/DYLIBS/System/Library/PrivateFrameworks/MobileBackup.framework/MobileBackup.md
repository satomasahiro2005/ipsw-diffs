## MobileBackup

> `/System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e0c8` | `0x2e290` | **`+0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0x5288` | `0x52d8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x7a30` | `0x7a5b` | **`+0x2b`** |
| `__AUTH_CONST.__cfstring` | `0x56e0` | `0x5700` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3e84` | `0x3ea4` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2270` | `0x2280` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x10c8` | `0x10d0` | **`+0x8`** |

### Other Changes

```diff

-3039.0.1.0.0
+3039.2.2.0.0

-  Functions: 1570
-  Symbols:   2591
-  CStrings:  1138
+  Functions: 1572
+  Symbols:   2595
+  CStrings:  1139
Symbols:
+ -[CoreTelephonyClient(BackupOnCellularSupport) mb_backupOnCellularSupport:cellularRadioType:error:]
+ -[MBBehaviorOptions d2dBackgroundDisconnectTimeout]
+ -[MBBehaviorOptions d2dFileTransferDisconnectTimeout]
+ -[MBXPCClient _fetchBackupOnCellularSupportWithCaching]
+ __OBJC_$_CATEGORY_CoreTelephonyClient_$_BackupOnCellularSupport
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_CoreTelephonyClient_$_BackupOnCellularSupport
+ ___55-[MBXPCClient _fetchBackupOnCellularSupportWithCaching]_block_invoke
- -[MBBehaviorOptions d2dTransferDisconnectTimeout]
- -[MBXPCClient _backupOnCellularSupport]
- ___39-[MBXPCClient _backupOnCellularSupport]_block_invoke
Functions:
~ -[MBCellularDataSubscriptionMonitor _backupOnCellularSupportWithError:] : 2248 -> 220
+ -[CoreTelephonyClient(BackupOnCellularSupport) mb_backupOnCellularSupport:cellularRadioType:error:]
~ -[MBXPCClient backupOnCellularSupportWithAccount:error:] : 96 -> 276
+ -[MBBehaviorOptions d2dBackgroundDisconnectTimeout]
CStrings:
+ "D2DBackgroundDisconnectTimeout"
+ "D2DFileTransferDisconnectTimeout"
- "D2DDisconnectTimeout"
```
