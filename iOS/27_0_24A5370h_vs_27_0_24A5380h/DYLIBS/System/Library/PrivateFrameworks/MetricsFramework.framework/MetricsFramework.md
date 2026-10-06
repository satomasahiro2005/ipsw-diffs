## MetricsFramework

> `/System/Library/PrivateFrameworks/MetricsFramework.framework/MetricsFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10c85c` | `0x10d5d8` | **`+0xd7c`** |
| `__DATA_DIRTY.__data` | `0x2dc0` | `0x33b0` | **`+0x5f0`** |
| `__AUTH.__data` | `0x4c00` | `0x47c8` | **`-0x438`** |
| `__DATA.__bss` | `0xd300` | `0xd000` | **`-0x300`** |
| `__DATA_DIRTY.__bss` | `0x1d80` | `0x2080` | **`+0x300`** |
| `__AUTH.__objc_data` | `0xfe8` | `0xe58` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x770` | `0x900` | **`+0x190`** |
| `__DATA.__data` | `0x2218` | `0x20a8` | **`-0x170`** |
| `__TEXT.__cstring` | `0x7080` | `0x71b0` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0x4420` | `0x44e0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x6a2c` | `0x6acc` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x57e8` | `0x5848` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x85c0` | `0x8610` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x5384` | `0x53d4` | **`+0x50`** |
| `__DATA.__common` | `0x1e0` | `0x1b0` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `0xf0` | `0x120` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x4da0` | `0x4dd0` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x56f8` | `0x5718` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xbb0` | `0xbc8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3aa8` | `0x3ac0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x230` | `0x244` | **`+0x14`** |
| `__TEXT.__const` | `0xd0a0` | `0xd0b0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x52c` | `0x53c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2e96` | `0x2ea4` | **`+0xe`** |
| `__TEXT.__swift5_types` | `0x474` | `0x478` | **`+0x4`** |

### Other Changes

```diff

-3600.49.3.0.0
+3600.49.7.1.1

-  Functions: 4874
-  Symbols:   1777
-  CStrings:  1432
+  Functions: 4883
+  Symbols:   1780
+  CStrings:  1442
Symbols:
+ _NSStringFromAFSiriOrchestrationMode
+ _OBJC_CLASS_$_AFSiriAvailability
+ _symbolic _____ So31ORCHSchemaORCHOrchestrationModeV
+ _symbolic _____Sg So31ORCHSchemaORCHOrchestrationModeV
- _swift_release_x9
CStrings:
+ "ORCHORCHESTRATIONMODE_LLM_SIRI"
+ "ORCHORCHESTRATIONMODE_SIRI_CLASSIC"
+ "ORCHORCHESTRATIONMODE_SIRI_X_FULL_UOD"
+ "ORCHORCHESTRATIONMODE_SIRI_X_HYBRID_UOD"
+ "ORCHORCHESTRATIONMODE_SYSTEM_ASSISTANT_EXPERIENCE"
+ "ORCHORCHESTRATIONMODE_UNKNOWN"
+ "RequestWithNoAssetsCalculator desiredOrchestrationMode resolved to %{public}s"
+ "RequestWithNoAssetsCalculator: AFSiriAvailability.fromPreferences unavailable"
+ "orchestration_mode"
+ "siriDesiredOrchestrationMode"
```
