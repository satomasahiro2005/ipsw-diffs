## centaurid

> `/usr/libexec/centaurid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x300e4` | `0x30ba8` | **`+0xac4`** |
| `__TEXT.__objc_methname` | `0x316a` | `0x33b6` | **`+0x24c`** |
| `__TEXT.__objc_stubs` | `0x3320` | `0x3560` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x5baf` | `0x5d3e` | **`+0x18f`** |
| `__DATA_CONST.__cfstring` | `0x10c20` | `0x10cc0` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xde0` | `0xe70` | **`+0x90`** |
| `__DATA_CONST.__objc_arraydata` | `0xa188` | `0xa1e0` | **`+0x58`** |
| `__DATA_CONST.__objc_arrayobj` | `0x558` | `0x5a0` | **`+0x48`** |
| `__DATA_CONST.__objc_intobj` | `0x9480` | `0x94b0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x112c` | `0x115c` | **`+0x30`** |
| `__TEXT.__cstring` | `0x19b63` | `0x19b91` | **`+0x2e`** |
| `__TEXT.__objc_methtype` | `0x982` | `0x99c` | **`+0x1a`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x7d8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x7a0` | `0x7a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-123.0.0.0.1
+124.0.0.0.1
+  - /AppleInternal/Library/Frameworks/TapToRadarKit.framework/TapToRadarKit

-  Functions: 623
-  Symbols:   240
-  CStrings:  3477
+  Functions: 628
+  Symbols:   243
+  CStrings:  3509
Symbols:
+ _OBJC_CLASS_$_RadarComponent
+ _OBJC_CLASS_$_RadarDraft
+ _OBJC_CLASS_$_TapToRadarService
CStrings:
+ "%{public}@::%{public}@: createDraft failed: %{public}@"
+ "%{public}@::%{public}@: creating draft"
+ "%{public}@::%{public}@: draft created successfully"
+ "%{public}@::%{public}@: framework not available"
+ "%{public}@::%{public}@: not authorized for this process"
+ "%{public}@::%{public}@: rate limited, reset date: %@"
+ "%{public}@::%{public}@: unexpected authorization status: %ld"
+ "%{public}@::%{public}@: user denied"
+ "B64@0:8@16@24@32@40@48@56"
+ "Connectivity"
+ "EnableBackgroundRadarDraft"
+ "authorizationStatus"
+ "com.apple.DiagnosticExtensions.BluetoothDiagnosticExtension"
+ "com.apple.DiagnosticExtensions.BluetoothHeadset"
+ "com.apple.DiagnosticExtensions.ConnectivityDE"
+ "com.apple.DiagnosticExtensions.WiFi"
+ "com.apple.DiagnosticExtensions.sysdiagnose"
+ "createDraft:forProcessNamed:withDisplayReason:error:"
+ "createTapToRadarDraftWithHostReason:firmwareReason:subsystemName:upTimestamp:monotonicTimestamp:realTimestamp:"
+ "doubleValue"
+ "initWithName:version:identifier:"
+ "isBackgroundRadarDraftEnabled"
+ "overallBootDuration"
+ "radarDescriptionForHostReason:firmwareReason:subsystemName:upTimestamp:monotonicTimestamp:realTimestamp:"
+ "radarTitleForHostReason:firmwareReason:subsystemName:"
+ "rateLimitResetDate"
+ "serviceSettings"
+ "setClassification:"
+ "setComponent:"
+ "setDiagnosticExtensionIDs:"
+ "setIsUserInitiated:"
+ "setKeywords:"
+ "setProblemDescription:"
+ "shared"
+ "stringValue"
- "1671730"
- "1942038"
- "com.apple.DiagnosticExtensions.ConnectivityDE,com.apple.DiagnosticExtensions.WiFi,com.apple.DiagnosticExtensions.BluetoothDiagnosticExtension,com.apple.DiagnosticExtensions.BluetoothHeadset,com.apple.DiagnosticExtensions.sysdiagnose"
```
