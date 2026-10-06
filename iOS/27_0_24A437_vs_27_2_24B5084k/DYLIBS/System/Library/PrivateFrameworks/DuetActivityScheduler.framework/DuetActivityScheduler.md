## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f2a0` | `0x3f398` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x41a7` | `0x4276` | **`+0xcf`** |
| `__AUTH_CONST.__cfstring` | `0x5280` | `0x5320` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x7f88` | `0x7fb8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4a00` | `0x4a30` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2938` | `0x2958` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x32ed` | `0x32d7` | **`-0x16`** |
| `__DATA.__objc_ivar` | `0x4a4` | `0x4a8` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1624` | `0x1628` | **`+0x4`** |

### Other Changes

```diff

-2467.2.2.0.0
+2467.40.37.0.0

-  Functions: 1689
-  Symbols:   2840
-  CStrings:  1004
+  Functions: 1693
+  Symbols:   2845
+  CStrings:  1009
Symbols:
+ -[_DASActivity isMindPalaceAmbientActivity]
+ -[_DASActivity isMindPalaceUserInitiatedActivity]
+ -[_DASContinuedProcessingWrapper hostManagedProgressUI]
+ -[_DASContinuedProcessingWrapper setHostManagedProgressUI:]
+ GCC_except_table140
+ _OBJC_IVAR_$__DASContinuedProcessingWrapper._hostManagedProgressUI
- GCC_except_table138
CStrings:
+ "ERROR Submitting %@: Please contact us to prevent this activity from getting rejected. Configuration: %@"
+ "Verify: dastool compute activityTimeline %@ --start -48h"
+ "com.apple.mindpalace.executeCompaction"
+ "com.apple.mindpalace.executeCompactionUserInitiated"
+ "com.apple.mindpalace.executeExtraction"
+ "com.apple.mindpalace.executeExtractionUserInitiated"
+ "hostManagedProgressUI"
- "ERROR Submitting %@: Please contact das-core@group.apple.com to prevent this activity from getting rejected. Configuration: %@"
- "Verify: dastool compute activityTimeline %@ --last 48"
```
