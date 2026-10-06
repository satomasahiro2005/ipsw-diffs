## BatteryUsageUI

> `/System/Library/PreferenceBundles/BatteryUsageUI.bundle/BatteryUsageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x119984` | `0x11a220` | **`+0x89c`** |
| `__TEXT.__oslogstring` | `0x3405` | `0x3655` | **`+0x250`** |
| `__DATA.__objc_const` | `0x6860` | `0x6a20` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0xa316` | `0xa476` | **`+0x160`** |
| `__TEXT.__objc_stubs` | `0x8900` | `0x8a60` | **`+0x160`** |
| `__TEXT.__cstring` | `0x97ae` | `0x989e` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x3984` | `0x3a44` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x2b40` | `0x2ba0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1b08` | `0x1b58` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x91a0` | `0x91e0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3fc0` | `0x3ff0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xd89` | `0xd69` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1eb2` | `0x1ed2` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x34d0` | `0x34f0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x450` | `0x468` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1ff0` | `0x2008` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x648` | `0x660` | **`+0x18`** |
| `__TEXT.__const` | `0x9a14` | `0x9a24` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xbce` | `0xbde` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2778` | `0x2784` | **`+0xc`** |
| `__DATA.__data` | `0x56a0` | `0x56a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x240` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x150` | `0x158` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 5241
-  Symbols:   751
-  CStrings:  3949
+  Functions: 5261
+  Symbols:   756
+  CStrings:  3983
Symbols:
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_PLUrsaViolationContext
+ _OBJC_METACLASS_$_PLUrsaViolationContext
+ ___error
+ _strerror
CStrings:
+ "\n\nNOTE: This issue was caught by a detection rule that is enabled on internal builds only. Mitigations for this rule are not applied on customer devices."
+ "\""
+ "$rulePolicy"
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
+ "PLUrsaViolationContext"
+ "T@\"NSDate\",&,N,V_violationTime"
+ "T@\"NSString\",C,N,V_procName"
+ "TB,N,V_internalOnlyRule"
+ "TB,N,V_mitigationsEnabled"
+ "Ti,N,V_issueType"
+ "Ti,N,V_ruleID"
+ "_internalOnlyRule"
+ "_issueType"
+ "_mitigationsEnabled"
+ "_procName"
+ "_ruleID"
+ "_violationTime"
+ "awdlInactivityTimeout"
+ "code"
+ "com.apple.graphic-icon.apps-on-current-device"
+ "generateTTRURL: called with issueType = %d, ruleID = %d, internalOnlyRule = %d"
+ "generateTTRURLWithRadarParams:context:metadataPath:"
+ "internalOnlyRule"
+ "mitigationsEnabled"
+ "procName"
+ "ruleID"
+ "setAttributes:ofItemAtPath:error:"
+ "setInternalOnlyRule:"
+ "setIssueType:"
+ "setMitigationsEnabled:"
+ "setProcName:"
+ "setRuleID:"
+ "setViolationTime:"
+ "violationTime"
+ "writeMetadata:toDirectory:"
+ "writeToURL:options:error:"
- "@56@0:8@16@24B32@36@44i52"
- "PLUrsaUtilities: created Ursa directory at: %{public}@"
- "PLUrsaUtilities: failed to create Ursa directory: %{public}@"
- "PLUrsaUtilities: failed to create metadata file URL"
- "PLUrsaUtilities: failed to create metadata file with permissions"
- "com.apple.graphic-icon.apps-on-%@"
- "createFileAtPath:contents:attributes:"
- "fileExistsAtPath:"
- "generateTTRURL: called with issueType = %d"
- "generateTTRURLWithRadarParams:procName:mitigationsEnabled:violationTime:metadataPath:issueType:"
- "initWithAttributedString:"
- "numberWithUnsignedShort:"
```
