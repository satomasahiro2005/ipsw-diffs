## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6adfc` | `0x6ae20` | **`+0x24`** |
| `__TEXT.__cstring` | `0x154e1` | `0x154f1` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f18` | `0x1f20` | **`+0x8`** |

### Other Changes

```diff
Functions:
~ +[SUUtility autoDownloadTimeInterval] : 180 -> 216
CStrings:
+ "[Auto download] Customer: Downloading every 5 days"
- "[Auto download] Beta: Downloading every 1 day"
```
