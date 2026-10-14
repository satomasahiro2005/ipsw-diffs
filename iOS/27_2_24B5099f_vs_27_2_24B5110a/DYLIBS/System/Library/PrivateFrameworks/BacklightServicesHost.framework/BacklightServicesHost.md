## BacklightServicesHost

> `/System/Library/PrivateFrameworks/BacklightServicesHost.framework/BacklightServicesHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cc9c` | `0x9d5f8` | **`+0x95c`** |
| `__AUTH_CONST.__objc_const` | `0x19478` | `0x196f0` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x13056` | `0x1310f` | **`+0xb9`** |
| `__TEXT.__objc_methlist` | `0x9dec` | `0x9ea4` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0x7d40` | `0x7dc0` | **`+0x80`** |
| `__DATA.__data` | `0x2520` | `0x2580` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c68` | `0x3cb8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x7ef1` | `0x7f41` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2908` | `0x2940` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x2de0` | `0x2e08` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1318` | `0x133c` | **`+0x24`** |
| `__TEXT.__gcc_except_tab` | `0xee0` | `0xef4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x638` | `0x640` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x318` | `0x320` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x518` | `0x520` | **`+0x8`** |

### Other Changes

```diff

-6.1.4.0.0
+6.1.6.0.0

-  Functions: 4247
-  Symbols:   7501
-  CStrings:  2009
+  Functions: 4266
+  Symbols:   7539
+  CStrings:  2016
Symbols:
+ +[BLSHEnvironmentEnumerationContext contextForUpdateFlipbookVisualState:backlightState:environmentCount:]
+ +[BLSHEnvironmentEnumerationContext contextForUpdateTransitionStatesToBacklightState:reason:event:environmentCount:]
+ -[BLSHBacklightEnvironmentStateMachine _lock_allFlipbookTransitionsDidBeginUpdateForTarget:]
+ -[BLSHBacklightEnvironmentStateMachine _lock_isAddingEnvironmentsForTarget:]
+ -[BLSHBacklightEnvironmentStateMachine _lock_transitionCompleteAfterCompletingTransitionState:forTarget:]
+ -[BLSHBacklightEnvironmentStateMachine endAddingEnvironmentsForContext:]
+ -[BLSHBacklightEnvironmentStateMachine startAddingEnvironmentsForContext:]
+ -[BLSHBacklightEventMetrics setSourceEventValue:]
+ -[BLSHBacklightEventMetrics sourceEventValue]
+ -[BLSHEnvironmentEnumerationContext .cxx_destruct]
+ -[BLSHEnvironmentEnumerationContext appendDescriptionToStream:]
+ -[BLSHEnvironmentEnumerationContext backlightState]
+ -[BLSHEnvironmentEnumerationContext description]
+ -[BLSHEnvironmentEnumerationContext didEnumerateEnvironment:]
+ -[BLSHEnvironmentEnumerationContext enumeratedCount]
+ -[BLSHEnvironmentEnumerationContext environmentCount]
+ -[BLSHEnvironmentEnumerationContext initWithSource:backlightState:reason:event:isFlipbook:environmentCount:]
+ _OBJC_CLASS_$_BLSHEnvironmentEnumerationContext
+ _OBJC_IVAR_$_BLSHBacklightEnvironmentStateMachine._lock_addingEnvironmentsContexts
+ _OBJC_IVAR_$_BLSHBacklightEnvironmentStateMachine._lock_updatingFlipbookBacklightState
+ _OBJC_IVAR_$_BLSHBacklightEventMetrics._sourceEventValue
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._backlightState
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._enumeratedCount
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._enumeratingEnvironmentIdentifier
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._environmentCount
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._event
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._isFlipbook
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._reason
+ _OBJC_IVAR_$_BLSHEnvironmentEnumerationContext._source
+ _OBJC_METACLASS_$_BLSHEnvironmentEnumerationContext
+ __OBJC_$_CLASS_METHODS_BLSHEnvironmentEnumerationContext
+ __OBJC_$_INSTANCE_METHODS_BLSHEnvironmentEnumerationContext
+ __OBJC_$_INSTANCE_VARIABLES_BLSHEnvironmentEnumerationContext
+ __OBJC_$_PROP_LIST_BLSHEnvironmentEnumerationContext
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BSDescriptionStreaming
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BSDescriptionStreaming
+ __OBJC_$_PROTOCOL_REFS_BSDescriptionStreaming
+ __OBJC_CLASS_PROTOCOLS_$_BLSHEnvironmentEnumerationContext
+ __OBJC_CLASS_RO_$_BLSHEnvironmentEnumerationContext
+ __OBJC_LABEL_PROTOCOL_$_BSDescriptionStreaming
+ __OBJC_METACLASS_RO_$_BLSHEnvironmentEnumerationContext
+ __OBJC_PROTOCOL_$_BSDescriptionStreaming
+ ___63-[BLSHEnvironmentEnumerationContext appendDescriptionToStream:]_block_invoke
+ ___63-[BLSHEnvironmentEnumerationContext appendDescriptionToStream:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_97_e8_32s40s48s56s64s72s80bs_e48_v24?0"<BLSHBacklightSceneHostEnvironment>"816ls32l8s40l8s48l8s56l8s64l8s80l8s72l8
- -[BLSHBacklightEnvironmentStateMachine _lock_allFlipbookTransitionsDidBeginUpdate]
- -[BLSHBacklightEnvironmentStateMachine _lock_transitionCompleteAfterCompletingTransitionState:]
- -[BLSHBacklightEnvironmentStateMachine endAddingEnvironments]
- GCC_except_table29
- GCC_except_table33
- _OBJC_IVAR_$_BLSHBacklightEnvironmentStateMachine._lock_addingEnvironmentsCount
- _OBJC_IVAR_$_BLSHSystemWakeTelemetry._isTelemetryEnqueuedAtUtilityQOS
- ___block_descriptor_89_e8_32s40s48s56s64s72bs_e48_v24?0"<BLSHBacklightSceneHostEnvironment>"816ls32l8s40l8s48l8s56l8s72l8s64l8
CStrings:
+ "%lu/%lu"
+ "%p ended adding environments for untracked context:%@, %@"
+ "ESM:%p:%{public}@ endAddingEnvironments:%{public}@ resumes:%{public}@"
+ "ESM:%p:%{public}@ startAddingEnvironments:%{public}@ interrupts:%{public}@"
+ "Uc"
+ "[SystemWakeMetrics] metrics timer fired"
+ "addingEnvironments"
+ "at"
+ "a\xf0!"
+ "updateFlipbookVisualState"
- "Tc"
- "_lock_addingEnvironmentsCount == 0"
- "a\xf1"
```
