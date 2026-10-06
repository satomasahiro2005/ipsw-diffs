## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9c7c` | `0xd9de4` | **`+0x168`** |
| `__TEXT.__cstring` | `0xf790` | `0xf7f9` | **`+0x69`** |
| `__AUTH_CONST.__cfstring` | `0xdbc0` | `0xdc20` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x39f98` | `0x39ff8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xf0da` | `0xf137` | **`+0x5d`** |
| `__TEXT.__objc_methlist` | `0x1d71c` | `0x1d764` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e78` | `0x5ea8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x5e8` | `0x5f0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3ed0` | `0x3ed8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1720` | `0x1728` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2208` | `0x2210` | **`+0x8`** |

### Other Changes

```diff

-753.0.15.0.0
+753.0.17.0.0

-  Functions: 10650
-  Symbols:   15768
-  CStrings:  3204
+  Functions: 10656
+  Symbols:   15778
+  CStrings:  3209
Symbols:
+ -[PowerUIIBLMNotificationManager displayUnusualDrainNotification]
+ -[PowerUIIBLMNotificationManager postIBLMNotificationWithTitleKey:bodyKey:identifier:category:]
+ -[PowerUIRuntimeAwarenessNotifier mlCheckActive]
+ -[PowerUIRuntimeAwarenessNotifier mlCheckTimer]
+ -[PowerUIRuntimeAwarenessNotifier mlCheckTransaction]
+ -[PowerUIRuntimeAwarenessNotifier setMlCheckActive:]
+ -[PowerUIRuntimeAwarenessNotifier setMlCheckTimer:]
+ -[PowerUIRuntimeAwarenessNotifier setMlCheckTransaction:]
+ -[PowerUIRuntimeAwarenessNotifier startMLCheckTimer]
+ -[PowerUIRuntimeAwarenessNotifier stopMLCheckTimer]
+ GCC_except_table5
+ _OBJC_IVAR_$_PowerUIRuntimeAwarenessNotifier._mlCheckActive
+ _OBJC_IVAR_$_PowerUIRuntimeAwarenessNotifier._mlCheckTimer
+ _OBJC_IVAR_$_PowerUIRuntimeAwarenessNotifier._mlCheckTransaction
+ ___52-[PowerUIRuntimeAwarenessNotifier startMLCheckTimer]_block_invoke
+ ___95-[PowerUIIBLMNotificationManager postIBLMNotificationWithTitleKey:bodyKey:identifier:category:]_block_invoke
+ _dispatch_resume
+ _kIBLMUnusualDrainNotification
- -[PowerUIRuntimeAwarenessNotifier cancelMLCheckAlarm]
- -[PowerUIRuntimeAwarenessNotifier mlAlarmScheduled]
- -[PowerUIRuntimeAwarenessNotifier scheduleMLCheckAlarm]
- -[PowerUIRuntimeAwarenessNotifier setMlAlarmScheduled:]
- GCC_except_table3
- _OBJC_IVAR_$_PowerUIRuntimeAwarenessNotifier._mlAlarmScheduled
- ___52-[PowerUIRuntimeAwarenessNotifier handleAlarmEvent:]_block_invoke_2
- ___64-[PowerUIIBLMNotificationManager displayIBLMEngagedNotification]_block_invoke
CStrings:
+ "Conditions no longer met for ML check (battery: %ld%%, plugged: %d), stopping timer"
+ "Current battery level: %ld%% - invalid"
+ "IBLM-UnusualDrain"
+ "POWERUI_ADAPTIVE_POWER_FIRST_TIME_BODY"
+ "POWERUI_ADAPTIVE_POWER_FIRST_TIME_TITLE"
+ "POWERUI_ADAPTIVE_POWER_UNUSUAL_DRAIN_BODY"
+ "POWERUI_ADAPTIVE_POWER_UNUSUAL_DRAIN_TITLE"
+ "Posting onboarding Adaptive Power notification"
+ "Posting unusual-drain Adaptive Power notification"
+ "Starting ML check timer"
+ "Stopping ML check timer"
+ "com.apple.osi.iblm.unusualDrainNotification"
+ "com.apple.powerui.runtimeAwareness.mlCheck"
+ "unusualDrainIBLMCategory"
- "/System/Library/UserNotifications/Bundles/com.apple.osintelligence.notifications.bundle"
- "ADAPTIVE_POWER_FIRST_TIME_BODY"
- "ADAPTIVE_POWER_FIRST_TIME_TITLE"
- "Cancelling ML check alarm"
- "Conditions no longer met for ML check (battery: %ld%%, plugged: %d), cancelling alarm"
- "Localizable-IBLM"
- "Posting First time IBLM notification"
- "RuntimeAwarenessMLCheck"
- "Scheduling ML check alarm"
```
