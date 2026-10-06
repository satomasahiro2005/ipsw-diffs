## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19a20` | `0x1ee08` | **`+0x53e8`** |
| `__AUTH_CONST.__cfstring` | `0x3ae0` | `0x4b80` | **`+0x10a0`** |
| `__TEXT.__cstring` | `0x30ab` | `0x3e4f` | **`+0xda4`** |
| `__AUTH_CONST.__objc_const` | `0x32d8` | `0x3ea8` | **`+0xbd0`** |
| `__AUTH.__objc_data` | `0x12c0` | `0x1900` | **`+0x640`** |
| `__TEXT.__objc_methlist` | `0x1414` | `0x176c` | **`+0x358`** |
| `__TEXT.__unwind_info` | `0x488` | `0x568` | **`+0xe0`** |
| `__DATA_CONST.__objc_classlist` | `0x1e0` | `0x280` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0xd98` | `0xe38` | **`+0xa0`** |
| `__DATA_CONST.__objc_superrefs` | `0x1c0` | `0x260` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x260` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xd66` | `0xdd7` | **`+0x71`** |
| `__DATA.__bss` | `0x130` | `0x190` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x470` | `0x4c8` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x3d0` | `0x424` | **`+0x54`** |
| `__DATA_CONST.__const` | `0x428` | `0x470` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0x78` | **`+0x30`** |

### Other Changes

