## RecoverDeviceUI

> `/Applications/RecoverDeviceUI.app/RecoverDeviceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13700` | `0x13904` | **`+0x204`** |
| `__DATA_CONST.__cfstring` | `0x1bc0` | `0x1c00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x538` | `0x4f8` | **`-0x40`** |
| `__TEXT.__cstring` | `0x153e` | `0x1560` | **`+0x22`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0

-  CStrings:  1263
+  CStrings:  1265
Functions:
~ -[RecoverDeviceMenuViewController titleForOption:] : 148 -> 368
~ -[RecoverDeviceMenuViewController tableView:didSelectRowAtIndexPath:] : 676 -> 672
~ -[RecoverDeviceUIExtensionRemoteViewController cleanupOldRecoveredDevices] : 804 -> 800
~ ___65-[RecoverDeviceUIExtensionRemoteViewController showProgressCard:]_block_invoke_2 : 2252 -> 2144
~ ___64-[RecoverDeviceUIExtensionRemoteViewController showScanningCard]_block_invoke_2 : 1232 -> 1356
~ ___61-[RecoverDeviceUIExtensionRemoteViewController showEraseCard]_block_invoke_2 : 1416 -> 1484
~ ___82-[RecoverDeviceUIExtensionRemoteViewController showEraseApprovalCard:isAlternate:]_block_invoke : 1736 -> 1828
~ -[RecoverDeviceUIExtensionRemoteViewController configureSUCardForErase:isAlternate:] : 600 -> 736
~ ___82-[RecoverDeviceUIExtensionRemoteViewController showSUCard:build:icon:isAlternate:]_block_invoke_4 : 324 -> 320
~ -[RecoverDeviceUIExtensionRemoteViewController convertDataToPasscode:] : 580 -> 576
CStrings:
+ "DONE"
+ "ERASE_APPROVAL_TITLE"
+ "ERASE_APPROVAL_TITLE_OTHER"
+ "PROGRESS_CARD_USAGE"
+ "PROGRESS_CARD_USAGE_VERSION"
+ "SCANNING_CARD_ERASE_DETAILS"
- "OK"
- "PROGRESS_CARD_TITLE_VERSION"
- "PROGRESS_CARD_USAGE_INSTRUCTIONS"
- "PROGRESS_CARD_VIEW_AGAIN_OTHER"
```
