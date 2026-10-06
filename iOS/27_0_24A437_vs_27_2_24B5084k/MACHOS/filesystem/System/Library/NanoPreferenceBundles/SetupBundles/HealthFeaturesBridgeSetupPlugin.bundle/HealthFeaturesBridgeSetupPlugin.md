## HealthFeaturesBridgeSetupPlugin

> `/System/Library/NanoPreferenceBundles/SetupBundles/HealthFeaturesBridgeSetupPlugin.bundle/HealthFeaturesBridgeSetupPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9068` | `0xaacc` | **`+0x1a64`** |
| `__TEXT.__eh_frame` | `0x48` | `0x420` | **`+0x3d8`** |
| `__DATA_CONST.__const` | `0x4f0` | `0x668` | **`+0x178`** |
| `__TEXT.__cstring` | `0x23e` | `0x38e` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x240` | `0x320` | **`+0xe0`** |
| `__DATA.__data` | `0x498` | `0x3f8` | **`-0xa0`** |
| `__TEXT.__auth_stubs` | `0xab0` | `0xb40` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x15c` | `0x1ec` | **`+0x90`** |
| `__TEXT.__const` | `0x350` | `0x3d8` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x797` | `0x717` | **`-0x80`** |
| `__TEXT.__constg_swiftt` | `0x2f0` | `0x27c` | **`-0x74`** |
| `__TEXT.__swift5_typeref` | `0x302` | `0x36a` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x560` | `0x5a8` | **`+0x48`** |
| `__DATA.__objc_const` | `0x530` | `0x4f0` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x178` | `0x1a8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x12c` | `0x148` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x1c1` | `0x1d1` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/swift/libswiftSynchronization.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 183
-  Symbols:   152
-  CStrings:  139
+  Functions: 211
+  Symbols:   157
+  CStrings:  141
Symbols:
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _objc_retain_x22
+ _objc_retain_x24
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_isEscapingClosureAtFileLocation
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_task_switch
- _HKPreferredRegulatoryDomainProvider
- _objc_release_x27
- _objc_retain_x25
- _swift_release_x27
- _swift_retain_x24
- _swift_retain_x25
- _swift_retain_x27
- _swift_retain_x8
CStrings:
+ "HealthFeaturesBridgeSetupPlugin/HealthFeaturesSetupFlowController.swift"
+ "HealthFeaturesBridgeSetupPlugin/HealthFeaturesViewModel.swift"
+ "HealthFeaturesBridgeSetupPlugin/MedicationsThatAffectHeartRateMiniFlowStepController.swift"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "_state"
- "advertisableFeaturePrerequisiteWorkPerformed"
- "commitEnablementPerformed"
- "postCommitWorkItems"
```
