## SensingAlgsService

> `/System/Library/PrivateFrameworks/SensingAlgsService.framework/SensingAlgsService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21408` | `0x217d4` | **`+0x3cc`** |
| `__TEXT.__oslogstring` | `0x182f` | `0x18c3` | **`+0x94`** |
| `__DATA_CONST.__const` | `0xa0` | `0x118` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x280` | `0x2a0` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x3e0` | `0x3c0` | **`-0x20`** |
| `__TEXT.__const` | `0x1ceb` | `0x1d03` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xeec` | `0xf04` | **`+0x18`** |
| `__TEXT.__cstring` | `0x42e` | `0x440` | **`+0x12`** |
| `__AUTH_CONST.__objc_const` | `0xb78` | `0xb68` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x808` | `0x800` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xb00` | `0xaf8` | **`-0x8`** |

### Other Changes

```diff

-72.0.0.0.0
+72.1.0.0.0

-  Functions: 784
-  Symbols:   1424
-  CStrings:  161
+  Functions: 789
+  Symbols:   1436
+  CStrings:  165
Symbols:
+ -[BrailleModeObserver initWithQueue:handler:]
+ -[SASInterfaceTouch initWithStreamSize:platformId:personalityId:queue:streamCallback:]
+ GCC_except_table125
+ GCC_except_table126
+ GCC_except_table134
+ GCC_except_table14
+ GCC_except_table17
+ GCC_except_table186
+ GCC_except_table195
+ GCC_except_table25
+ GCC_except_table28
+ GCC_except_table3
+ GCC_except_table33
+ GCC_except_table40
+ GCC_except_table41
+ GCC_except_table5
+ _OBJC_IVAR_$_BrailleModeObserver._notifyToken
+ _OUTLINED_FUNCTION_40
+ _OUTLINED_FUNCTION_41
+ __NSConcreteStackBlock
+ __ZN14SABinaryParser14parseRunHeaderEv
+ __ZN14SABinaryParser19parseLongInjExtDataEPFbPvRK20_SABinaryInjExtPointtjPKhES7_PFbS0_S3_EPFbS0_RK24_SABinaryRunControlPointES7_S7_S9_
+ ___45-[BrailleModeObserver initWithQueue:handler:]_block_invoke
+ ___86-[SASInterfaceTouch initWithStreamSize:platformId:personalityId:queue:streamCallback:]_block_invoke
+ ___block_descriptor_40_ea8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_40_ea8_32bs_e8_v12?0i8ls32l8
+ ___block_descriptor_40_ea8_32w_e8_v12?0B8lw32l8
+ _dispatch_async
+ _notify_cancel
+ _notify_register_dispatch
+ _objc_alloc
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_retain
+ _objc_retain_x22
- -[BrailleModeObserver brailleEnabled]
- -[BrailleModeObserver init]
- -[BrailleModeObserver setBrailleEnabled:]
- GCC_except_table1
- GCC_except_table123
- GCC_except_table124
- GCC_except_table132
- GCC_except_table185
- GCC_except_table19
- GCC_except_table194
- GCC_except_table2
- GCC_except_table30
- GCC_except_table31
- GCC_except_table4
- GCC_except_table7
- _CFNotificationCenterAddObserver
- _CFNotificationCenterGetDarwinNotifyCenter
- _CFNotificationCenterRemoveObserver
- _OBJC_IVAR_$_BrailleModeObserver._brailleEnabled
- __OBJC_$_PROP_LIST_BrailleModeObserver
- __ZL20NotificationListenerP22__CFNotificationCenterPvPK10__CFStringPKvPK14__CFDictionary
- __ZN14SABinaryParser19parseLongInjExtDataEPFbPvRK20_SABinaryInjExtPointtjPKhES7_PFbS0_S3_E
- _objc_alloc_init
- _objc_retain_x1
- _objc_retain_x4
CStrings:
+ "24B5105a"
+ "Device supports braille sensing mode, but no queue was provided. Braille mode is disabled"
+ "SensingAlgsService-72.1~21"
+ "[BrailleModeObserver] Failed to register notification: %u"
+ "v12@?0B8"
+ "v12@?0i8"
- "24B5098s"
- "SensingAlgsService-72~1038"
```
