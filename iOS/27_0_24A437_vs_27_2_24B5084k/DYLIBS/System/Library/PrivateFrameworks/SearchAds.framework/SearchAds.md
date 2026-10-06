## SearchAds

> `/System/Library/PrivateFrameworks/SearchAds.framework/SearchAds`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14638` | `0x14bb8` | **`+0x580`** |
| `__TEXT.__oslogstring` | `0xf92` | `0x10d2` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x1320` | `0x13e0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x10e6` | `0x1166` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x7e0` | `0x808` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xf54` | `0xf7c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xde8` | `0xe00` | **`+0x18`** |
| `__TEXT.__const` | `0x960` | `0x970` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x5c8` | **`+0x10`** |

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Functions: 592
-  Symbols:   268
-  CStrings:  263
+  Functions: 595
+  Symbols:   273
+  CStrings:  278
Symbols:
+ _APPerfLogForCategory
+ __os_signpost_emit_with_name_impl
+ _objc_retain_x10
+ _os_signpost_enabled
+ _os_signpost_id_generate
CStrings:
+ "ClientSettingsRetrieval"
+ "ClientSettingsServerRetrieval"
+ "[%@]: %@: reverseGeolocationRefreshThresholdInMeters: %f, clickExpirationThresholdInSeconds: %ld, frequencyCapExpirationInSeconds: %ld, maxFrequencyCapElements: %lu, maxClickCapElements: %lu."
+ "[%@]: After applyClientSettings:"
+ "[%@]: Properties at init:"
+ "cacheHit"
+ "floraSettings"
+ "iris1Settings"
+ "iris2Settings"
+ "landingPageSettings"
+ "metisSettings"
+ "reason=%{public}s"
+ "searchSettings"
+ "serverError"
+ "serverSuccess"
```
