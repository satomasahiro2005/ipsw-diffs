## MentalHealthAppPlugin

> `/System/Library/Health/FeedItemPlugins/MentalHealthAppPlugin.healthplugin/MentalHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe140` | `0xbe9b8` | **`+0x878`** |
| `__TEXT.__cstring` | `0x3b93` | `0x3c33` | **`+0xa0`** |
| `__DATA.__data` | `0x2a40` | `0x2a90` | **`+0x50`** |
| `__TEXT.__const` | `0x6214` | `0x6244` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x4108` | `0x40e0` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2a60` | `0x2a80` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x166e` | `0x168e` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d8` | `0x8c0` | **`-0x18`** |
| `__TEXT.__eh_frame` | `0x1eec` | `0x1ed4` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x21f4` | `0x2208` | **`+0x14`** |
| `__AUTH.__data` | `0x15e0` | `0x15f0` | **`+0x10`** |
| `__DATA.__bss` | `0x4bc0` | `0x4bd0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1700` | `0x170c` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x2688` | `0x2690` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 3393
-  Symbols:   341
-  CStrings:  407
+  Functions: 3400
+  Symbols:   340
+  CStrings:  409
Symbols:
- _OBJC_CLASS_$_HKSampleQuery
CStrings:
+ "MHPregnancyExecutor:shouldShowFeedItem"
+ "MentalHealthAssessmentsPDFDataQuery:loadGAD7Assessments"
+ "MentalHealthAssessmentsPDFDataQuery:loadPHQ9Assessments"
+ "StateOfMindDataLoggingExecutor:getLatestSample"
- "com.apple.Health"
- "getLatestSample(for:)"
```
