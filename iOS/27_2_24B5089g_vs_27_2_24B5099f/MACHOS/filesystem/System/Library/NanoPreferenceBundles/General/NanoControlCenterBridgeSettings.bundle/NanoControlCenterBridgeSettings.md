## NanoControlCenterBridgeSettings

> `/System/Library/NanoPreferenceBundles/General/NanoControlCenterBridgeSettings.bundle/NanoControlCenterBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf7e8` | `0x17f58` | **`+0x8770`** |
| `__TEXT.__eh_frame` | `0x248` | `0x828` | **`+0x5e0`** |
| `__DATA.__data` | `0xa58` | `0xed8` | **`+0x480`** |
| `__TEXT.__const` | `0xa14` | `0xe44` | **`+0x430`** |
| `__TEXT.__swift5_typeref` | `0xbf0` | `0xfe6` | **`+0x3f6`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0x1010` | **`+0x2a0`** |
| `__TEXT.__constg_swiftt` | `0x58c` | `0x810` | **`+0x284`** |
| `__TEXT.__unwind_info` | `0x380` | `0x5b8` | **`+0x238`** |
| `__DATA.__objc_const` | `0x3d0` | `0x5d8` | **`+0x208`** |
| `__DATA.__bss` | `0x650` | `0x808` | **`+0x1b8`** |
| `__TEXT.__swift5_reflstr` | `0x1f0` | `0x371` | **`+0x181`** |
| `__TEXT.__cstring` | `0x2d9` | `0x459` | **`+0x180`** |
| `__DATA_CONST.__auth_got` | `0x6c0` | `0x810` | **`+0x150`** |
| `__TEXT.__objc_methname` | `0x29f` | `0x3ef` | **`+0x150`** |
| `__DATA_CONST.__const` | `0x6a8` | `0x7c0` | **`+0x118`** |
| `__TEXT.__swift5_fieldmd` | `0x2bc` | `0x3c8` | **`+0x10c`** |
| `__TEXT.__objc_classname` | `0x1ff` | `0x2df` | **`+0xe0`** |
| `__DATA.__objc_data` | `0xa0` | `0x160` | **`+0xc0`** |
| `__TEXT.__swift5_capture` | `0xec` | `0x18c` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x248` | `0x2d8` | **`+0x90`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x84` | **`+0x6c`** |
| `__DATA_CONST.__auth_ptr` | `0x2f8` | `0x360` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x1aa` | `0x1fc` | **`+0x52`** |
| `__TEXT.__swift5_assocty` | `0xa8` | `0xd8` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x30` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xb0` | `0xc8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x1c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x3c` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x7` | `0x11` | **`+0xa`** |

### Same-size Content Changes

- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-102.0.0.0.0
+104.0.0.0.0

-  Functions: 290
-  Symbols:   151
-  CStrings:  66
+  Functions: 430
+  Symbols:   172
+  CStrings:  90
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
+ _OBJC_METACLASS_$_NSObject
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __swift_stdlib_reportUnimplementedInitializer
+ _objc_msgSendSuper2
+ _objc_release_x24
+ _objc_retain_x20
+ _objc_retain_x21
+ _objc_retain_x9
+ _swift_deallocPartialClassInstance
+ _swift_deletedAsyncMethodErrorTu
+ _swift_errorRelease
+ _swift_initStackObject
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain_x24
+ _swift_retain_x8
+ _swift_retain_x9
+ _swift_setDeallocating
+ _swift_task_deinitOnExecutor
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
- __Block_copy
- __Block_release
- __NSConcreteStackBlock
- _objc_release_x27
- _swift_continuation_await
- _swift_continuation_init
- _swift_retain_x2
- _swift_willThrow
CStrings:
+ "%s.%s couldn't get required properties. pairingID: %s; pairingDataStore: %s"
+ "%s.%s no NPSDomainAccessor. Not resetting layout."
+ ".cxx_destruct"
+ "@16@0:8"
+ "CONTROL_CENTER_FLASHLIGHT_FAST_MAX"
+ "CONTROL_CENTER_FLASHLIGHT_SECTION_TITLE"
+ "CONTROL_CENTER_RESET_LAYOUT_SECTION_TITLE"
+ "CONTROL_CENTER_RESET_LAYOUT_TITLE"
+ "NanoControlCenterBridgeSettings.ObserverBox"
+ "NanoControlCenterFlashlightFastMaxChangedNotification"
+ "_TtC31NanoControlCenterBridgeSettingsP33_42C36FF0D170D5830375EE02D388AF3518SyncDomainAccessor"
+ "_TtCCV31NanoControlCenterBridgeSettingsP33_42C36FF0D170D5830375EE02D388AF3521BridgeSettingsContent5Model11ObserverBox"
+ "__flashlightFastMaxBrightness"
+ "__flashlightFastMaxBrightnessTask"
+ "__flashlightFastMaxBrightnessTaskID"
+ "_controlCenterObserverBox"
+ "_crownOrientationDomainAccessor"
+ "_presentingResetLayoutConfirmation"
+ "accessor"
+ "boolForKey:keyExistsAndHasValidFormat:"
+ "com.apple.NanoControlCenter.SyncDomainAccessor"
+ "controlCenterAccessor"
+ "dealloc"
+ "domain"
+ "flashlight_fast_max"
+ "init()"
+ "init(domain:pairingID:pairingDataStore:)"
+ "manager"
+ "parent"
+ "setBool:forKey:"
+ "v16@0:8"
- "%s.%s couldn't make NPSDomainAccessor. Not resetting layout."
- "CONTROL_CENTER_RESET_TITLE"
- "_presentingResetConfirmation"
- "boolForKey:"
- "crownOrientation(for:)"
- "initWithDomain:"
- "v8@?0"
```
