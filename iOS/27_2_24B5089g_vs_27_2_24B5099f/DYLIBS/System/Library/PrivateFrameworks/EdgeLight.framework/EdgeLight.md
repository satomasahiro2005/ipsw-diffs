## EdgeLight

> `/System/Library/PrivateFrameworks/EdgeLight.framework/EdgeLight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e90` | `0x4fcc` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0x418` | `0x463` | **`+0x4b`** |
| `__TEXT.__cstring` | `0x7d9` | `0x7fa` | **`+0x21`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__const` | `0x160` | `0x170` | **`+0x10`** |

### Other Changes

```diff

-560.40.3.0.0
+560.40.5.0.0

-  CStrings:  97
+  CStrings:  100
Functions:
~ -[PTEffectRingLightEstimation initWithMetalContext:ringLightConfig:] : 540 -> 652
~ -[PTEffectRingLightEstimation updateDefaults:] : 756 -> 960
CStrings:
+ "PTEffectRingLightEstimation_bias"
+ "PTEffectRingLightEstimation_bias %f"
+ "effect nits range (%f, %f) to (%f, %f)"
```
