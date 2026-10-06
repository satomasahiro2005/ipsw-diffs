## SensingAlgsService

> `/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2111c` | `0x21408` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x1796` | `0x182f` | **`+0x99`** |
| `__TEXT.__gcc_except_tab` | `0xe88` | `0xeec` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3e0` | `0x42c` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x238` | `0x280` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xad0` | `0xb00` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x7f0` | `0x808` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a0` | `0x5a8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 780
-  Symbols:   1413
-  CStrings:  155
+  Functions: 784
+  Symbols:   1424
+  CStrings:  161
Symbols:
+ -[BrailleModeObserver dealloc]
+ -[BrailleModeObserver init]
+ GCC_except_table185
+ GCC_except_table194
+ GCC_except_table75
+ _AXDeviceSupportsBrailleSensingMode
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ __AXSBrailleSensingModeExpected
+ __ZL20NotificationListenerP22__CFNotificationCenterPvPK10__CFStringPKvPK14__CFDictionary
+ ___clang_call_terminate
+ _objc_alloc_init
+ _objc_retain_x1
- GCC_except_table184
- GCC_except_table193
- GCC_except_table74
CStrings:
+ "24A413"
+ "Device supports braille sensing mode. Enabling braille mode observer"
+ "SensingAlgsService-72~103"
+ "[BrailleModeObserver] Braille mode %s"
+ "[BrailleModeObserver] Notification registered"
+ "com.apple.accessibility.braille.sensing.mode.expected.status"
+ "disabled"
+ "enabled"
- "24A5408d"
- "SensingAlgsService-72~108"
```
