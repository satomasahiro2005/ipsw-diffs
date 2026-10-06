## ModelManagerServices

> `/System/Library/PrivateFrameworks/ModelManagerServices.framework/ModelManagerServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1501dc` | `0x154cb0` | **`+0x4ad4`** |
| `__DATA.__bss` | `0x1fd20` | `0x1ef20` | **`-0xe00`** |
| `__DATA_DIRTY.__bss` | `0x12e80` | `0x13c80` | **`+0xe00`** |
| `__DATA_DIRTY.__data` | `0x5998` | `0x5f40` | **`+0x5a8`** |
| `__AUTH.__data` | `0x1b70` | `0x1760` | **`-0x410`** |
| `__TEXT.__eh_frame` | `0x11660` | `0x11a08` | **`+0x3a8`** |
| `__AUTH_CONST.__const` | `0xcad0` | `0xcd58` | **`+0x288`** |
| `__DATA.__data` | `0x2cb8` | `0x2b38` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x1adb` | `0x1c3b` | **`+0x160`** |
| `__TEXT.__swift5_capture` | `0xe70` | `0xfd0` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x7da0` | `0x7ea0` | **`+0x100`** |
| `__TEXT.__const` | `0x1b130` | `0x1b1f8` | **`+0xc8`** |
| `__AUTH_CONST.__auth_got` | `0x1008` | `0x1090` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x5f64` | `0x5fb8` | **`+0x54`** |
| `__TEXT.__swift5_fieldmd` | `0x5200` | `0x523c` | **`+0x3c`** |
| `__DATA.__common` | `0x48` | `0x10` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `0x100` | `0x138` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x2aaf` | `0x2adf` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x788` | `0x7b0` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x81c` | `0x83c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4f8` | `0x510` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x52a0` | `0x52b0` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-698.0.0.502.1
+703.0.11.0.0

-  Functions: 11401
-  Symbols:   3147
-  CStrings:  402
+  Functions: 11482
+  Symbols:   3155
+  CStrings:  409
Symbols:
+ ___swift_closure_destructor.130Tm
+ ___swift_closure_destructor.134Tm
+ ___swift_closure_destructor.243Tm
+ _qos_class_self
+ _swift_task_addPriorityEscalationHandler
+ _swift_task_removePriorityEscalationHandler
+ _symbolic Ieg_
+ _symbolic ScP
+ _symbolic _____Sg 8Dispatch0A3QoSV0B6SClassO
+ _symbolic ___________8priorityt s6UInt64V s5UInt8V
+ _symbolic ______pSgz_Xx s5ErrorP
+ _symbolic _____yq_______pGIeghn_ s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____yqd__G 20ModelManagerServices22TaskCancellableMessageO
- ___swift_closure_destructor.118Tm
- ___swift_closure_destructor.122Tm
- ___swift_closure_destructor.241Tm
- _get_type_metadata 15Synchronization5MutexVySDy20ModelManagerServices14UUIDIdentifierVyAD7SessionCGAD0C13ServiceClientC0G5CacheVGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ " priority "
+ "Escalated task for message %llu to priority %hhu."
+ "Escalation message for %llu sent successfully."
+ "Failed to send escalation message for %llu: %@"
+ "Received task escalation for message %llu to priority %hhu."
+ "Task for message %llu escalated to priority %hhu, sending escalation message."
+ "Task for message %llu not found to escalate."
```
