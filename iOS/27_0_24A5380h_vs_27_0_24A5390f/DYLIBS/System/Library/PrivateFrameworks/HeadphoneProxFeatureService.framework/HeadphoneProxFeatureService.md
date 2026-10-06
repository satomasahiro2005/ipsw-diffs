## HeadphoneProxFeatureService

> `/System/Library/PrivateFrameworks/HeadphoneProxFeatureService.framework/HeadphoneProxFeatureService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8a4` | `0x1bfdc` | **`+0x738`** |
| `__TEXT.__oslogstring` | `0x2686` | `0x26f6` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x638` | `0x668` | **`+0x30`** |
| `__DATA.__data` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x408` | `0x410` | **`+0x8`** |

### Other Changes

```diff

-40.33.1.0.0
+40.36.1.0.0

-  - /System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/CloudSubscriptionFeatures

-  Functions: 426
+  Functions: 428

-  CStrings:  136
+  CStrings:  137
CStrings:
+ "HeadphoneProxFeatureService: isAppleIntelligencePrerequisiteMet: region ineligible (rdar://179108724)"
+ "HeadphoneProxFeatureService: isAppleIntelligencePrerequisiteMet: wasEverAvailable=%{bool}d"
- "HeadphoneProxFeatureService: isAppleIntelligencePrerequisiteMet %{bool}d %{bool}d"
```
