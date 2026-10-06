## PromotedContentUI

> `/System/Library/PrivateFrameworks/PromotedContentUI.framework/PromotedContentUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a77cc` | `0x1a6c64` | **`-0xb68`** |
| `__TEXT.__eh_frame` | `0x62c8` | `0x6328` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0x7600` | `0x75d0` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0xbcf8` | `0xbd20` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x36d8` | `0x36f8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1758` | `0x1778` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4e48` | `0x4e60` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1bdc` | `0x1bf0` | **`+0x14`** |
| `__TEXT.__cstring` | `0x7ec1` | `0x7ed1` | **`+0x10`** |

### Other Changes

```diff

-557.2.9.0.0
+557.2.13.0.0

-  Functions: 6787
+  Functions: 6795

-  CStrings:  998
+  CStrings:  995
CStrings:
+ "appleSearchAdsTimeToPrewarmV2"
+ "appleSearchAdsTimeToSignedPayload_POISearchHomeV2"
+ "pageLayoutFinal %{public}@ -> %{public}@ (window %{public}ldx%{public}ld, verticalSizeClass %{public}ld). PC Identifier: %{public}@"
- "appleSearchAdsTimeToPrewarm"
- "appleSearchAdsTimeToSignedPayload_POISearchHome"
- "moduleFactoryTimeToMake"
- "poiAdPayloadStrategyTimeToGeneratePayload"
- "poiRequestBuilderDeviceInfo"
- "poiStrategyRegistryBuild"
```
