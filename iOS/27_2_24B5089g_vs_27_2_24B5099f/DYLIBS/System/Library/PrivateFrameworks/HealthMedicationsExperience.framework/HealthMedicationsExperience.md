## HealthMedicationsExperience

> `/System/Library/PrivateFrameworks/HealthMedicationsExperience.framework/HealthMedicationsExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x22e9` | `0x25a9` | **`+0x2c0`** |
| `__TEXT.__text` | `0x861b0` | `0x860e0` | **`-0xd0`** |
| `__TEXT.__eh_frame` | `0x36a0` | `0x36b8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x12b0` | `0x12c0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x314` | `0x318` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 3128
+  Functions: 3130

-  CStrings:  315
+  CStrings:  326
CStrings:
+ "HealthMedicationsExperience/ListConceptManager+Medications.swift"
+ "HealthMedicationsExperience/MedicationConceptQuerying.swift"
+ "MedicationDoseDaySummaryProvider:queryMedicationDoseEvents"
+ "MedicationDoseDaySummaryProvider:queryMedicationScheduleItems"
+ "MedicationDoseDaySummaryProvider:startProvidingData"
+ "MedicationOntologyContentProvider:hkConceptPublisher"
+ "MedicationRoomInteractionEvent:statisticsAnalyticsPayload"
+ "MedicationScheduleItemDataSource:doseEvents"
+ "MedicationScheduleItemDataSource:fetchScheduleItem"
+ "MedicationScheduleItemDataSource:fetchScheduleItems"
+ "MedicationScheduleItemDataSource:hk_scheduleItems"
```
