## ScreenTime

> `/System/Library/Frameworks/ScreenTime.framework/ScreenTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5888` | `0x5adc` | **`+0x254`** |
| `__AUTH_CONST.__objc_const` | `0xf10` | `0xf40` | **`+0x30`** |
| `__TEXT.__cstring` | `0x366` | `0x38f` | **`+0x29`** |
| `__DATA_CONST.__objc_selrefs` | `0x668` | `0x690` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x7ec` | `0x814` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x240` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xf0` | `0x110` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x170` | `0x178` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-655.0.107.0.0
+655.1.6.1.0

+  - /System/Library/PrivateFrameworks/FamilyControlsObjC.framework/FamilyControlsObjC

-  Functions: 198
-  Symbols:   431
-  CStrings:  53
+  Functions: 203
+  Symbols:   437
+  CStrings:  54
Symbols:
+ -[STScreenTimeConfigurationObserver _cancelNotificationToken:]
+ -[STScreenTimeConfigurationObserver authorizationNotificationToken]
+ -[STScreenTimeConfigurationObserver setAuthorizationNotificationToken:]
+ GCC_except_table13
+ GCC_except_table18
+ GCC_except_table21
+ _FOAuthorizationRecordsChangedNotification
+ _OBJC_IVAR_$_STScreenTimeConfigurationObserver._authorizationNotificationToken
- GCC_except_table16
- GCC_except_table19
CStrings:
+ "webBrowserSettings.hasChildAuthorization"
```
