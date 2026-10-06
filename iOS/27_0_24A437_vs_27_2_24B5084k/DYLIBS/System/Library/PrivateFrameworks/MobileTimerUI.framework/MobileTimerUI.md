## MobileTimerUI

> `/System/Library/PrivateFrameworks/MobileTimerUI.framework/MobileTimerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc658` | `0xc680` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x980` | `0x9a0` | **`+0x20`** |
| `__TEXT.__const` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__ustring` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-2333.0.0.0.0
+2333.2.3.0.0

-  CStrings:  93
+  CStrings:  94
Functions:
~ +[UIFont(MTUIFonts) mtui_thinTimeFont] : 88 -> 56
~ +[UIFont(MTUIFonts) mtui_thinTimeFontOfSize:] : 48 -> 112
~ -[MTUIDateLabel _updateDateString] : 696 -> 736
~ +[UIFont(MTUIFonts) mtui_lightTimeFont] : 88 -> 56
CStrings:
+ "\u2009"
```
