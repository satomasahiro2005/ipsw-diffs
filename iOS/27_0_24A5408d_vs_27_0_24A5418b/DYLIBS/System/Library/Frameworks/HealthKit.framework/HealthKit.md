## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f8274` | `0x3f82ac` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x33880` | `0x338a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x37d02` | `0x37d12` | **`+0x10`** |

### Other Changes

```diff

-7027.0.72.2.5
+7027.0.72.2.7

-  CStrings:  9195
+  CStrings:  9196
Functions:
~ -[HKAnalyticsEventSubmissionManager submitEvent:error:] : 1192 -> 1248
CStrings:
+ "menopaus"
```
