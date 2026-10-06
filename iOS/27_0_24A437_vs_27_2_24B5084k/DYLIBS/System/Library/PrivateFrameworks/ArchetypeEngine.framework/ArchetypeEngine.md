## ArchetypeEngine

> `/System/Library/PrivateFrameworks/ArchetypeEngine.framework/ArchetypeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c454` | `0xa01fc` | **`+0x3da8`** |
| `__TEXT.__eh_frame` | `0x4968` | `0x4db0` | **`+0x448`** |
| `__TEXT.__oslogstring` | `0x2bf9` | `0x2fcf` | **`+0x3d6`** |
| `__AUTH_CONST.__const` | `0x24e0` | `0x2678` | **`+0x198`** |
| `__TEXT.__const` | `0x21c8` | `0x22e8` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x18c8` | `0x19c8` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1025` | `0x10d5` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x1490` | `0x1514` | **`+0x84`** |
| `__TEXT.__constg_swiftt` | `0xca0` | `0xd1c` | **`+0x7c`** |
| `__TEXT.__swift5_capture` | `0xb0c` | `0xb74` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x298` | `0x2d4` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x1da8` | `0x1de0` | **`+0x38`** |
| `__DATA.__data` | `0xde0` | `0xe18` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x9a0` | `0x9d8` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0xa51` | `0xa82` | **`+0x31`** |
| `__AUTH_CONST.__objc_const` | `0x10c8` | `0x10f0` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x620` | `0x640` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xf0` | `0x108` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x10c` | `0x124` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x3fc` | `0x410` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x768` | **`+0x10`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xb4` | `0xb8` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x34` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-41.11.0.0.0
+41.13.0.0.0

-  Functions: 2809
+  Functions: 2897

-  CStrings:  253
+  CStrings:  267
CStrings:
+ "LearningPlatformWritingStyleRetrieval: found %ld stale profiles for cleanup before %s"
+ "LearningPlatformWritingStyleRetrieval: stale cleanup hit its %ld-result cap; the remainder will be cleaned next cycle"
+ "PersonalContextXPCServer: cleanUpStaleWritingStyleProfiles called"
+ "PersonalContextXPCServer: cleanUpStaleWritingStyleProfiles finished"
+ "WritingAssistantStyleProfileOrchestrator: removing %ld stale profiles in batch"
+ "WritingAssistantStyleProfileOrchestrator: running stale profile cleanup for profiles before %s (force: %{bool}d)"
+ "WritingAssistantStyleProfileOrchestrator: stale profile cleanup already in progress, dropping duplicate request"
+ "WritingAssistantStyleProfileOrchestrator: stale profile cleanup failed: %s"
+ "WritingAssistantStyleProfileOrchestrator: stale profile cleanup not due, skipping"
+ "WritingAssistantStyleProfileOrchestrator: stale profile cleanup removed %ld profiles"
+ "WritingStyleProfileLastStaleCleanupDate"
+ "WritingStyleProfileStaleCleanupIntervalSeconds"
+ "WritingStyleProfileStalenessThresholdSeconds"
+ "com.apple.Archetype"
```
