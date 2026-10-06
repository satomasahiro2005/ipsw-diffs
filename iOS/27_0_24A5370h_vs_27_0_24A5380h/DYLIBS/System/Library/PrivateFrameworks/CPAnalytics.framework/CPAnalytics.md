## CPAnalytics

> `/System/Library/PrivateFrameworks/CPAnalytics.framework/CPAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x22f0` | `0x23e1` | **`+0xf1`** |
| `__AUTH_CONST.__cfstring` | `0x2b40` | `0x2be0` | **`+0xa0`** |
| `__TEXT.__text` | `0x12390` | `0x123c0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  CStrings:  443
+  CStrings:  448
Functions:
~ +[CPAnalyticsCoreAnalyticsHelper upgradePayload:sourceEvent:] : 572 -> 620
CStrings:
+ "com.apple.photos.personalEnvironment.create"
+ "com.apple.photos.personalEnvironment.deleted"
+ "com.apple.photos.personalEnvironment.enqueued"
+ "com.apple.photos.personalEnvironment.generationSummary"
+ "com.apple.photos.personalEnvironment.pickerSession"
```
