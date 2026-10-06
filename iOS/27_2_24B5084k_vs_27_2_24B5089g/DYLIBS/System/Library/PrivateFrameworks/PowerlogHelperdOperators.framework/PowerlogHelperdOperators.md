## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e73c8` | `0x1e78c8` | **`+0x500`** |
| `__AUTH_CONST.__cfstring` | `0x340a0` | `0x34240` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x26a1b` | `0x26afd` | **`+0xe2`** |
| `__TEXT.__oslogstring` | `0x15dbe` | `0x15e78` | **`+0xba`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3ac0` | `0x3b38` | **`+0x78`** |
| `__DATA_CONST.__objc_arraydata` | `0x16428` | `0x16498` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x1a40` | `0x1a80` | **`+0x40`** |
| `__AUTH.__objc_data` | `0xc30` | `0xc08` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x1860` | `0x1888` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3030` | `0x3048` | **`+0x18`** |
| `__DATA.__bss` | `0x20b0` | `0x20c8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x11270` | `0x11288` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xb260` | `0xb270` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3c68` | `0x3c78` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x3b8` | `0x3c0` | **`+0x8`** |

### Other Changes

```diff

-3486.40.92.0.0
+3486.40.98.0.0

-  Functions: 8845
-  Symbols:   11965
-  CStrings:  9104
+  Functions: 8852
+  Symbols:   11974
+  CStrings:  9119
Symbols:
+ +[PLUrsaUtilities remoteDiagnosticParamsForProcess:]
+ +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
+ ___52+[PLUrsaUtilities remoteDiagnosticParamsForProcess:]_block_invoke
+ ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
+ _normalizedProcessName
+ _remoteDiagnosticParamsForProcess:.mapping
+ _remoteDiagnosticParamsForProcess:.onceToken
+ _shouldCollectCPLDiagnosticExtensionForProcess:.cplDiagnosticExtensionProcesses
+ _shouldCollectCPLDiagnosticExtensionForProcess:.onceToken
CStrings:
+ ",%@"
+ "2033894"
+ "Drop Box (Multi-device)"
+ "ExtensionIdentifiers"
+ "HomeKitPrimaryResident"
+ "Nearby"
+ "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
+ "PLUrsaUtilities: requesting remote device diagnostics for %{public}@: %{public}@ (component %{public}@ -> %{public}@)"
+ "PowerExceptions"
+ "RemoteDeviceSelections"
+ "Watch"
+ "Watch,Mac,iPad"
+ "com.apple.PhotoLibraryServices.PhotosDiagnostics"
+ "deferredmediad"
+ "devicesharingd"
```
