## HealthMedicationsDaemonPlugin

> `/System/Library/PrivateFrameworks/HealthMedicationsDaemonPlugin.framework/HealthMedicationsDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55c90` | `0x5cd64` | **`+0x70d4`** |
| `__AUTH_CONST.__auth_got` | `0x0` | `0x8d0` | **`+0x8d0`** |
| `__TEXT.__eh_frame` | `—` | `0x4d8` | **`+0x4d8`** |
| `__TEXT.__const` | `0x192` | `0x5ac` | **`+0x41a`** |
| `__AUTH_CONST.__const` | `0x480` | `0x808` | **`+0x388`** |
| `__DATA.__bss` | `0x10` | `0x290` | **`+0x280`** |
| `__DATA_DIRTY.__bss` | `0x10` | `0x210` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x1420` | `0x15b0` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `—` | `0x104` | **`+0x104`** |
| `__DATA.__data` | `0x1140` | `0x1200` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `—` | `0xb4` | **`+0xb4`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0xa8` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x840` | `0x8c8` | **`+0x88`** |
| `__TEXT.__swift5_assocty` | `—` | `0x78` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x59` | **`+0x59`** |
| `__DATA_DIRTY.__data` | `—` | `0x58` | **`+0x58`** |
| `__TEXT.__swift_as_entry` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `—` | `0x24` | **`+0x24`** |
| `__TEXT.__swift5_proto` | `—` | `0x24` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x3000` | `0x3020` | **`+0x20`** |
| `__TEXT.__swift5_types` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x1d50` | `0x1d58` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthDomains.framework/HealthDomains

-  - /System/Library/PrivateFrameworks/HealthTopics.framework/HealthTopics
+  - /System/Library/PrivateFrameworks/HealthReport.framework/HealthReport

+  - /usr/lib/swift/libswiftCore.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 1938
-  Symbols:   3534
+  Functions: 2050
+  Symbols:   3620
Symbols:
+ _HKCategoryTypeIdentifierPregnancy
+ __Block_copy
+ __Block_release
+ ___chkstk_darwin
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_closure_destructor
+ ___swift_memcpy0_1
+ ___swift_noop_void_return
+ __swiftEmptyArrayStorage
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_HealthMedicationsDaemonPlugin
+ __swift_stdlib_malloc_size
+ _associated conformance 29HealthMedicationsDaemonPlugin28MedicationLactationEscalatorV0A6Report20EscalationEvaluatingAA5ModelAdEP_0A7Domains0I10Evaluation
+ _associated conformance 29HealthMedicationsDaemonPlugin28MedicationPregnancyEscalatorV0A6Report20EscalationEvaluatingAA5ModelAdEP_0A7Domains0I10Evaluation
+ _associated conformance 29HealthMedicationsDaemonPlugin36MedicationInteractionSevereEscalatorV0A6Report20EscalationEvaluatingAA5ModelAdEP_0A7Domains0J10Evaluation
+ _associated conformance 29HealthMedicationsDaemonPlugin38MedicationInteractionCriticalEscalatorV0A6Report20EscalationEvaluatingAA5ModelAdEP_0A7Domains0J10Evaluation
+ _associated conformance 29HealthMedicationsDaemonPlugin38MedicationInteractionModerateEscalatorV0A6Report20EscalationEvaluatingAA5ModelAdEP_0A7Domains0J10Evaluation
+ _associated conformance 29HealthMedicationsDaemonPlugin5ErrorOSHAASQ
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _bzero
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_retain_x9
+ _swift_allocBox
+ _swift_allocError
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_dynamicCastObjCClass
+ _swift_getExistentialTypeMetadata
+ _swift_getObjCClassMetadata
+ _swift_getWitnessTable
+ _swift_isEscapingClosureAtFileLocation
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x19
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_retain_x24
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _swift_willThrow
+ _symbolic $s12HealthReport20EscalationEvaluatingP
+ _symbolic ShySo29HKMedicationUserDomainConceptCG
+ _symbolic So19HKUserDomainConceptC_____SAySo7NSErrorCSgGSgSbIggyyd_ s5Int64V
+ _symbolic So7NSErrorCSg
+ _symbolic So9HDProfileCSgXw
+ _symbolic _____ 13HealthDomains35MedicationNamesEscalationEvaluationV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin28MedicationLactationEscalatorV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin28MedicationPregnancyEscalatorV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin36MedicationInteractionSevereEscalatorV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin38MedicationInteractionCriticalEscalatorV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin38MedicationInteractionModerateEscalatorV
+ _symbolic _____ 29HealthMedicationsDaemonPlugin5ErrorO
+ _type_layout_string 29HealthMedicationsDaemonPlugin28MedicationLactationEscalatorV
+ _type_layout_string 29HealthMedicationsDaemonPlugin28MedicationPregnancyEscalatorV
+ _type_layout_string 29HealthMedicationsDaemonPlugin36MedicationInteractionSevereEscalatorV
+ _type_layout_string 29HealthMedicationsDaemonPlugin38MedicationInteractionCriticalEscalatorV
+ _type_layout_string 29HealthMedicationsDaemonPlugin38MedicationInteractionModerateEscalatorV
```
