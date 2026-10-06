## CommunicationsSetupUI

> `/System/Library/PrivateFrameworks/CommunicationsSetupUI.framework/CommunicationsSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x904f0` | `0x904a0` | **`-0x50`** |
| `__TEXT.__cstring` | `0xc667` | `0xc697` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xbae0` | `0xbb00` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb50` | `0xb70` | **`+0x20`** |

### Other Changes

```diff

-1565.100.1.0.0
+1567.100.1.0.0

-  CStrings:  1797
+  CStrings:  1798
Functions:
~ -[CNFRegSettingsController _openQuickSwitchLearnMore] : 204 -> 188
~ -[CNFRegSettingsController _showQuickSwitchRemoveAlertForAlias:] : 644 -> 580
CStrings:
+ "FACETIME_QUICK_SWITCH_LEARN_MORE_URL"
```
