## PrivateFederatedLearning

> `/System/Library/PrivateFrameworks/PrivateFederatedLearning.framework/PrivateFederatedLearning`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81b30` | `0x830e8` | **`+0x15b8`** |
| `__TEXT.__eh_frame` | `0x4968` | `0x4a40` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x1938` | `0x1a08` | **`+0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x11a0` | `0x11e8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x538` | `0x560` | **`+0x28`** |
| `__DATA.__data` | `0xbb0` | `0xbd0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1858` | `0x1878` | **`+0x20`** |
| `__TEXT.__const` | `0x3ad8` | `0x3ae8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1126` | `0x112e` | **`+0x8`** |

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  Functions: 1798
-  Symbols:   923
-  CStrings:  215
+  Functions: 1803
+  Symbols:   924
+  CStrings:  218
Symbols:
+ _symbolic ______p 15PriMLFoundation8TaskSinkP
CStrings:
+ "Cohort key '%s' not allowed for policy key '%s'"
+ "No metadata to submit. Either empty or all-zero."
+ "No metrics to submit. Either empty or all-zero."
+ "Policy key '%s' not in CohortAllowList — cohorts not authorized for this task"
+ "[PFLDediscoResultProcessor] Nothing to submit on failure for task %s: recipe has no metadata schema."
- "Cohort key '%s' not allowed for prefix '%s'"
- "Collection-ID prefix '%s' not in CohortAllowList — cohorts not authorized for this task"
```
