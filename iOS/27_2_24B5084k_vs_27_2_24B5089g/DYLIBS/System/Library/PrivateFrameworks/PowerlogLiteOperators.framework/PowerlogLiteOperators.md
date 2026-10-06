## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f7118` | `0x4f791c` | **`+0x804`** |
| `__AUTH_CONST.__cfstring` | `0x78280` | `0x784a0` | **`+0x220`** |
| `__TEXT.__cstring` | `0x608c1` | `0x60a1f` | **`+0x15e`** |
| `__TEXT.__oslogstring` | `0x16a19` | `0x16ad3` | **`+0xba`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50c8` | `0x5140` | **`+0x78`** |
| `__DATA_CONST.__objc_arraydata` | `0x16d50` | `0x16dc0` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x2c60` | `0x2c10` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3f08` | `0x3f58` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x2a58` | `0x2a98` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x4770` | `0x4790` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3150` | `0x3168` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2f7c4` | `0x2f7dc` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x14e08` | `0x14e18` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8480` | `0x8490` | **`+0x10`** |

### Other Changes

```diff

-3486.40.92.0.0
+3486.40.98.0.0

-  Functions: 19887
-  Symbols:   25891
-  CStrings:  19889
+  Functions: 19892
+  Symbols:   25896
+  CStrings:  19910
Symbols:
+ +[PLUrsaUtilities remoteDiagnosticParamsForProcess:]
+ +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
+ ___52+[PLUrsaUtilities remoteDiagnosticParamsForProcess:]_block_invoke
+ ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
+ _normalizedProcessName
CStrings:
+ ",%@"
+ "2033894"
+ "ComponentID"
+ "ComponentName"
+ "ComponentVersion"
+ "DeviceClasses"
+ "Drop Box (Multi-device)"
+ "ExtensionIdentifiers"
+ "HomeKitPrimaryResident"
+ "Nearby"
+ "OpenBandExtraSensesOnLastWLPerMode"
+ "OpenBandExtraSensesPerMode"
+ "OpenBandReadsPerMode"
+ "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
+ "PLUrsaUtilities: requesting remote device diagnostics for %{public}@: %{public}@ (component %{public}@ -> %{public}@)"
+ "RemoteDeviceSelections"
+ "Watch"
+ "Watch,Mac,iPad"
+ "com.apple.PhotoLibraryServices.PhotosDiagnostics"
+ "deferredmediad"
+ "devicesharingd"
```
