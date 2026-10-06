## backboardd

> `/usr/libexec/backboardd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56f34` | `0x58298` | **`+0x1364`** |
| `__TEXT.__objc_methname` | `0xd8c9` | `0xdb53` | **`+0x28a`** |
| `__TEXT.__objc_stubs` | `0x9c80` | `0x9e20` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x4b68` | `0x4c7f` | **`+0x117`** |
| `__TEXT.__oslogstring` | `0x6f39` | `0x704c` | **`+0x113`** |
| `__DATA.__objc_const` | `0xaca0` | `0xad88` | **`+0xe8`** |
| `__DATA_CONST.__cfstring` | `0x4f60` | `0x5020` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x2e2e` | `0x2eb6` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x4924` | `0x49a4` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x3278` | `0x32f0` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x3058` | `0x30c8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1578` | `0x15c8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x730` | `0x770` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0x228` | `0x1f8` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x7d4` | `0x7f0` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x878` | `0x890` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-868.0.0.0.0
+873.100.0.0.0

-  Functions: 1880
-  Symbols:   614
-  CStrings:  4039
+  Functions: 1897
+  Symbols:   617
+  CStrings:  4079
Symbols:
+ _OBJC_CLASS_$_BKSHardwareButtonLongPressDescriptor
+ _OBJC_CLASS_$_BSContinuousMachTimer
+ ___NSArray0__struct
CStrings:
+ " 0x%X/0x%X/%llX long press: emitting synthesized long press"
+ "%s: error unarchiving long press timeouts"
+ "@\"BSContinuousMachTimer\""
+ "CBUIBrightnessNotificationTakenOver"
+ "ConfigA"
+ "ConfigB"
+ "CoreBrightness owns UIBacklightLevelChangedNotification; backboardd will not post it"
+ "LockButton"
+ "SmartCover"
+ "_BKHIDXXSetButtonLongPressTimeouts"
+ "_BKHIDXXSetButtonLongPressTimeouts_block_invoke"
+ "_coreBrightnessOwnsUINotification"
+ "_didEmitLongPress"
+ "_lock_armLongPressTimerForRecord:senderID:page:usage:timeout:"
+ "_lock_cancelLongPressTimerForRecord:"
+ "_lock_effectiveLongPressTimeoutsByUsageKey"
+ "_lock_ensureDeathWatcherForPID:"
+ "_lock_longPressTimeoutsByPID"
+ "_lock_pidToDeathWatcher"
+ "_lock_recomputeEffectiveTimeouts"
+ "_lock_removeDeathWatcherForPID:"
+ "_longPressTimer"
+ "_longPressTimerFiredForSenderID:page:usage:record:"
+ "_longPressTimerQueue"
+ "_probeCoverSensorsFromContext:deviceUsagePage:deviceUsage:available:engaged:attached:unknownState:"
+ "addEntriesFromDictionary:"
+ "com.apple.backboard.button-long-press.0x%X/0x%X"
+ "com.apple.backboardd.button-long-press"
+ "hoistOnThread:forSessionID:"
+ "long press timeouts for pid %d removed"
+ "long press timeouts for pid %d set to %{public}@"
+ "removeLongPressTimeoutsForPID:"
+ "setLongPressTimeouts:forPID:"
+ "timeout"
+ "v16@?0@\"BSContinuousMachTimer\"8"
+ "v28@0:8@?16I24"
+ "v28@0:8@?<v@?>16I24"
+ "v40@0:8Q16S24S28@32"
+ "v48@0:8@16Q24S32S36d40"
+ "v64@0:8@16I24I28^Q32^Q40^B48^B56"
+ "\x81"
- "_eventRecords"
```
