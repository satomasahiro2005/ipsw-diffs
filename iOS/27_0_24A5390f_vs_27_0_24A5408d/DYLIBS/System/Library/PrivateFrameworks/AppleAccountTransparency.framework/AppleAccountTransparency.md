## AppleAccountTransparency

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/AppleAccountTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x506e4` | `0x521cc` | **`+0x1ae8`** |
| `__TEXT.__oslogstring` | `0x2cdc` | `0x2ede` | **`+0x202`** |
| `__TEXT.__eh_frame` | `0x43c0` | `0x4520` | **`+0x160`** |
| `__AUTH.__data` | `0x268` | `0x308` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x1908` | `0x1978` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1498` | `0x14f0` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0xdbc` | `0xe08` | **`+0x4c`** |
| `__TEXT.__const` | `0x2d00` | `0x2d48` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1929` | `0x1967` | **`+0x3e`** |
| `__AUTH_CONST.__const` | `0x2438` | `0x2468` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xbb4` | `0xbe4` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x9f0` | `0xa18` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0xb72` | `0xb9a` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3f8` | `0x3d8` | **`-0x20`** |
| `__DATA.__data` | `0x5b8` | `0x5c8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xa58` | `0xa48` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x190` | `0x19c` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x1a0` | `0x1ac` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x1a8` | `0x1b4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x68` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x10d7` | `0x10dc` | **`+0x5`** |
| `__TEXT.__swift5_capture` | `0x734` | `0x730` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xbc` | **`+0x4`** |

### Other Changes

```diff

-445.0.0.0.0
+447.0.0.0.0

-  Functions: 1361
-  Symbols:   674
-  CStrings:  283
+  Functions: 1384
+  Symbols:   675
+  CStrings:  292
Symbols:
+ __DATA__TtC24AppleAccountTransparencyP33_E6620FDB736EB60F373829B9563727CB17BGSystemTaskAcker
+ __IVARS__TtC24AppleAccountTransparencyP33_E6620FDB736EB60F373829B9563727CB17BGSystemTaskAcker
+ __METACLASS_DATA__TtC24AppleAccountTransparencyP33_E6620FDB736EB60F373829B9563727CB17BGSystemTaskAcker
+ _symbolic BAyt______pIeNghHgILrzo_ s5ErrorP
+ _symbolic SS8callSite_t
+ _symbolic Sd
+ _symbolic _____ 24AppleAccountTransparency17BGSystemTaskAcker33_E6620FDB736EB60F373829B9563727CBLLC
- __PROTOCOL_INSTANCE_METHODS__TtP24AppleAccountTransparency14FlowIDSettable_
- __PROTOCOL_METHOD_TYPES__TtP24AppleAccountTransparency14FlowIDSettable_
- __PROTOCOL_PROPERTIES__TtP24AppleAccountTransparency14FlowIDSettable_
- __PROTOCOL__TtP24AppleAccountTransparency14FlowIDSettable_
- _swift_dynamicCastObjCProtocolConditional
- _symbolic $s24AppleAccountTransparency14FlowIDSettableP
CStrings:
+ "AAT XPC timeout: %s after %fs"
+ "AATBackgroundTaskScheduler: No signed-in account — completing task without fetch: %@"
+ "AATBackgroundTaskScheduler: Outer BGST budget (%fs) exceeded — acking as expired"
+ "AATBackgroundTaskScheduler: Task cancelled while fetching altDSID — exiting"
+ "AATBackgroundTaskScheduler: Task completed"
+ "AATBackgroundTaskScheduler: Task expired with retryAfter %f"
+ "AATBackgroundTaskScheduler: Workload exited with %@"
+ "AATBackgroundTaskScheduler: setTaskExpiredWithRetryAfter failed: %{public}@ — falling back to setTaskCompleted"
+ "XPC call timed out at "
+ "makeFetchTask(acker:)"
- "AATBackgroundTaskScheduler: No signed-in account — completing task without fetch"
```
