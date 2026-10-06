## AutomationNotificationContent

> `/private/var/staged_system_apps/Shortcuts.app/PlugIns/AutomationNotificationContent.appex/AutomationNotificationContent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x634` | `0x23c` | **`-0x3f8`** |
| `__TEXT.__objc_stubs` | `0x320` | `0x180` | **`-0x1a0`** |
| `__TEXT.__objc_methname` | `0x424` | `0x31e` | **`-0x106`** |
| `__TEXT.__auth_stubs` | `0x1a0` | `0x100` | **`-0xa0`** |
| `__DATA.__objc_selrefs` | `0x1b8` | `0x150` | **`-0x68`** |
| `__TEXT.__cstring` | `0x9c` | `0x4b` | **`-0x51`** |
| `__DATA_CONST.__auth_got` | `0xd8` | `0x88` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x58` | `0x18` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x28` | `—` | **`-0x28`** |
| `__TEXT.__objc_methtype` | `0x16e` | `0x159` | **`-0x15`** |
| `__TEXT.__objc_methlist` | `0x1b4` | `0x1a4` | **`-0x10`** |
| `__TEXT.__const` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-5037.109.0.0.0
-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
+5110.0.8.0.0

-  Functions: 6
-  Symbols:   44
-  CStrings:  94
+  Functions: 4
+  Symbols:   26
+  CStrings:  78
Symbols:
- _OBJC_CLASS_$_NSMutableArray
- _OBJC_CLASS_$_WFAutomationNotificationListContentView
- _OBJC_CLASS_$_WFDatabase
- _OBJC_CLASS_$_WFInitialization
- _OBJC_CLASS_$_WFTriggerManager
- _WFNotificationAutomationsEnabledCategory
- _WFNotificationTriggerNotifyBackgroundCategory
- _WFTriggerIDsToDisableNotificationUserInfoFromTriggers
- _WFTriggerKeysToDisableFromNotificationUserInfo
- __NSConcreteStackBlock
- _objc_opt_new
- _objc_release_x24
- _objc_release_x25
- _objc_release_x27
- _objc_release_x8
- _objc_retain_x1
- _objc_retain_x23
- _os_transaction_create
CStrings:
- "addObject:"
- "allConfiguredTriggers"
- "com.apple.shortcuts.automation-notification"
- "count"
- "defaultDatabase"
- "enumerateObjectsUsingBlock:"
- "estimatedSizeForNotificationUserInfo:"
- "initWithDatabase:"
- "initializeProcessWithDatabase:"
- "isEnabled"
- "preferredSize"
- "setPreferredContentSize:"
- "updateUIFromNotificationUserInfo:"
- "userInfo"
- "v32@?0@\"WFConfiguredTrigger\"8Q16^B24"
- "{CGSize=dd}24@0:8@16"
```
