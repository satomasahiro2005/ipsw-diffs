## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f65e8` | `0x4f7118` | **`+0xb30`** |
| `__TEXT.__oslogstring` | `0x167b9` | `0x16a19` | **`+0x260`** |
| `__TEXT.__cstring` | `0x60733` | `0x608c1` | **`+0x18e`** |
| `__AUTH_CONST.__objc_const` | `0x38a50` | `0x38bb0` | **`+0x160`** |
| `__AUTH_CONST.__cfstring` | `0x781a0` | `0x78280` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x2f71c` | `0x2f7c4` | **`+0xa8`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30d8` | `0x3150` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x14da8` | `0x14e08` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2c10` | `0x2c60` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x16d00` | `0x16d50` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x6e70` | `0x6ea0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2d68` | `0x2d84` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x1f94` | `0x1fa4` | **`+0x10`** |
| `__TEXT.__const` | `0x2cb0` | `0x2cc0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1958` | `0x1960` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa70` | `0xa78` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb48` | `0xb50` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x4778` | `0x4770` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x8478` | `0x8480` | **`+0x8`** |

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 19875
-  Symbols:   25867
-  CStrings:  19863
+  Functions: 19887
+  Symbols:   25891
+  CStrings:  19889
Symbols:
+ +[PLUrsaUtilities generateTTRURLWithRadarParams:context:metadataPath:]
+ +[PLUrsaUtilities writeMetadata:toDirectory:]
+ -[PLCoalitionAgent buildPLEntryDiffForObject:withNewUsage:hasPrevSample:withStartDate:withEndDate:]
+ -[PLCoalitionAgent logOSMetrics:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldLogCoalitionObject:withNewUsage:hasPrevSample:]
+ -[PLCoalitionAgent shouldProcessCoalitionID:seenCoalitionIDs:]
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
+ GCC_except_table171
+ GCC_except_table216
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_PLUrsaViolationContext
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
- +[PLUrsaUtilities generateTTRURLWithRadarParams:procName:mitigationsEnabled:violationTime:metadataPath:issueType:]
- -[PLCoalitionAgent buildPLEntryDiffForObject:withStartDate:withEndDate:]
- -[PLCoalitionAgent logCoalitionObjectDifference]
- -[PLCoalitionAgent logOSMetrics:]
- -[PLCoalitionAgent shouldLogCoalitionObject:]
- -[PLCoalitionDataObject hasPrevSample]
- -[PLCoalitionDataObject prevCoalResourceUsage]
- GCC_except_table173
- GCC_except_table219
- _OBJC_IVAR_$_PLCoalitionDataObject._hasPrevSample
- _OBJC_IVAR_$_PLCoalitionDataObject._prevCoalResourceUsage
- ___48-[PLCoalitionAgent logCoalitionObjectDifference]_block_invoke
CStrings:
+ "\n\nNOTE: This issue was caught by a detection rule that is enabled on internal builds only. Mitigations for this rule are not applied on customer devices."
+ "$rulePolicy"
+ "Feature disabled int=%d adg=%d forceDisable=%d"
+ "InternalOnlyRule"
+ "J775d"
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
+ "RuleID"
+ "UrsaForceDisable"
+ "debugDataCompressionFailed"
+ "debugDataDumpSuccess"
+ "debugDataGetFail"
+ "debugDataGetSuccess"
+ "debugDataHandoffToRxBurn"
+ "debugDataRequestDropped"
+ "debugDataRequestDump"
+ "debugDataTrimCalled"
+ "generateTTRURL: called with issueType = %d, ruleID = %d, internalOnlyRule = %d"
+ "idleStackFlowVCurveCDPAtSlowGC"
+ "internalOnlyRule"
+ "ruleID"
+ "sanitizeDoneTime"
+ "sanitizeReject"
+ "sanitizeStartTime"
+ "sanitizeStatus"
+ "timer_read64_synced"
- "-[PLCoalitionAgent logCoalitionObjectDifference]"
- "Feature disabled int=%d adg=%d"
- "PLUrsaUtilities: created Ursa directory at: %{public}@"
- "PLUrsaUtilities: failed to create Ursa directory: %{public}@"
- "PLUrsaUtilities: failed to create metadata file URL"
- "PLUrsaUtilities: failed to create metadata file with permissions"
- "generateTTRURL: called with issueType = %d"
- "idleStackPurgeableValidityCurveAtSlowGC"
- "self.lastCoalitionObjectDictionary=%@"
```
