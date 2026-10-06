## AutomationNotificationContent

> `/private/var/staged_system_apps/Shortcuts.app/PlugIns/AutomationNotificationContent.appex/AutomationNotificationContent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23c` | `0x3f0` | **`+0x1b4`** |
| `__TEXT.__objc_stubs` | `0x180` | `0x280` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x31e` | `0x3c1` | **`+0xa3`** |
| `__TEXT.__auth_stubs` | `0x100` | `0x160` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x150` | `0x190` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x88` | `0xb8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x18` | `0x40` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5111.0.2.0.0
+5113.0.1.1.1
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Symbols:   26
-  CStrings:  78
+  Symbols:   37
+  CStrings:  86
Symbols:
+ _OBJC_CLASS_$_WFDatabase
+ _OBJC_CLASS_$_WFInitialization
+ _WFMakeAutomationNotificationListViewController
+ _WFNotificationAutomationsEnabledCategory
+ _WFNotificationTriggerNotifyBackgroundCategory
+ _WFTriggerKeysToDisableFromNotificationUserInfo
+ ___NSArray0__struct
+ _objc_release_x24
+ _objc_release_x25
+ _objc_release_x26
+ _objc_retain_x8
Functions:
~ sub_100000da8 -> sub_100000e08 : 420 -> 856
CStrings:
+ "addChildViewController:"
+ "count"
+ "defaultDatabase"
+ "didMoveToParentViewController:"
+ "initializeProcessWithDatabase:"
+ "preferredContentSize"
+ "setPreferredContentSize:"
+ "userInfo"
```
