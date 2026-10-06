## WelcomeKitUI

> `/System/Library/PrivateFrameworks/WelcomeKitUI.framework/WelcomeKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14560` | `0x14b64` | **`+0x604`** |
| `__TEXT.__cstring` | `0x4ec0` | `0x4fd0` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x37f8` | `0x38c0` | **`+0xc8`** |
| `__TEXT.__objc_methlist` | `0x1ae4` | `0x1b7c` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x4ce0` | `0x4d60` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1458` | `0x14d0` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x588` | `0x5b0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x608` | `0x630` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x234` | `0x24c` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__const` | `0x92` | `0x9a` | **`+0x8`** |

### Other Changes

```diff

-1439.0.0.0.0
+1441.40.1.0.0

-  Functions: 497
-  Symbols:   1208
-  CStrings:  649
+  Functions: 510
+  Symbols:   1229
+  CStrings:  653
Symbols:
+ -[WLTransferringViewController _currentUptime]
+ -[WLTransferringViewController _hasItemCount]
+ -[WLTransferringViewController _noteProgressReport]
+ -[WLTransferringViewController _progressReportAge]
+ -[WLTransferringViewController _progressReportsHaveStalled]
+ -[WLTransferringViewController _transferProgressText]
+ -[WLTransferringViewController _updateProgressTextForItemCount]
+ -[WLTransferringViewController displayedProgressText]
+ -[WLTransferringViewController setCompletedItemCount:totalItemCount:]
+ -[WLWelcomeController daemon:didUpdateCompletedItemCount:totalItemCount:]
+ -[WLWelcomeController setMigrationState:]
+ -[WLWelcomeController updateCompletedItemCount:totalItemCount:]
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_WLTransferringViewController._completedItemCount
+ _OBJC_IVAR_$_WLTransferringViewController._displayedProgressText
+ _OBJC_IVAR_$_WLTransferringViewController._firstItemCountUptime
+ _OBJC_IVAR_$_WLTransferringViewController._lastProgressReportUptime
+ _OBJC_IVAR_$_WLTransferringViewController._reportedStall
+ _OBJC_IVAR_$_WLTransferringViewController._totalItemCount
+ ___73-[WLWelcomeController daemon:didUpdateCompletedItemCount:totalItemCount:]_block_invoke
+ ___block_descriptor_56_e8_32w_e5_v8?0lw32l8
CStrings:
+ "%@ has had no progress report for %.0f seconds. Showing the waiting text in place of the estimate."
+ "%@ received a progress report after a stall."
+ "%@ will update item count. completed_item_count=%lld, total_item_count=%lld"
+ "PROGRESS_TRANSFERRING_NO_RECENT_UPDATE"
```
