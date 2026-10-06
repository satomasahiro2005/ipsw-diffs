## SearchOnDeviceAnalytics

> `/System/Library/PrivateFrameworks/SearchOnDeviceAnalytics.framework/SearchOnDeviceAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16d2e8` | `0x1714e8` | **`+0x4200`** |
| `__TEXT.__eh_frame` | `0xce3c` | `0xd264` | **`+0x428`** |
| `__AUTH_CONST.__const` | `0xc4b8` | `0xc708` | **`+0x250`** |
| `__TEXT.__const` | `0x27ff0` | `0x28210` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x8730` | `0x88e0` | **`+0x1b0`** |
| `__DATA.__bss` | `0x27140` | `0x272c0` | **`+0x180`** |
| `__AUTH.__data` | `0x94e0` | `0x9640` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0xa31` | `0xb71` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x413f` | `0x4219` | **`+0xda`** |
| `__TEXT.__constg_swiftt` | `0x6ccc` | `0x6da4` | **`+0xd8`** |
| `__TEXT.__swift5_fieldmd` | `0x913c` | `0x91f4` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x17e0` | `0x1890` | **`+0xb0`** |
| `__TEXT.__swift5_capture` | `0xa24` | `0xabc` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x59e8` | `0x5a78` | **`+0x90`** |
| `__DATA.__data` | `0x58d0` | `0x5940` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x928` | `0x978` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xaed2` | `0xaf22` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0x6c` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x44` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x40` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x524` | `0x534` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x14b4` | `0x14c0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x190` | `0x198` | **`+0x8`** |

### Other Changes

```diff

-3600.56.21.0.0
+3600.56.26.0.0

-  Functions: 15263
-  Symbols:   3379
-  CStrings:  625
+  Functions: 15388
+  Symbols:   3407
+  CStrings:  629
Symbols:
+ __DATA__TtC23SearchOnDeviceAnalytics14OrphanableTask
+ __IVARS__TtC23SearchOnDeviceAnalytics14OrphanableTask
+ __METACLASS_DATA__TtC23SearchOnDeviceAnalytics14OrphanableTask
+ ___swift_closure_destructor.14Tm
+ _associated conformance 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeOSHAASQ
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic BD
+ _symbolic IeghH_
+ _symbolic Say_____4mode_yyYaYbKc9operationtG 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeO
+ _symbolic ScCyyt_____G s5NeverO
+ _symbolic Scgy___________pG 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeO s5ErrorP
+ _symbolic _____ 23SearchOnDeviceAnalytics14OrphanableTaskC
+ _symbolic _____ 23SearchOnDeviceAnalytics14OrphanableTaskC5State33_686DDEC55B801A84D9775349C14C477FLLO
+ _symbolic _____ 23SearchOnDeviceAnalytics17WatchdogWorkGroupV
+ _symbolic _____ 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeO
+ _symbolic _____ s8DurationV
+ _symbolic _____4mode_yyc9operationt 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeO
+ _symbolic ______pIeghHzo_ s5ErrorP
+ _symbolic _____y_____4mode_yyYaYbKc9operationtG s23_ContiguousArrayStorageC 23SearchOnDeviceAnalytics17WatchdogWorkGroupV8TaskModeO
+ _symbolic yt______pIeghHrzo_ s5ErrorP
+ _type_layout_string 23SearchOnDeviceAnalytics17WatchdogWorkGroupV
CStrings:
+ "OrphanableTask waiter cancelled — operation left running (orphaned)"
+ "OrphanableTask.signal() ignored — already resolved"
+ "WatchdogWorkGroup best-effort task failed (swallowed): %s"
+ "WatchdogWorkGroup watchdog fired after %s: %ld/%ld required task(s) complete, %ld still running (cancelling)"
```
