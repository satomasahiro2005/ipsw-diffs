## TextComposer

> `/System/Library/PrivateFrameworks/TextComposer.framework/TextComposer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cec44` | `0x1d194c` | **`+0x2d08`** |
| `__TEXT.__oslogstring` | `0xa8e2` | `0xab52` | **`+0x270`** |
| `__AUTH_CONST.__cfstring` | `0xaec0` | `0xb080` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x1015b` | `0x1030b` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0xfcd8` | `0xfe60` | **`+0x188`** |
| `__TEXT.__eh_frame` | `0xcaa0` | `0xcc20` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x2818` | `0x2950` | **`+0x138`** |
| `__TEXT.__const` | `0x16984` | `0x16aa4` | **`+0x120`** |
| `__TEXT.__swift5_reflstr` | `0x296c` | `0x28ac` | **`-0xc0`** |
| `__TEXT.__unwind_info` | `0x85a8` | `0x8648` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x32a0` | `0x3330` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x5aa8` | `0x5b38` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x10098` | `0x10018` | **`-0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x4910` | `0x4898` | **`-0x78`** |
| `__DATA.__data` | `0x23a8` | `0x2338` | **`-0x70`** |
| `__TEXT.__swift5_capture` | `0xfc0` | `0x1024` | **`+0x64`** |
| `__TEXT.__gcc_except_tab` | `0x1d54` | `0x1d0c` | **`-0x48`** |
| `__DATA.__bss` | `0x225e0` | `0x22620` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1e50` | `0x1e78` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x1470` | `0x1490` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x730` | `0x710` | **`-0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x1410` | `0x13f0` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x498` | `0x4b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd80` | `0xd98` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x514` | `0x528` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x604` | `0x618` | **`+0x14`** |
| `__AUTH.__data` | `0x37f8` | `0x37e8` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x1270` | `0x1280` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4108` | `0x4118` | **`+0x10`** |
| `__TEXT.__ustring` | `0x1852` | `0x1862` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x588` | `0x590` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x930` | `0x938` | **`+0x8`** |

### Other Changes

```diff

-211.26.0.0.0
+211.30.0.0.0

-  Functions: 13458
-  Symbols:   885
-  CStrings:  2584
+  Functions: 13493
+  Symbols:   889
+  CStrings:  2616
Symbols:
+ _TCSmartActionsSpotlightCacheVersion
+ _TCSmartActionsSpotlightResponseKey
+ _TCSmartActionsSpotlightVersionKey
+ _kCFStringTransformMandarinLatin
CStrings:
+ "Cached smart action found, but no smart action type is eligible for this conversation - treating as a cache miss"
+ "Found cached smart action - checking eligibility"
+ "PostEditingAllowList"
+ "Smart Actions Cache (Spotlight) | [HIT] | (cacheKey:%{private}@)"
+ "Smart Actions Cache (Spotlight) | [MISS] | %@"
+ "Smart Actions Cache (Spotlight) | [MISS] | (cacheKey:%{private}@)"
+ "TCProofreadingReviewTelemetryDailyCount"
+ "TCProofreadingReviewTelemetryDailyCountDay"
+ "TCProofreadingReviewTelemetryDailyMaximum"
+ "TCTelemetry: proofreading review daily maximum of %{public}ld donations reached"
+ "TCTelemetry: proofreading review daily maximum reached, skipping donation"
+ "TCTextCompositionAssistant failed to load from '%@': %@"
+ "TCUseAllowList"
+ "[TCTextCompositionAssistant] : BypassSmartRepliesCache=YES - bypassing cache and invoking model"
+ "[TCTextCompositionAssistant|BasicSmartReplies] Cached empty response"
+ "[TCTextCompositionAssistant|BasicSmartReplies] Failed to cache empty response"
+ "\\{\\{([\\s\\S]*?)\\}\\}"
+ "an"
+ "ang"
+ "c"
+ "ch"
+ "com.apple.TextComposer.TCTelemetry.dailyBudget"
+ "com_apple_textcomposer_smartActionsResponse"
+ "com_apple_textcomposer_smartActionsVersion"
+ "eng"
+ "in"
+ "ing"
+ "no Spotlight cache key on most recent message"
+ "proofreading_review_allowlist"
+ "s"
+ "sh"
+ "v24@?0@\"NSString\"8@?<v@?@\"TCSmartActionsResponse\">16"
+ "z"
+ "İ"
+ "ı"
+ "ました"
- "ExampleCitationsAndAdvisories"
- "UseOfficialComposeResourceID"
- "[TCTextCompositionAssistant] : Found cached response but BypassSmartRepliesCache=YES - bypassing cache and invoking model"
- "_contentAdvisoriesData"
```
