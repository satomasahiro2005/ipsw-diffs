## ActivityAchievementsDaemon

> `/System/Library/PrivateFrameworks/ActivityAchievementsDaemon.framework/ActivityAchievementsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75f08` | `0x76198` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x929d` | `0x93dd` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x11fc8` | `0x12028` | **`+0x60`** |
| `__DATA.__data` | `0x1080` | `0x10e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x607c` | `0x60ac` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2738` | `0x2760` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x37d8` | `0x3800` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x2154` | `0x2178` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x2cc0` | `0x2ce0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6211` | `0x6221` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xcb8` | `0xcc0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x714` | `0x71c` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1ee8` | `0x1ef0` | **`+0x8`** |

### Other Changes

```diff

-2027.0.18.0.0
+2027.0.20.0.0

-  Functions: 2820
-  Symbols:   4486
-  CStrings:  1012
+  Functions: 2825
+  Symbols:   4498
+  CStrings:  1017
Symbols:
+ -[ACHEarnedInstanceAwardingEngine _queue_updateWorkoutStateWithSnapshot:]
+ -[ACHEarnedInstanceAwardingEngine didUpdateWorkoutSnapshot:]
+ -[ACHEarnedInstanceAwardingEngine initWithClient:assertionClient:workoutObserver:dataStore:earnedInstanceStore:historicalEvaluationPolicy:]
+ _OBJC_IVAR_$_ACHEarnedInstanceAwardingEngine._isWorkoutActive
+ _OBJC_IVAR_$_ACHEarnedInstanceAwardingEngine._workoutObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__HKWorkoutObserverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES__HKWorkoutObserverDelegate
+ __OBJC_CLASS_PROTOCOLS_$_ACHEarnedInstanceAwardingEngine
+ __OBJC_LABEL_PROTOCOL_$__HKWorkoutObserverDelegate
+ __OBJC_PROTOCOL_$__HKWorkoutObserverDelegate
+ ___139-[ACHEarnedInstanceAwardingEngine initWithClient:assertionClient:workoutObserver:dataStore:earnedInstanceStore:historicalEvaluationPolicy:]_block_invoke
+ ___60-[ACHEarnedInstanceAwardingEngine didUpdateWorkoutSnapshot:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ _swift_retain_x19
- -[ACHEarnedInstanceAwardingEngine initWithClient:assertionClient:dataStore:earnedInstanceStore:historicalEvaluationPolicy:]
- ___123-[ACHEarnedInstanceAwardingEngine initWithClient:assertionClient:dataStore:earnedInstanceStore:historicalEvaluationPolicy:]_block_invoke
CStrings:
+ "Protected data became available; attempting queued evaluations"
+ "Queuing incremental request for %{public}@ because a workout is active"
+ "Received a request to run a historical evaluation but a workout is active. Skipping!"
+ "Workout is active"
+ "Workout is no longer active; attempting queued evaluations"
+ "[ACHCurrentActivitySummaryQueryServer] received summary update but a workout is running, skipping client callback"
- "Protected data became available; attempting queued evaluation"
```
