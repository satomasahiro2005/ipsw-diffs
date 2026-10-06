## HangTracerSettingsClient

> `/System/Library/PrivateFrameworks/HangTracerSettingsClient.framework/HangTracerSettingsClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17278` | `0x18c3c` | **`+0x19c4`** |
| `__TEXT.__oslogstring` | `0x60a` | `0xa2f` | **`+0x425`** |
| `__AUTH_CONST.__objc_const` | `0x1670` | `0x1960` | **`+0x2f0`** |
| `__TEXT.__cstring` | `0x31ce` | `0x3372` | **`+0x1a4`** |
| `__TEXT.__objc_methlist` | `0xc94` | `0xd8c` | **`+0xf8`** |
| `__AUTH.__objc_data` | `0x3c0` | `0x460` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x3980` | `0x3900` | **`-0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xb60` | `0xbc8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x670` | `0x6d8` | **`+0x68`** |
| `__DATA.__bss` | `0x36b0` | `0x3710` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x380` | `0x3d8` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0xdc` | `0x100` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x4b0` | `0x4d0` | **`+0x20`** |
| `__TEXT.__const` | `0x20c2` | `0x20e2` | **`+0x20`** |
| `__TEXT.__ustring` | `0x822` | `0x83c` | **`+0x1a`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x60` | **`+0x10`** |

### Other Changes

```diff

-421.0.0.0.0
+424.0.0.0.0

