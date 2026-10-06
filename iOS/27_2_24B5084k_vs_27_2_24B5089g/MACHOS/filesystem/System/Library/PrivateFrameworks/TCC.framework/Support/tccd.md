## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8ebbc` | `0x8fe24` | **`+0x1268`** |
| `__TEXT.__objc_methname` | `0x13533` | `0x138f5` | **`+0x3c2`** |
| `__TEXT.__oslogstring` | `0x10db2` | `0x11095` | **`+0x2e3`** |
| `__TEXT.__cstring` | `0x1347d` | `0x1366f` | **`+0x1f2`** |
| `__TEXT.__objc_stubs` | `0xb980` | `0xbb60` | **`+0x1e0`** |
| `__TEXT.__gcc_except_tab` | `0x3120` | `0x31fc` | **`+0xdc`** |
| `__DATA_CONST.__cfstring` | `0x8da0` | `0x8e40` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x56b4` | `0x5754` | **`+0xa0`** |
| `__DATA.__objc_const` | `0xa6c8` | `0xa758` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x37c0` | `0x3840` | **`+0x80`** |
| `__TEXT.__dlopen_cstrs` | `0x90` | `0xd9` | **`+0x49`** |
| `__DATA_CONST.__const` | `0x28d8` | `0x2920` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1ab0` | `0x1ad8` | **`+0x28`** |
| `__DATA.__bss` | `0x429` | `0x441` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__objc_doubleobj` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x764` | `0x770` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x1628` | `0x1630` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-918.0.0.0.0
+919.0.0.0.0

-  Functions: 3078
-  Symbols:   510
-  CStrings:  6012
+  Functions: 3105
+  Symbols:   512
+  CStrings:  6055
Symbols:
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _OBJC_CLASS_$_NSNumberFormatter
CStrings:
+ "%s: %{public}@ accessed Health data %lu time(s) since %{public}@"
+ "%s: %{public}@ did not expand; falling back to the countless sentence"
+ "%s: HealthKit framework not available, no access count for %{public}@"
+ "%s: access report failed for %{public}@: %{public}@"
+ "%s: could not create the access store for %{public}@, no access count"
+ "%s: last drain for %{public}@ is %.0fs in the future, ignoring the throttle"
+ "%s: no access report for %{public}s/%{public}s, deferring to a later unlock (%lu of %lu)"
+ "%s: no localized string for %{public}@; falling back to the countless sentence"
+ "%s: still no access report for %{public}s/%{public}s after %lu deferrals, showing the prompt without a count"
+ "%s: timed out waiting for the access report for %{public}@"
+ "+[TCCDReminderMonitor milestoneOverrideFromDefaultsForKey:]"
+ "-[TCCDReminderMonitor enqueueReminderWithContext:deferrals:]"
+ "-[TCCDReminderMonitor healthDataAccessCountForBundleIdentifier:]"
+ "-[TCCDReminderMonitor healthDataAccessCountForBundleIdentifier:]_block_invoke"
+ "-[TCCDReminderMonitor isServiceThrottled:atTime:]"
+ "-[TCCDReminderMonitor reminderInfoTextForService:accessCount:]"
+ "-[TCCDReminderMonitor reportResourceUsage:]_block_invoke"
+ "-[TCCDReminderMonitor showReminderPrompt:result:accessCount:]"
+ "A\""
+ "HKDataTypeAccessStore"
+ "REMINDER_ACCESS_INFO_COUNT"
+ "REMINDER_ACCESS_INFO_COUNT_ONE"
+ "T@\"NSArray\",C,N,V_researchMilestoneOverride"
+ "T@\"NSString\",&,N,V_reminderAccessCountFormatLocalizationKey"
+ "T@\"NSString\",&,N,V_reminderAccessCountSingularLocalizationKey"
+ "_reminderAccessCountFormatLocalizationKey"
+ "_reminderAccessCountSingularLocalizationKey"
+ "_researchMilestoneOverride"
+ "accessCount"
+ "com.apple.developer.healthkit.research"
+ "deferrals"
+ "enqueueReminderWithContext:deferrals:"
+ "fetchAccessReportForBundleIdentifier:objectTypes:since:modeMask:completion:"
+ "healthAccessCountForContext:client:"
+ "healthDataAccessCountForBundleIdentifier:"
+ "healthResearchReminderMilestoneOverride"
+ "localizedStringFromNumber:numberStyle:"
+ "milestoneOverrideFromDefaultsForKey:"
+ "reminderAccessCountFormatLocalizationKey"
+ "reminderAccessCountFormatLocalizationKeyNameForServiceName:"
+ "reminderAccessCountSingularLocalizationKey"
+ "reminderAccessCountSingularLocalizationKeyNameForServiceName:"
+ "reminderInfoTextForService:accessCount:"
+ "researchMilestoneOverride"
+ "setReminderAccessCountFormatLocalizationKey:"
+ "setReminderAccessCountSingularLocalizationKey:"
+ "setResearchMilestoneOverride:"
+ "showReminderPrompt:result:accessCount:"
+ "v24@?0@\"HKDataTypeAccessReport\"8@\"NSError\"16"
+ "\xf0\xf0\xf0\xf0!\xf0c"
- "+[TCCDReminderMonitor milestoneOverrideFromDefaults]"
- "-[TCCDReminderMonitor enqueueReminderWithContext:]"
- "-[TCCDReminderMonitor reportResourceUsage:]_block_invoke_2"
- "-[TCCDReminderMonitor showReminderPrompt:result:]"
- "A!"
- "milestoneOverrideFromDefaults"
- "\xf0\xf0\xf0\xf1\xf0c"
```
