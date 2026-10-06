## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d14` | `0x3f80` | **`+0x26c`** |
| `__TEXT.__oslogstring` | `0x987` | `0xa79` | **`+0xf2`** |
| `__TEXT.__cstring` | `0x894` | `0x90c` | **`+0x78`** |
| `__TEXT.__objc_methname` | `0x963` | `0x9d3` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x640` | `0x680` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xb80` | `0xbc0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x470` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1b4` | `0x1d0` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x308` | `0x318` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x240` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x39` | `0x47` | **`+0xe`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-3600.68.61.11.9
+3600.68.61.11.11

-  Functions: 38
-  Symbols:   119
-  CStrings:  225
+  Functions: 40
+  Symbols:   121
+  CStrings:  234
Symbols:
+ _AFIsLinwoodUserSettingOn
+ __AFPreferencesSiriDataSharingOptInStatusVersionWithContext
CStrings:
+ "%s Already performed. Skipping."
+ "%s Opting out Siri Data Sharing for Siri AI user at opt-in version 2.0 (version left unchanged)."
+ "%s hasSiriAIEnabled=%{BOOL}d optInStatusVersion=%ld — cohort does not apply. Marking complete without writing."
+ "-[SiriMigrator _performSiriAIDataSharingOptOutV2IfNeeded]"
+ "B28@0:8B16Q20"
+ "SiriAIDataSharingOptOutV2Completed"
+ "SiriMigratorSiriAIOptOutV2"
+ "_performSiriAIDataSharingOptOutV2IfNeeded"
+ "_shouldOptOutSiriAIDataSharingForHasSiriAIEnabled:optInStatusVersion:"
```
