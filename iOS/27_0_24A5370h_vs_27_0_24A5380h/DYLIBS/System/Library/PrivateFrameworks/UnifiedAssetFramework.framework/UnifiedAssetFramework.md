## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/UnifiedAssetFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7761c` | `0x778ac` | **`+0x290`** |
| `__AUTH_CONST.__cfstring` | `0x5060` | `0x51c0` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x4570` | `0x46c0` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x570` | `0x6b0` | **`+0x140`** |
| `__TEXT.__cstring` | `0xb73d` | `0xb840` | **`+0x103`** |
| `__DATA_DIRTY.__objc_data` | `0xb40` | `0xa50` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0xedd1` | `0xecfe` | **`-0xd3`** |
| `__TEXT.__objc_methlist` | `0x3640` | `0x36c0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x2670` | `0x26a0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ce8` | `0x1d10` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x310` | `0x320` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x11e8` | `0x11f8` | **`+0x10`** |
| `__DATA.__common` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-3600.67.1.0.0
+3600.70.1.0.0

-  Functions: 1449
-  Symbols:   2745
-  CStrings:  2105
+  Functions: 1457
+  Symbols:   2767
+  CStrings:  2114
Symbols:
+ +[UAFAssetOriginReport sourceStringForEntry:]
+ +[UAFAutoAssetHistory persistAssetSetInfoLocked:atomicEntries:autoAssetSet:isEliminating:reason:atomicInstanceMetadata:originReport:]
+ +[UAFBiomeInstrumenter logAssetSetDownloadEvent:atomicInstanceMetadata:entries:errorCodes:assetOriginReport:assetSetDailyStatusEventType:]
+ +[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]
+ +[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]
+ -[UAFAssetOriginReport .cxx_destruct]
+ -[UAFAssetOriginReport _originDictForMAEntry:]
+ -[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]
+ -[UAFAssetOriginReport atomicInstanceUUID]
+ -[UAFAssetOriginReport initWithAutoAssetSet:atomicInstance:atomicEntries:error:]
+ -[UAFAssetOriginReport originEntryForSpecifier:]
+ -[UAFAssetOriginReport originInfoForSpecifier:]
+ -[UAFAssetOriginReport reportValid]
+ -[UAFAssetOriginReport underlyingMAReport]
+ GCC_except_table111
+ GCC_except_table120
+ GCC_except_table96
+ _OBJC_CLASS_$_UAFAssetOriginReport
+ _OBJC_IVAR_$_UAFAssetOriginReport._assetSetIdentifier
+ _OBJC_IVAR_$_UAFAssetOriginReport._atomicInstanceUUID
+ _OBJC_IVAR_$_UAFAssetOriginReport._specifierToOriginEntry
+ _OBJC_IVAR_$_UAFAssetOriginReport._underlyingMAReport
+ _OBJC_METACLASS_$_UAFAssetOriginReport
+ __OBJC_$_CLASS_METHODS_UAFAssetOriginReport
+ __OBJC_$_INSTANCE_METHODS_UAFAssetOriginReport
+ __OBJC_$_INSTANCE_VARIABLES_UAFAssetOriginReport
+ __OBJC_$_PROP_LIST_UAFAssetOriginReport
+ __OBJC_CLASS_RO_$_UAFAssetOriginReport
+ __OBJC_METACLASS_RO_$_UAFAssetOriginReport
+ ___block_descriptor_64_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- +[UAFAutoAssetHistory persistAssetSetInfoLocked:atomicEntries:autoAssetSet:isEliminating:reason:]
- +[UAFAutoAssetManager assetSetEmpty:]
- +[UAFBiomeInstrumenter _collectAssetOriginMetadata:atomicInstanceOriginMetadata:entries:]
- +[UAFBiomeInstrumenter logAssetSetDownloadEvent:atomicInstanceMetadata:entries:errorCodes:assetSetDailyStatusEventType:]
- +[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetSetDailyStatusEventType:]
- +[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetSetDailyStatusEventType:]
- GCC_except_table112
- GCC_except_table121
CStrings:
+ "%s UAFAssetOriginReport: lockedAtomicEntriesOriginReportSync returned nil for '%{public}@'/%{public}@: %{public}@"
+ "+[UAFAutoAssetHistory persistAssetSetInfoLocked:atomicEntries:autoAssetSet:isEliminating:reason:atomicInstanceMetadata:originReport:]"
+ "+[UAFBiomeInstrumenter logAssetSetDownloadEvent:atomicInstanceMetadata:entries:errorCodes:assetOriginReport:assetSetDailyStatusEventType:]"
+ "+[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]"
+ "+[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetOriginReport:assetSetDailyStatusEventType:]"
+ "-[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]"
+ "BMUAFAssetUAFAssetSource"
+ "MAAutoAssetSetOriginEntry"
+ "UAFDiagnostics"
+ "_Factory_Install"
+ "_Over_The_Air"
+ "_PreSoftware_Update_Staging"
+ "assetAvailableOSBuild"
+ "assetDownloadedOSBuild"
+ "atomicInstanceMetadata"
+ "atomicInstanceUUID"
+ "fromFactory"
+ "fromPSUS"
- "%s Auto asset set %{public}@ is desired but newest published atomic instance %{public}@ from catalog %{public}@ contains no assets"
- "%s Auto asset set %{public}@ is desired but no atomic instance is available"
- "%s Could not retrieve the asset origin metadata for auto asset set %{public}@ atomic instance %{public}@ : %{public}@"
- "+[UAFAutoAssetHistory persistAssetSetInfoLocked:atomicEntries:autoAssetSet:isEliminating:reason:]"
- "+[UAFBiomeInstrumenter _collectAssetOriginMetadata:atomicInstanceOriginMetadata:entries:]"
- "+[UAFBiomeInstrumenter logAssetSetDownloadEvent:atomicInstanceMetadata:entries:errorCodes:assetSetDailyStatusEventType:]"
- "+[UAFInstrumentationProvider _emitAssetDailyStatusEvent:atomicInstanceMetadata:entries:assetSetDailyStatusEventType:]"
- "+[UAFInstrumentationProvider logUAFAssetSetDailyStatus:atomicInstanceMetadata:entries:assetSetDailyStatusEventType:]"
- "Collection of Auto Asset Set Origin"
```
