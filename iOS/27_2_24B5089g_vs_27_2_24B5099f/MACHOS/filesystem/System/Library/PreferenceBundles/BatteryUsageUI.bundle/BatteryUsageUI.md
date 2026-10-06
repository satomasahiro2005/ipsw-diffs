## BatteryUsageUI

> `/System/Library/PreferenceBundles/BatteryUsageUI.bundle/BatteryUsageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a73c` | `0x11b370` | **`+0xc34`** |
| `__TEXT.__swift5_typeref` | `0xf19a` | `0xf6da` | **`+0x540`** |
| `__TEXT.__auth_stubs` | `0x3ff0` | `0x4130` | **`+0x140`** |
| `__TEXT.__cstring` | `0x99fe` | `0x9aae` | **`+0xb0`** |
| `__DATA_CONST.__auth_got` | `0x2008` | `0x20a8` | **`+0xa0`** |
| `__DATA.__bss` | `0xb0a8` | `0xb138` | **`+0x90`** |
| `__DATA_CONST.__auth_ptr` | `0xdc0` | `0xe50` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x9500` | `0x9580` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x8ac0` | `0x8b40` | **`+0x80`** |
| `__DATA.__data` | `0x56a8` | `0x5710` | **`+0x68`** |
| `__TEXT.__objc_methname` | `0xa4e6` | `0xa546` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1ed2` | `0x1e82` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x2784` | `0x273c` | **`-0x48`** |
| `__DATA_CONST.__const` | `0x71c0` | `0x7200` | **`+0x40`** |
| `__TEXT.__const` | `0x9a24` | `0x99f4` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x8c8` | `0x8ec` | **`+0x24`** |
| `__DATA.__objc_const` | `0x6a20` | `0x6a00` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x2bb8` | `0x2bd8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf98` | `0xfb8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x8f0` | `0x8d0` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x2fec` | `0x2fcc` | **`-0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xa90` | `0xaa8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x3705` | `0x3715` | **`+0x10`** |
| `__DATA.__objc_data` | `0x1b58` | `0x1b50` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2c0` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x508` | `0x50c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3486.40.98.0.0
+3486.40.112.0.0

-  Functions: 5268
-  Symbols:   756
-  CStrings:  4013
+  Functions: 5283
+  Symbols:   759
+  CStrings:  4022
Symbols:
+ _CGRectGetHeight
+ _CGRectGetMinY
+ _CGRectGetWidth
CStrings:
+ ","
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "ProportionalHStack: invalid ratios, skipping layout"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "componentsSeparatedByString:"
+ "diagnosticExtensionIDsForProcess:"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
+ "lowercaseString"
+ "stringByTrimmingCharactersInSet:"
+ "whitespaceCharacterSet"
- ",%@"
- "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
- "shouldCollectCPLDiagnosticExtensionForProcess:"
```
