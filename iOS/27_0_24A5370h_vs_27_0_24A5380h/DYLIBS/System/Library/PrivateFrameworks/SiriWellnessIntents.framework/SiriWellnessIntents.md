## SiriWellnessIntents

> `/System/Library/PrivateFrameworks/SiriWellnessIntents.framework/SiriWellnessIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x3cd1` | `0x3df1` | **`+0x120`** |
| `__TEXT.__text` | `0x142dec` | `0x142e88` | **`+0x9c`** |
| `__TEXT.__eh_frame` | `0x275c` | `0x2784` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1b98` | `0x1ba0` | **`+0x8`** |

### Other Changes

```diff

-3600.12.4.1.1
+3600.12.12.0.0
CStrings:
+ "    Built MatchedMedName:\n        scheduleID (%{sensitive}s),\n        medID (%{sensitive}s),\n        name (%{sensitive}s),\n        schedule (%{sensitive}s),\n        loggedTime (%{sensitive}s),\n        status (%{sensitive}s),\n        dosage (%{sensitive}s),\n        dosageUnit (%{sensitive}s),\n        strength (%{sensitive}s),\n        strengthUnit (%{sensitive}s),\n        completionStatus (%{sensitive}s)"
+ "%{sensitive}@"
+ "Failed to convert HKDayIndexRange into a valid date interval. Start: %{sensitive}s End: %{sensitive}s"
+ "Found %ld projections in %{sensitive}s"
+ "Persisting sample...\n  systolic: %{sensitive}f\n  diastolic: %{sensitive}f\n  unit: %{sensitive}s"
+ "Response from querying storage: %{sensitive}@"
+ "Returning response: %{sensitive}s"
+ "doseEventsForID: %{sensitive}s"
+ "end_mostLikelyDays: %{sensitive}ld. end_allDays: %{sensitive}ld"
+ "got a dose event with scheduleID: %s, medID: %s, status: %{sensitive}s"
+ "summary: %{sensitive}@"
+ "updateDosageForDoseEvent: asNeededDosageFromHealthApp (%{sensitive}s)"
+ "updateDosageForDoseEvent: using healthAppDosage (%{sensitive}s)"
- "    Built MatchedMedName:\n        scheduleID (%s),\n        medID (%s),\n        name (%s),\n        schedule (%s),\n        loggedTime (%s),\n        status (%s),\n        dosage (%s),\n        dosageUnit (%s),\n        strength (%s),\n        strengthUnit (%s),\n        completionStatus (%s)"
- "%@"
- "Failed to convert HKDayIndexRange into a valid date interval. Start: %s End: %s"
- "Found %ld projections in %s"
- "Persisting sample...\n  systolic: %f\n  diastolic: %f\n  unit: %s"
- "Response from querying storage: %@"
- "Returning response: %s"
- "doseEventsForID: %s"
- "end_mostLikelyDays: %ld. end_allDays: %ld"
- "got a dose event with scheduleID: %s, medID: %s, status: %s"
- "summary: %@"
- "updateDosageForDoseEvent: asNeededDosageFromHealthApp (%s)"
- "updateDosageForDoseEvent: using healthAppDosage (%s)"
```
