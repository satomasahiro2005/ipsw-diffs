## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa54` | `0x20964` | **`+0xf10`** |
| `__TEXT.__cstring` | `0x40d0` | `0x444d` | **`+0x37d`** |
| `__TEXT.__oslogstring` | `0x3461` | `0x3626` | **`+0x1c5`** |
| `__DATA_CONST.__cfstring` | `0x4060` | `0x41e0` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x463e` | `0x4781` | **`+0x143`** |
| `__TEXT.__objc_stubs` | `0x3a40` | `0x3b40` | **`+0x100`** |
| `__DATA.__objc_const` | `0x3098` | `0x3128` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1a14` | `0x1a74` | **`+0x60`** |
| `__DATA.__objc_data` | `0xe70` | `0xec0` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x11a0` | `0x11e0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0xe41` | `0xe63` | **`+0x22`** |
| `__TEXT.__unwind_info` | `0x7e0` | `0x7f8` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x59f` | `0x5af` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa08` | `0xa10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1307.40.64.0.0
+1307.40.66.0.0

-  Functions: 668
+  Functions: 685

-  CStrings:  1664
+  CStrings:  1699
CStrings:
+ "+[MRFinishRepairAlert alertShownKeyForFollowUpClientID:]"
+ "+[MRFinishRepairAlert composedMessageWithFormat:finishRepairMessage:]"
+ "+[MRFinishRepairAlert shouldPresentAlertWithTitle:message:displayFollowup:alreadyShown:]"
+ "-[MRBaseComponentHandler popUpFinishRepairAlert]"
+ "-[MRBaseComponentHandler sendFinishRepairAlertShownAnalytics]_block_invoke"
+ "B40@0:8@16@24B32B36"
+ "B60@0:8@16@24@32@40B48Q52"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairAlertShown)"
+ "FINISH_LATER"
+ "FINISH_REPAIR_ALERT_MESSAGE"
+ "FINISH_REPAIR_ALERT_SHOWN"
+ "FINISH_REPAIR_NOTIFICATION_MESSAGE"
+ "FinishRepairAlertShown"
+ "MRFinishRepairAlert"
+ "No response for %@ notification, not acting on it ERROR:%d"
+ "Q24@0:8Q16"
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
+ "actionResponseForButtonStyle:"
+ "alertShownKeyForFollowUpClientID:"
+ "composedMessageWithFormat:finishRepairMessage:"
+ "partsAndServiceHistoryURL"
+ "popUpFinishRepairAlert"
+ "popUpNotificationNowWithMessage:title:openSensitiveURL:componentName:legacyPopup:buttonStyle:"
+ "sendFinishRepairAlertShownAnalytics"
+ "shouldPresentAlertWithTitle:message:displayFollowup:alreadyShown:"
+ "stringByReplacingOccurrencesOfString:withString:"
- "popUpNotificationNowWithMessage:title:openSensitiveURL:componentName:legacyPopup:"
- "v52@0:8@16@24@32@40B48"
```
