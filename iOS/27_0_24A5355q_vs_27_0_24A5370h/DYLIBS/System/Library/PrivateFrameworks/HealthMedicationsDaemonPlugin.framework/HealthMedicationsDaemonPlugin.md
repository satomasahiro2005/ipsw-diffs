## HealthMedicationsDaemonPlugin

> `/System/Library/PrivateFrameworks/HealthMedicationsDaemonPlugin.framework/HealthMedicationsDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5581c` | `0x55c90` | **`+0x474`** |
| `__TEXT.__oslogstring` | `0x65f3` | `0x66c0` | **`+0xcd`** |
| `__TEXT.__cstring` | `0x659d` | `0x6610` | **`+0x73`** |
| `__DATA_CONST.__const` | `0x1d00` | `0x1d50` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3480` | `0x34c0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x7928` | `0x7968` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fc8` | `0x3000` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x45cc` | `0x4604` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1408` | `0x1420` | **`+0x18`** |
| `__DATA.__bss` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x394` | `0x39c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x820` | `0x828` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa18` | `0xa10` | **`-0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 1928
-  Symbols:   3521
-  CStrings:  852
+  Functions: 1938
+  Symbols:   3534
+  CStrings:  856
Symbols:
+ +[HDHealthMedicationsPluginProtectedDatabaseSchema setUserDefaultsOverride:]
+ +[HDHealthMedicationsPluginProtectedDatabaseSchema userDefaultsOverride]
+ -[HDMedicationsDemoDataGenerator _existingActiveMedicationsListWithError:]
+ -[HDMedicationsWidgetSchedulingManager unitTesting_afterProfileReady:]
+ GCC_except_table17
+ GCC_except_table30
+ GCC_except_table38
+ _NSLocalizedDescriptionKey
+ _OBJC_IVAR_$_HDMedicationsWidgetSchedulingManager._unitTesting_profileReadyComplete
+ _OBJC_IVAR_$_HDMedicationsWidgetSchedulingManager._unitTesting_profileReadyCompletionHandler
+ __OBJC_$_CLASS_METHODS_HDHealthMedicationsPluginProtectedDatabaseSchema
+ ___70-[HDMedicationsWidgetSchedulingManager unitTesting_afterProfileReady:]_block_invoke
+ ___74-[HDMedicationsDemoDataGenerator _existingActiveMedicationsListWithError:]_block_invoke
+ ___block_descriptor_40_e8_32s_e36_B32?0"HKUserDomainConcept"8q16^24ls32l8
+ ___block_descriptor_48_e8_32s40bs_e5_v8?0ls32l8s40l8
+ __userDefaultsOverride
- GCC_except_table13
- GCC_except_table26
- GCC_except_table34
CStrings:
+ "HDMedicationsDemoDataGenerator"
+ "[%{public}@] _existingActiveMedicationsListWithError: enumerate failed: %{public}@"
+ "[%{public}@] _existingActiveMedicationsListWithError: failed (%{public}@) — skipping active-medications setup this run."
+ "enumerateUserDomainConceptsWithPredicate returned NO without populating an error"
```
