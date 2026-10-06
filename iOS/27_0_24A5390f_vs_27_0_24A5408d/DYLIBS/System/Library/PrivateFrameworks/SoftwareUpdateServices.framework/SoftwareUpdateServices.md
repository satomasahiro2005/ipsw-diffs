## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x15431` | `0x15491` | **`+0x60`** |
| `__TEXT.__text` | `0x6aa9c` | `0x6aac4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xdf40` | `0xdf60` | **`+0x20`** |

### Other Changes

```diff

-1112.0.1.0.0
+1112.0.3.0.0

-  CStrings:  2221
+  CStrings:  2222
Functions:
~ __requiredBatteryLevelToAutoDownload : 324 -> 364
CStrings:
+ "off-charger, auto-download, critical, released 24 hours ago"
+ "off-charger, auto-download, critical, released within 24 hours"
- "emergency or critical update"
```
