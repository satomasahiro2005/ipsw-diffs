## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6bb8` | `0x1e73c8` | **`+0x810`** |
| `__TEXT.__oslogstring` | `0x15b6e` | `0x15dbe` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0x168c0` | `0x16a40` | **`+0x180`** |
| `__AUTH_CONST.__cfstring` | `0x33f80` | `0x340a0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x2694b` | `0x26a1b` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x111c8` | `0x11270` | **`+0xa8`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x2fa0` | `0x3030` | **`+0x90`** |
| `__DATA_CONST.__objc_arraydata` | `0x163c8` | `0x16428` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb208` | `0xb260` | **`+0x58`** |
| `__AUTH.__objc_data` | `0xbe0` | `0xc30` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4580` | `0x45a8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x28c8` | `0x28e0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x16c8` | `0x16dc` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x3c58` | `0x3c68` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe00` | `0xe08` | **`+0x8`** |
| `__DATA.__bss` | `0x20b8` | `0x20b0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xf80` | `0xf88` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3a0` | `0x3a8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 8831
-  Symbols:   11942
-  CStrings:  9088
+  Functions: 8845
+  Symbols:   11965
+  CStrings:  9104
Symbols:
+ +[PLUrsaUtilities generateTTRURLWithRadarParams:context:metadataPath:]
+ +[PLUrsaUtilities writeMetadata:toDirectory:]
+ -[PLAggregateSummarizationService getQueryForDisplayAPL:]
+ -[PLCoalitionAgent buildPLEntryDiffForObject:withNewUsage:hasPrevSample:withStartDate:withEndDate:]
+ -[PLCoalitionAgent logOSMetrics:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldLogCoalitionObject:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldProcessCoalitionID:seenCoalitionIDs:]
+ -[PLMetricsFormatterJSON addDisplayAPL:userData:forIndex:]
+ -[PLUrsaViolationContext .cxx_destruct]
+ -[PLUrsaViolationContext init]
+ -[PLUrsaViolationContext internalOnlyRule]
+ -[PLUrsaViolationContext issueType]
+ -[PLUrsaViolationContext mitigationsEnabled]
+ -[PLUrsaViolationContext procName]
+ -[PLUrsaViolationContext ruleID]
+ -[PLUrsaViolationContext setInternalOnlyRule:]
+ -[PLUrsaViolationContext setIssueType:]
+ -[PLUrsaViolationContext setMitigationsEnabled:]
+ -[PLUrsaViolationContext setProcName:]
+ -[PLUrsaViolationContext setRuleID:]
+ -[PLUrsaViolationContext setViolationTime:]
+ -[PLUrsaViolationContext violationTime]
+ GCC_except_table216
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_PLUrsaViolationContext
+ _OBJC_IVAR_$_PLMetricsFormatterJSON.appDisplayXAPLMapping
+ _OBJC_IVAR_$_PLUrsaViolationContext._internalOnlyRule
+ _OBJC_IVAR_$_PLUrsaViolationContext._issueType
+ _OBJC_IVAR_$_PLUrsaViolationContext._mitigationsEnabled
+ _OBJC_IVAR_$_PLUrsaViolationContext._procName
+ _OBJC_IVAR_$_PLUrsaViolationContext._ruleID
+ _OBJC_IVAR_$_PLUrsaViolationContext._violationTime
+ _OBJC_METACLASS_$_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_METHODS_PLUrsaViolationContext
+ __OBJC_$_INSTANCE_VARIABLES_PLUrsaViolationContext
+ __OBJC_$_PROP_LIST_PLUrsaViolationContext
+ __OBJC_CLASS_RO_$_PLUrsaViolationContext
+ __OBJC_METACLASS_RO_$_PLUrsaViolationContext
+ ___57-[PLAggregateSummarizationService getQueryForDisplayAPL:]_block_invoke
+ ___block_descriptor_41_e8_32s_e17_"NSArray"16?0d8ls32l8
- +[PLUrsaUtilities generateTTRURLWithRadarParams:procName:mitigationsEnabled:violationTime:metadataPath:issueType:]
- -[PLAggregateSummarizationService getQueryForDisplayAPL]
- -[PLCoalitionAgent buildPLEntryDiffForObject:withStartDate:withEndDate:]
- -[PLCoalitionAgent logCoalitionObjectDifference]
- -[PLCoalitionAgent logOSMetrics:]
- -[PLCoalitionAgent shouldLogCoalitionObject:]
- -[PLCoalitionDataObject hasPrevSample]
- -[PLCoalitionDataObject prevCoalResourceUsage]
- -[PLMetricsFormatterJSON addDisplayAPL:userData:]
- GCC_except_table173
- GCC_except_table219
- _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
- _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
- ___48-[PLCoalitionAgent logCoalitionObjectDifference]_block_invoke
- ___56-[PLAggregateSummarizationService getQueryForDisplayAPL]_block_invoke
- _logCoalitionObjectDifference.classDebugEnabled
- _logCoalitionObjectDifference.defaultOnce
CStrings:
+ "\n\nNOTE: This issue was caught by a detection rule that is enabled on internal builds only. Mitigations for this rule are not applied on customer devices."
+ "                           SELECT bundleID AS %@, SUM(%f * Frames * (%f*AvgRed + %f*AvgGreen + %f*AvgBlue))/SUM(Frames) %@, SUM(Frames) %@ FROM %@                            WHERE timestamp >= %f AND timestamp < %f                           GROUP BY %@;"
+ "\""
+ "$rulePolicy"
+ "AveragePictureLevelX"
+ "DisplayXAPL"
+ "PLDisplayAgent_EventBackward_APLStats"
+ "PLDisplayAgent_EventBackward_APLStatsX"
+ "PLUrsaUtilities: %{public}@ exists but is not a directory"
+ "PLUrsaUtilities: could not remove existing metadata at %{public}@, overwriting in place: %{public}@"
+ "PLUrsaUtilities: could not set permissions on %{public}@, continuing: %{public}@"
+ "PLUrsaUtilities: could not write metadata to %{public}@, falling back to %{public}@"
+ "PLUrsaUtilities: created directory at: %{public}@"
+ "PLUrsaUtilities: failed to create directory %{public}@: errno=%d (%{public}s) error=%{public}@"
+ "PLUrsaUtilities: failed to create metadata file URL in %{public}@"
+ "PLUrsaUtilities: failed to write metadata to %{public}@: errno=%d (%{public}s) error=%{public}@"
+ "PLUrsaUtilities: failed to write metadata to both %{public}@ and %{public}@"
+ "PLUrsaUtilities: invalid metadata directory"
+ "PLUrsaUtilities: nil violation context"
+ "TotalFrameCountX"
+ "displayX_apl"
+ "generateTTRURL: called with issueType = %d, ruleID = %d, internalOnlyRule = %d"
+ "internalOnlyRule"
+ "ruleID"
- "                           SELECT bundleID AS %@, SUM(%f * Frames * (%f*AvgRed + %f*AvgGreen + %f*AvgBlue))/SUM(Frames) %@, SUM(Frames) %@ FROM PLDisplayAgent_EventBackward_APLStats                           WHERE timestamp >= %f AND timestamp < %f                           GROUP BY %@;"
- "-[PLCoalitionAgent logCoalitionObjectDifference]"
- "PLUrsaUtilities: created Ursa directory at: %{public}@"
- "PLUrsaUtilities: failed to create Ursa directory: %{public}@"
- "PLUrsaUtilities: failed to create metadata file URL"
- "PLUrsaUtilities: failed to create metadata file with permissions"
- "generateTTRURL: called with issueType = %d"
- "self.lastCoalitionObjectDictionary=%@"
```
