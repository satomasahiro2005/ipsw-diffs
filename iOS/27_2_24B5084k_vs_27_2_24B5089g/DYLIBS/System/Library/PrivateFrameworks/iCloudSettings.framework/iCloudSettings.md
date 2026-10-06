## iCloudSettings

> `/System/Library/PrivateFrameworks/iCloudSettings.framework/iCloudSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d918c` | `0x1d94f8` | **`+0x36c`** |
| `__TEXT.__oslogstring` | `0xb466` | `0xb506` | **`+0xa0`** |
| `__DATA.__data` | `0x5828` | `0x57f8` | **`-0x30`** |
| `__TEXT.__cstring` | `0x667a` | `0x669a` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x43cd` | `0x43ed` | **`+0x20`** |
| `__TEXT.__const` | `0x13354` | `0x13364` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4404` | `0x4410` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x6ca0` | `0x6ca8` | **`+0x8`** |

### Other Changes

```diff

-301.24.1.3.0
+301.24.1.4.0

-  Functions: 9238
+  Functions: 9241

-  CStrings:  1729
+  CStrings:  1730
CStrings:
+ "Async AMS load requested, launching AMS flow ahead of dataModel load."
+ "Pre-launch action has not executed and the check was not skipped — NDM should take priority, aborting AMS Deeplink."
+ "handleAMSDeeplink(urlString:skipPreLaunchCheck:)"
- "NDM should take priority aborting AMS Deeplink."
- "handleAMSDeeplink(urlString:)"
```
