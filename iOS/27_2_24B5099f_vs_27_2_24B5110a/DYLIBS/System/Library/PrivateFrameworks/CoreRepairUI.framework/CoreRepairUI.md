## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e7f4` | `0x1fb88` | **`+0x1394`** |
| `__TEXT.__cstring` | `0x3e5a` | `0x4240` | **`+0x3e6`** |
| `__AUTH_CONST.__cfstring` | `0x4ac0` | `0x4cc0` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0xda0` | `0xf65` | **`+0x1c5`** |
| `__AUTH_CONST.__objc_const` | `0x3ed8` | `0x3f98` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x174c` | `0x17c4` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xdd0` | `0xe28` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x1900` | `0x1950` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x550` | `0x570` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__const` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x15c` | `0x160` | **`+0x4`** |

### Other Changes

```diff

-1307.40.64.0.0
+1307.40.66.0.0

-  Functions: 520
+  Functions: 540

-  CStrings:  739
+  CStrings:  767
CStrings:
+ "+[MRFinishRepairAlert alertShownKeyForFollowUpClientID:]"
+ "+[MRFinishRepairAlert composedMessageWithFormat:finishRepairMessage:]"
+ "+[MRFinishRepairAlert shouldPresentAlertWithTitle:message:displayFollowup:alreadyShown:]"
+ "-[MRBaseComponentHandler popUpFinishRepairAlert]"
+ "-[MRBaseComponentHandler sendFinishRepairAlertShownAnalytics]_block_invoke"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairAlertShown)"
+ "FINISH_CAMERA_CONTROL_REPAIR_TITLE"
+ "FINISH_CG_REPAIR_TITLE"
+ "FINISH_ECL_REPAIR_TITLE"
+ "FINISH_LATER"
+ "FINISH_REPAIR_ALERT_MESSAGE"
+ "FINISH_REPAIR_ALERT_SHOWN"
+ "FINISH_REPAIR_NOTIFICATION_MESSAGE"
+ "FINISH_VB_REPAIR_TITLE"
+ "FinishRepairAlertShown"
+ "No response for %@ notification, not acting on it ERROR:%d"
+ "[%s] Finish Repair alert already shown for this repair, skipping"
+ "[%s] Finish Repair alert never reached the screen, re-arming it"
+ "[%s] could not build the Finish Repair alert body, skipping"
+ "[%s] could not build the Finish Repair notification body, falling back to %@"
+ "[%s] follow-up UI disabled, skipping Finish Repair alert"
+ "[%s] message format unusable, falling back to the Finish Repair message: %{public}@"
+ "[%s] no Finish Repair message to build the body from"
+ "[%s] no Finish Repair title or message, skipping Finish Repair alert"
+ "[%s] no follow-up client ID, cannot track the Finish Repair alert"
+ "[%s] popups disabled, skipping Finish Repair alert"
+ "[%s] presenting Finish Repair alert outside the handler lock"
+ "[%s] presenting one-time Finish Repair alert"
```
