## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f1d4` | `0x4f43c` | **`+0x268`** |
| `__TEXT.__objc_methlist` | `0x5d28` | `0x5d50` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1900` | `0x1920` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4320` | `0x4340` | **`+0x20`** |
| `__TEXT.__cstring` | `0x13c2` | `0x13e2` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x132a` | `0x133a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1600` | `0x1608` | **`+0x8`** |

### Other Changes

```diff

-236.0.21.100.0
+236.0.21.104.0

-  Functions: 2058
-  Symbols:   3263
-  CStrings:  367
+  Functions: 2062
+  Symbols:   3267
+  CStrings:  368
Symbols:
+ -[SPUISearchHeader updateCompletionVisibility]
+ -[SPUISearchViewController presentationSource]
+ -[SPUIUnifiedFieldViewController topPocketHeight]
+ GCC_except_table94
+ ___70-[SPUISearchViewController searchViewWillPresentFromSource:isOverApp:]_block_invoke_4
- GCC_except_table92
CStrings:
+ "DisplayPolicy signals: query=%{sensitive}@ qid=%lu len=%ld elevatable=%d tier=%ld rawTier=%ld hasTopHitSection=%d firstBundle=%{sensitive}@ firstResultBundle=%{sensitive}@ firstResultCount=%lu priorityComplete=%d complete=%d sectionCount=%lu"
+ "com.apple.spotlight.tophits"
- "DisplayPolicy signals: query=%{sensitive}@ qid=%lu len=%ld elevatable=%d isSiriWorthy=%d firstBundle=%{sensitive}@ firstResultBundle=%{sensitive}@ firstResultCount=%lu hasTopHits=%d hasTopHitResult=%d complete=%d sectionCount=%lu"
```
