## HealthMedicationsUI

> `/System/Library/PrivateFrameworks/HealthMedicationsUI.framework/HealthMedicationsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f8318` | `0x2f8c68` | **`+0x950`** |
| `__TEXT.__cstring` | `0x981b` | `0x994b` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x6418` | `0x64d0` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x3880` | `0x38b0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2ae0` | `0x2b10` | **`+0x30`** |
| `__DATA.__data` | `0x8490` | `0x84b0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x9568` | `0x9588` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x658a` | `0x657a` | **`-0x10`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 14052
+  Functions: 14056

-  CStrings:  1005
+  CStrings:  1010
Symbols:
+ ___swift_closure_destructor.32Tm
+ _symbolic So13HKDisplayTypeC
- ___swift_closure_destructor.31Tm
- _symbolic So29HKInteractiveChartDisplayTypeC
CStrings:
+ "MedicationChartDataSource:medicationDoseEventStatisticsCollectionQueryFor"
+ "MedicationDoseEventDataSource:fetchDoseEvents"
+ "MedicationDoseEventDataSource:observeDoseEvents"
+ "MedicationSearchViewModel:makeCHRImportPublisher"
+ "MedicationSourceListDataSource:queryDoseEventSources"
```
