## FeedbackCore

> `/System/Library/PrivateFrameworks/FeedbackCore.framework/FeedbackCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x147af0` | `0x147ccc` | **`+0x1dc`** |
| `__DATA.__data` | `0x2dd0` | `0x2d90` | **`-0x40`** |
| `__TEXT.__cstring` | `0xa358` | `0xa388` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1200` | `0x1208` | **`+0x8`** |

### Other Changes

```diff

-231.1.0.0.0
+232.0.0.0.0

-  Symbols:   7434
-  CStrings:  2626
+  Symbols:   7435
+  CStrings:  2627
Symbols:
+ _UIAccessibilityTraitHeader
Functions:
~ -[FBKProminentInformationCell setQuestion:] : 192 -> 240
~ sub_260ee6c90 -> sub_262165cc0 : 812 -> 876
~ sub_260f45924 -> sub_2621c4994 : 3792 -> 3764
~ sub_260f4df64 -> sub_2621ccfb8 : 588 -> 980
CStrings:
+ "Received unexpected diffable object for identifier [%@] in section [%@]"
+ "Skipping duplicate DE consent alert for extension [%{public}@]"
- "Received unexpected diffable object for identifier [%{public}@] in section [%{public}@]"
```
