## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/AutomaticAssessmentConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78b4` | `0x7a7c` | **`+0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0xfe0` | `0x1010` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b0` | `0x6e0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x854` | `0x87c` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x346` | `0x34f` | **`+0x9`** |
| `__DATA.__objc_ivar` | `0x100` | `0x104` | **`+0x4`** |

### Other Changes

```diff

-53.0.0.0.0
+55.0.0.0.0

-  Functions: 252
-  Symbols:   443
-  CStrings:  17
+  Functions: 256
+  Symbols:   447
+  CStrings:  18
Symbols:
+ -[AEAssessmentApplication initWithBundleIdentifier:teamIdentifier:requiresSignatureValidation:pid:]
+ -[AEAssessmentApplication initWithPID:]
+ -[AEAssessmentApplication initWithPID:teamIdentifier:]
+ -[AEAssessmentApplication pid]
+ _OBJC_IVAR_$_AEAssessmentApplication._pid
- -[AEAssessmentApplication initWithBundleIdentifier:teamIdentifier:requiresSignatureValidation:]
CStrings:
+ ""
+ "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureChecks = %@, pid = %@ }>"
- "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureChecks = %@ }>"
```
