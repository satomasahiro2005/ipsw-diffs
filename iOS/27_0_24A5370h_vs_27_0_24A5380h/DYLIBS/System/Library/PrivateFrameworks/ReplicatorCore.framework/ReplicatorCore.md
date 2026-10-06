## ReplicatorCore

> `/System/Library/PrivateFrameworks/ReplicatorCore.framework/ReplicatorCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b13c` | `0x7c2bc` | **`+0x1180`** |
| `__TEXT.__oslogstring` | `0x2496` | `0x2566` | **`+0xd0`** |
| `__AUTH_CONST.__objc_const` | `0x1b38` | `0x1bf0` | **`+0xb8`** |
| `__AUTH.__data` | `0x100` | `0x1b0` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xc80` | `0xd20` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xd3c` | `0xdb8` | **`+0x7c`** |
| `__TEXT.__const` | `0xf08` | `0xf68` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x1fe0` | `0x2020` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x13f8` | `0x13c8` | **`-0x30`** |
| `__TEXT.__cstring` | `0xa16` | `0x9e6` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0xe3b` | `0xe6b` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x704` | `0x730` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x1008` | `0x1028` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1938` | `0x1950` | **`+0x18`** |
| `__DATA.__common` | `0x30` | `0x18` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x90` | `0xa8` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x6bd` | `0x6cd` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x64` | `0x68` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x2c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-168.0.0.0.0
+172.0.0.0.0

-  - /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter

-  Functions: 902
-  Symbols:   622
-  CStrings:  228
+  Functions: 915
+  Symbols:   628
+  CStrings:  231
Symbols:
+ _BSCurrentUserDirectory
+ __DATA__TtC14ReplicatorCore20AppGroupFileMigrator
+ __IVARS__TtC14ReplicatorCore20AppGroupFileMigrator
+ __METACLASS_DATA__TtC14ReplicatorCore20AppGroupFileMigrator
+ _symbolic $s14ReplicatorCore12FileManagingP
+ _symbolic _____ 14ReplicatorCore20AppGroupFileMigratorC
+ _symbolic _____Sg 16ReplicatorEngine19PersonaMonitorEventO6DeviceV
+ _symbolic ______p 14ReplicatorCore12FileManagingP
- _swift_willThrowTypedImpl
- _symbolic ______p s5ErrorP
CStrings:
+ "Cannot remove incomplete data from vault: %{public}@"
+ "Detected incomplete vault migration"
+ "Failed to move data from legacy location to vault: %{public}@"
+ "Moving data from legacy location to vault"
+ "No data to migrate to the vault"
- "Could not create migration client: "
- "Could not start orphaned file remover: %@"
```
