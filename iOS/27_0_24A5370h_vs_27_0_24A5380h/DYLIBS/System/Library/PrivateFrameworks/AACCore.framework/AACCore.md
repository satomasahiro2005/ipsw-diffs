## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/AACCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11d1c` | `0x11f20` | **`+0x204`** |
| `__AUTH_CONST.__cfstring` | `0x15e0` | `0x1640` | **`+0x60`** |
| `__TEXT.__cstring` | `0x19d5` | `0x1a29` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x4780` | `0x47b0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xc98` | `0xcb0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1a64` | `0x1a7c` | **`+0x18`** |
| `__DATA.__data` | `0xa50` | `0xa58` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x284` | `0x288` | **`+0x4`** |

### Other Changes

```diff

-53.0.0.0.0
+55.0.0.0.0

-  Functions: 609
-  Symbols:   1486
-  CStrings:  220
+  Functions: 611
+  Symbols:   1490
+  CStrings:  223
Symbols:
+ -[AEAssessmentApplicationDescriptor initWithPID:teamIdentifier:requiresSignatureValidation:]
+ -[AEAssessmentApplicationDescriptor pid]
+ _AECoreNotAliveParticipantPIDsKey
+ _OBJC_IVAR_$_AEAssessmentApplicationDescriptor._pid
CStrings:
+ "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@, pid = %@ }>"
+ "AENotAliveParticipantPIDs"
+ "One or more participant PIDs are not alive."
+ "pid"
- "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@ }>"
```
