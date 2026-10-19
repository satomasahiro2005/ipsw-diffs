## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fb88` | `0x206fc` | **`+0xb74`** |
| `__AUTH_CONST.__cfstring` | `0x4cc0` | `0x4f00` | **`+0x240`** |
| `__TEXT.__cstring` | `0x4240` | `0x43d9` | **`+0x199`** |
| `__DATA_CONST.__objc_selrefs` | `0xe28` | `0xea8` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xf65` | `0xfd8` | **`+0x73`** |
| `__TEXT.__gcc_except_tab` | `0x3d8` | `0x440` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x450` | `0x498` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x17c4` | `0x180c` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4d0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x570` | `0x598` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x240` | `0x260` | **`+0x20`** |

### Other Changes

```diff

-  Functions: 540
-  Symbols:   255
-  CStrings:  767
+  Functions: 552
+  Symbols:   260
+  CStrings:  789
Symbols:
+ _OBJC_CLASS_$_CRPearlController
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _PSTableCellKey
CStrings:
+ "BATTERY_ERROR"
+ "BATTERY_ERROR_IPAD"
+ "CANCEL"
+ "FinishRepairBlockedNoNetwork"
+ "FinishRepairBlockedOSUpdate"
+ "FinishRepairNotNow"
+ "NETWORK_CONNECTION_DESC"
+ "NETWORK_CONNECTION_DESC_IPAD"
+ "NETWORK_CONNECTION_REQUIRED"
+ "NOT_AVAILABLE"
+ "NOT_NOW"
+ "Network is not reachable"
+ "OS Update required to proceed"
+ "RESTART_AND_FINISH_REPAIR"
+ "RestartFinishRepairTapped"
+ "RestartInitiated"
+ "SOFTWARE_UPDATE"
+ "SOFTWARE_UPDATE_DESC"
+ "SOFTWARE_UPDATE_DESC_IPAD"
+ "SOFTWARE_UPDATE_REQUIRED"
+ "TRY_AGAIN_LATER_DESC"
+ "prefs:root=General&path=SOFTWARE_UPDATE_LINK"
+ "v16@?0@\"UIAlertAction\"8"
+ "viewController is nil when attempting to show action sheet."
- "SEED_BUILDS_NOT_SUPPORTED"
- "SEED_BUILDS_NOT_SUPPORTED_IPAD"
```