```diff

-  Functions: 461
-  Symbols:   249
-  CStrings:  610
+  Functions: 527
+  Symbols:   260
+  CStrings:  747
Symbols:
+ _OBJC_CLASS_$_CRBatteryAuxStatus
+ _OBJC_CLASS_$_CRDisplayMainStatus
+ _OBJC_CLASS_$_CRDisplayMainTCONStatus
+ _OBJC_CLASS_$_CRFcamMainStatus
+ _OBJC_CLASS_$_CRFcamStatus
+ _OBJC_CLASS_$_CRIOBoardStatus
+ _OBJC_CLASS_$_CRPearlController
+ _OBJC_CLASS_$_UIActivityIndicatorView
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _PSTableCellKey
CStrings:
+ "BATTERYAUX_FOOTER_LEARN_MORE"
+ "BATTERYMAIN_FOOTER_LEARN_MORE"
+ "BATTERY_ERROR"
+ "BATTERY_ERROR_IPAD"
+ "BatteryAux"
+ "BatteryMain"
+ "CANCEL"
+ "DISPLAYMAINTCON_DESC"
+ "DISPLAYMAINTCON_FOLLOWUP_INFO"
+ "DISPLAYMAINTCON_FOLLOWUP_TITLE"
+ "DISPLAYMAINTCON_POPUP_INFO"
+ "DISPLAYMAINTCON_SETTINGS_TITLE"
+ "DISPLAYMAIN_FOOTER_LEARN_MORE"
+ "DISPLAYOUTRTCON_DESC"
+ "DISPLAYOUTRTCON_FOLLOWUP_INFO"
+ "DISPLAYOUTRTCON_FOLLOWUP_TITLE"
+ "DISPLAYOUTRTCON_POPUP_INFO"
+ "DISPLAYOUTRTCON_SETTINGS_TITLE"
+ "DISPLAYOUTR_FOOTER_LEARN_MORE"
+ "DisplayMain"
+ "DisplayOutr"
+ "FCAM_COMPONENT"
+ "FCAM_FOOTER_LEARN_MORE"
+ "FCAM_KB_URL"
+ "FCAM_MAIN_COMPONENT"
+ "FCAM_MAIN_FOOTER_LEARN_MORE"
+ "FINISH_BATTERYAUX_DESC"
+ "FINISH_BATTERYAUX_REPAIR_DESC"
+ "FINISH_BATTERYAUX_REPAIR_TITLE"
+ "FINISH_BATTERYMAIN_DESC"
+ "FINISH_BATTERYMAIN_REPAIR_DESC"
+ "FINISH_BATTERYMAIN_REPAIR_TITLE"
+ "FINISH_DISPLAYMAIN_DESC"
+ "FINISH_DISPLAYMAIN_REPAIR_DESC"
+ "FINISH_DISPLAYMAIN_REPAIR_TITLE"
+ "FINISH_DISPLAYOUTR_DESC"
+ "FINISH_DISPLAYOUTR_REPAIR_DESC"
+ "FINISH_DISPLAYOUTR_REPAIR_TITLE"
+ "FINISH_FCAM_DESC"
+ "FINISH_FCAM_MAIN_DESC"
+ "FINISH_FCAM_MAIN_REPAIR_DESC"
+ "FINISH_FCAM_MAIN_REPAIR_TITLE"
+ "FINISH_FCAM_REPAIR_DESC"
+ "FINISH_FCAM_REPAIR_TITLE"
+ "FINISH_IOBOARD_DESC"
+ "FINISH_IOBOARD_REPAIR_DESC"
+ "FINISH_IOBOARD_REPAIR_TITLE"
+ "Front Camera"
+ "GENUINE_BATTERYAUX_DESC"
+ "GENUINE_BATTERYMAIN_DESC"
+ "GENUINE_DISPLAYMAIN_DESC"
+ "GENUINE_DISPLAYOUTR_DESC"
+ "GENUINE_FCAM_DESC"
+ "GENUINE_FCAM_MAIN_DESC"
+ "IMPORTANT_BATTERYAUX_MESSAGE"
+ "IMPORTANT_BATTERYMAIN_MESSAGE"
+ "IMPORTANT_DISPLAYMAIN_MESSAGE"
+ "IMPORTANT_DISPLAYOUTR_MESSAGE"
+ "IMPORTANT_FCAM_MAIN_MESSAGE"
+ "IMPORTANT_FCAM_MESSAGE"
+ "IO Board"
+ "IOBOARD_FOOTER_LEARN_MORE"
+ "IO_BOARD"
+ "Main Battery"
+ "Main Display"
+ "Main Front Camera"
+ "NETWORK_CONNECTION_DESC"
+ "NETWORK_CONNECTION_DESC_IPAD"
+ "NETWORK_CONNECTION_REQUIRED"
+ "NEW_BATTERYAUX"
+ "NEW_BATTERYMAIN"
+ "NEW_DISPLAYMAIN"
+ "NEW_DISPLAYOUTR"
+ "NEW_FCAM"
+ "NEW_FCAM_MAIN"
+ "NEW_IOBOARD"
+ "NEW_MAIN_DISPLAY"
+ "NONGENUINE_BATTERYAUX_DESC"
+ "NONGENUINE_BATTERYMAIN_DESC"
+ "NONGENUINE_DISPLAYMAIN_DESC"
+ "NONGENUINE_DISPLAYOUTR_DESC"
+ "NONGENUINE_FCAM_DESC"
+ "NONGENUINE_FCAM_MAIN_DESC"
+ "NOT_AVAILABLE"
+ "NOT_NOW"
+ "NeedsServiceAux"
+ "Network is not reachable"
+ "OS Update required to proceed"
+ "Outer Display"
+ "RESTART_AND_FINISH_REPAIR"
+ "RestartInitiated"
+ "SOFTWARE_UPDATE"
+ "SOFTWARE_UPDATE_DESC"
+ "SOFTWARE_UPDATE_DESC_IPAD"
+ "SOFTWARE_UPDATE_REQUIRED"
+ "TRY_AGAIN_LATER_DESC"
+ "UNABLE_TO_VERIFY_BATTERYAUX_MESSAGE"
+ "UNABLE_TO_VERIFY_BATTERYAUX_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_BATTERYMAIN_MESSAGE"
+ "UNABLE_TO_VERIFY_BATTERYMAIN_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_DISPLAYMAIN_MESSAGE"
+ "UNABLE_TO_VERIFY_DISPLAYMAIN_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_DISPLAYOUTR_MESSAGE"
+ "UNABLE_TO_VERIFY_DISPLAYOUTR_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_FCAM_MAIN_MESSAGE"
+ "UNABLE_TO_VERIFY_FCAM_MAIN_NOTIF_TEXT"
+ "UNABLE_TO_VERIFY_FCAM_MESSAGE"
+ "UNABLE_TO_VERIFY_FCAM_NOTIF_TEXT"
+ "USED_BATTERYAUX_DESC"
+ "USED_DISPLAYMAIN_DESC"
+ "USED_DISPLAYOUTR_DESC"
+ "USED_FCAM_DESC"
+ "USED_FCAM_MAIN_DESC"
+ "com.apple.mobilerepair.BatteryAuxRepair"
+ "com.apple.mobilerepair.DisplayMainRepair"
+ "com.apple.mobilerepair.batteryauxunlockchecker"
+ "com.apple.mobilerepair.displaymainnotifyServer"
+ "com.apple.mobilerepair.displaymainunlockchecker"
+ "failed to clear display main TCON follow up item error:%@"
+ "firstUIDisplayedTimeForDisplayMain"
+ "hasDisplayedFollowupForBatteryAux"
+ "hasDisplayedFollowupForDisplayMain"
+ "hasNotifiedServerForBatteryAux"
+ "hasNotifiedServerForDisplayMain"
+ "lastCheckTimeForBatteryAux"
+ "lastCheckTimeForDisplayMain"
+ "lastKnownIDForDisplayMain"
+ "prefs:root=General&path=SOFTWARE_UPDATE_LINK"
+ "retriggerCheckCountForBatteryAux"
+ "retriggerCheckCountForDisplayMain"
+ "settings-navigation://com.apple.Settings.General/About/MAIN_PARTS_AND_SERVICE/BatteryAux"
+ "settings-navigation://com.apple.Settings.General/About/MAIN_PARTS_AND_SERVICE/DisplayMain"
+ "tcrt-innr"
+ "tcrt-outr"
+ "unlockCheckCountForBatteryAux"
+ "unlockCheckCountForDisplayMain"
+ "v16@?0@\"UIAlertAction\"8"
+ "vcrt-4080"
+ "vcrt-4081"
- "SEED_BUILDS_NOT_SUPPORTED"
- "SEED_BUILDS_NOT_SUPPORTED_IPAD"
```