-  Functions: 806
-  Symbols:   1177
-  CStrings:  589
+  Functions: 851
+  Symbols:   1259
+  CStrings:  617
Symbols:
+ +[HTPerformanceInformation informationWithExtendedAttribute:]
+ +[HTPerformanceInformation parseLostPerfIntervalsFromObject:]
+ -[HTHangExtendedAttributes getMATUExtendedAttributeNamed:forFileAtPath:]
+ -[HTHangExtendedAttributes hangWindow]
+ -[HTHangExtendedAttributes performanceInformation]
+ -[HTHangExtendedAttributes sampleWindow]
+ -[HTHangsDataEntry hangWindow]
+ -[HTHangsDataEntry initWithPath:hangID:creationDate:duration:processBundleID:processPath:processRecord:isBoosted:isBeingProcessed:performanceInformation:hangWindow:sampleWindow:]
+ -[HTHangsDataEntry performanceInformation]
+ -[HTHangsDataEntry sampleWindow]
+ -[HTPerformanceInformation .cxx_destruct]
+ -[HTPerformanceInformation initWithLostPerfIntervals:]
+ -[HTPerformanceInformation lostPerfIntervals]
+ -[HTPerformanceInformation percentActiveDuringHangWindow:]
+ -[HTPerformanceInformation percentActiveForReason:duringHangWindow:]
+ -[HTPerformanceLostPerfInterval .cxx_destruct]
+ -[HTPerformanceLostPerfInterval initWithIntervalWindow:reason:]
+ -[HTPerformanceLostPerfInterval intervalWindow]
+ -[HTPerformanceLostPerfInterval reason]
+ _HTUIInternalInsightLowPowerModeBody
+ _HTUIInternalInsightLowPowerModeBody.str
+ _HTUIInternalInsightLowPowerModeHeadline
+ _HTUIInternalInsightScreenOffThrottlingBody
+ _HTUIInternalInsightScreenOffThrottlingBody.str
+ _HTUIInternalInsightScreenOffThrottlingHeadline
+ _HTUIInternalInsightThermalThrottlingBody
+ _HTUIInternalInsightThermalThrottlingBody.str
+ _HTUIInternalInsightThermalThrottlingHeadline
+ _HTUIInternalInsightsPlacardLabel
+ _HTUIInternalInsightsPlacardLabel.str
+ _HTUIInternalInsightsSectionTitle
+ _HTUIInternalInsightsSectionTitle.str
+ _HTUIInternalNoClientIssuesDetectedFormat
+ _HTUIInternalNoIssuesDetected
+ _HTUIInternalNoIssuesDetected.str
+ _HTUIInternalSystemConditionsCalloutDurationFormat
+ _HTUIInternalSystemConditionsHUDDisabledStatus
+ _HTUIInternalSystemConditionsHUDDisabledStatus.str
+ _HTUIInternalSystemConditionsHUDEnableLink
+ _HTUIInternalSystemConditionsHUDEnableLink.str
+ _HTUIInternalSystemConditionsLostPerfActiveFormat
+ _HTUIInternalSystemConditionsNoneActive
+ _HTUIInternalSystemConditionsNoneActive.str
+ _HTUIInternalSystemConditionsPlacardLabel
+ _HTUIInternalSystemConditionsPlacardLabel.str
+ _HTUIInternalSystemConditionsSectionTitle
+ _HTUIInternalSystemConditionsSectionTitle.str
+ _HTUIInternalSystemConditionsTraceCoverageNotice
+ _HTUIInternalSystemConditionsTraceCoverageNotice.str
+ _MATU_TO_MS
+ _NSStringFromClass
+ _OBJC_CLASS_$_HTPerformanceInformation
+ _OBJC_CLASS_$_HTPerformanceLostPerfInterval
+ _OBJC_IVAR_$_HTHangExtendedAttributes._hangWindow
+ _OBJC_IVAR_$_HTHangExtendedAttributes._performanceInformation
+ _OBJC_IVAR_$_HTHangExtendedAttributes._sampleWindow
+ _OBJC_IVAR_$_HTHangsDataEntry._hangWindow
+ _OBJC_IVAR_$_HTHangsDataEntry._performanceInformation
+ _OBJC_IVAR_$_HTHangsDataEntry._sampleWindow
+ _OBJC_IVAR_$_HTPerformanceInformation._lostPerfIntervals
+ _OBJC_IVAR_$_HTPerformanceLostPerfInterval._intervalWindow
+ _OBJC_IVAR_$_HTPerformanceLostPerfInterval._reason
+ _OBJC_METACLASS_$_HTPerformanceInformation
+ _OBJC_METACLASS_$_HTPerformanceLostPerfInterval
+ __OBJC_$_CLASS_METHODS_HTPerformanceInformation
+ __OBJC_$_INSTANCE_METHODS_HTPerformanceInformation
+ __OBJC_$_INSTANCE_METHODS_HTPerformanceLostPerfInterval
+ __OBJC_$_INSTANCE_VARIABLES_HTPerformanceInformation
+ __OBJC_$_INSTANCE_VARIABLES_HTPerformanceLostPerfInterval
+ __OBJC_$_PROP_LIST_HTPerformanceInformation
+ __OBJC_$_PROP_LIST_HTPerformanceLostPerfInterval
+ __OBJC_CLASS_RO_$_HTPerformanceInformation
+ __OBJC_CLASS_RO_$_HTPerformanceLostPerfInterval
+ __OBJC_METACLASS_RO_$_HTPerformanceInformation
+ __OBJC_METACLASS_RO_$_HTPerformanceLostPerfInterval
+ _kHTExtendedAttributeHangEnd
+ _kHTExtendedAttributeHangStart
+ _kHTExtendedAttributeSampleEnd
+ _kHTExtendedAttributeSampleStart
+ _kHTLostPerfJSONKeyEndMATU
+ _kHTLostPerfJSONKeyIntervals
+ _kHTLostPerfJSONKeyReason
+ _kHTLostPerfJSONKeyStartMATU
+ _objc_retain_x26
+ _objc_retain_x28
+ _objc_retain_x4
+ _strtoull
- -[HTHangsDataEntry initWithPath:hangID:creationDate:duration:processBundleID:processPath:processRecord:isBoosted:isBeingProcessed:]
- ___72-[HTHangsDataFinder findEventsFilteringDeveloperApps:completionHandler:]_block_invoke_2
- ___90-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]_block_invoke_2
- ___90-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]_block_invoke_3
- _objc_retain_x27
CStrings:
+ "%@ – %@ (%@)"
+ "(nil)"
+ "HTHangExtendedAttributes: hangID=%{public}@ perfXattr=%{public}s length=%lu intervalCount=%lu"
+ "HTHangsDataFinder: URL %{public}@ does not have extended attributes, skipping"
+ "HTHangsDataFinder: adding %lu entries to list of results"
+ "HTHangsDataFinder: assembled entry hangID=%{public}@ path=%{public}@ performanceInformation=%{public}s lostPerfIntervalCount=%lu"
+ "HTHangsDataFinder: entry at path %{public}@ is missing bundle id or hang id: skipping."
+ "HTHangsDataFinder: error finding entries for type: %lu"
+ "HTHangsDataFinder: error looking for hang logs at path %{public}@ error: %{public}@"
+ "HTHangsDataFinder: finding hang events (filtering on developer apps: %d)"
+ "HTHangsDataFinder: found %lu pending hangs entries"
+ "HTHangsDataFinder: getting pending hangs list (filtering on developer apps: %d)"
+ "HTHangsDataFinder: looking for data entries at path %{public}@"
+ "HTHangsDataFinder: unable to retrieve information about app with bundle id %{public}@ (Error: %{public}@)"
+ "HTPerformanceInformation: parsed xattr payload (length=%lu intervalCount=%lu)"
+ "HTPerformanceInformation: xattr payload failed to parse as JSON: %{public}@"
+ "HTPerformanceInformation: xattr payload was not a JSON object (class=%{public}@)"
+ "HTUIInternalInsightLowPowerModeBody"
+ "HTUIInternalInsightLowPowerModeHeadline"
+ "HTUIInternalInsightScreenOffThrottlingBody"
+ "HTUIInternalInsightScreenOffThrottlingHeadline"
+ "HTUIInternalInsightThermalThrottlingBody"
+ "HTUIInternalInsightThermalThrottlingHeadline"
+ "HTUIInternalInsightsPlacardLabel"
+ "HTUIInternalInsightsSectionTitle"
+ "HTUIInternalNoClientIssuesDetectedFormat"
+ "HTUIInternalNoIssuesDetected"
+ "HTUIInternalSystemConditionsCalloutDurationFormat"
+ "HTUIInternalSystemConditionsHUDDisabledStatus"
+ "HTUIInternalSystemConditionsHUDEnableLink"
+ "HTUIInternalSystemConditionsLostPerfActiveFormat"
+ "HTUIInternalSystemConditionsNoneActive"
+ "HTUIInternalSystemConditionsPlacardLabel"
+ "HTUIInternalSystemConditionsSectionTitle"
+ "HTUIInternalSystemConditionsTraceCoverageNotice"
+ "No %@ issues detected."
+ "absent"
+ "present"
- "Adding %lu entries to list of results"
- "Entry at path %@ is missing bundle id or hang id: skipping."
- "Error looking for hang logs at path %@ error: %@"
- "Finding hang events (filtering on developer apps: %d)"
- "Found %lu pending hangs entries"
- "Getting pending hangs list (filtering on developer apps: %d)"
- "Looking for data entries at path %@"
- "There was an error finding entries for type: %lu"
- "URL %@ does not have extended attributes, skipping"
- "Unable to retrieve information about app with bundle id %@ (Error: %@)"
```
