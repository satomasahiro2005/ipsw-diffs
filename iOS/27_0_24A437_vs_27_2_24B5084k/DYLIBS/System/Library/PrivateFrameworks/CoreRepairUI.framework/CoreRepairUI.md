## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ee08` | `0x1e3a8` | **`-0xa60`** |
| `__AUTH_CONST.__cfstring` | `0x4b80` | `0x49c0` | **`-0x1c0`** |
| `__TEXT.__cstring` | `0x3e4f` | `0x3d1c` | **`-0x133`** |
| `__DATA_CONST.__objc_selrefs` | `0xe38` | `0xdb8` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x424` | `0x3d0` | **`-0x54`** |
| `__DATA_CONST.__const` | `0x470` | `0x428` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0x176c` | `0x1724` | **`-0x48`** |
| `__TEXT.__oslogstring` | `0xdd7` | `0xda0` | **`-0x37`** |
| `__TEXT.__unwind_info` | `0x568` | `0x538` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4a0` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x260` | `0x240` | **`-0x20`** |
| `__TEXT.__const` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 527
-  Symbols:   260
-  CStrings:  747
+  Functions: 516
+  Symbols:   255
+  CStrings:  730
Symbols:
- _OBJC_CLASS_$_CRPearlController
- _OBJC_CLASS_$_UIActivityIndicatorView
- _OBJC_CLASS_$_UIAlertAction
- _OBJC_CLASS_$_UIAlertController
- _PSTableCellKey
CStrings:
+ "SEED_BUILDS_NOT_SUPPORTED"
+ "SEED_BUILDS_NOT_SUPPORTED_IPAD"
- "BATTERY_ERROR"
- "BATTERY_ERROR_IPAD"
- "CANCEL"
- "NETWORK_CONNECTION_DESC"
- "NETWORK_CONNECTION_DESC_IPAD"
- "NETWORK_CONNECTION_REQUIRED"
- "NOT_AVAILABLE"
- "NOT_NOW"
- "Network is not reachable"
- "OS Update required to proceed"
- "RESTART_AND_FINISH_REPAIR"
- "RestartInitiated"
- "SOFTWARE_UPDATE"
- "SOFTWARE_UPDATE_DESC"
- "SOFTWARE_UPDATE_DESC_IPAD"
- "SOFTWARE_UPDATE_REQUIRED"
- "TRY_AGAIN_LATER_DESC"
- "prefs:root=General&path=SOFTWARE_UPDATE_LINK"
- "v16@?0@\"UIAlertAction\"8"
```
