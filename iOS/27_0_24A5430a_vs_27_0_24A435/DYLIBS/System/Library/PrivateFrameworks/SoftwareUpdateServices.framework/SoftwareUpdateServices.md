## SoftwareUpdateServices

> `/System/Library/PrivateFrameworks/SoftwareUpdateServices.framework/SoftwareUpdateServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6aac4` | `0x6aae8` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x1f08` | `0x1f10` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ +[SUUtility autoDownloadTimeInterval] : 180 -> 216
CStrings:
+ "[Auto download] Customer: Downloading every 5 days"
- "[Auto download] Beta: Downloading every 1 day"
```
