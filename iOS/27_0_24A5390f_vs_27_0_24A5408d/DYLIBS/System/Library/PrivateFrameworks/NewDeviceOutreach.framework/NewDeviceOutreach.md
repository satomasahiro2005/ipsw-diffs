## NewDeviceOutreach

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/NewDeviceOutreach`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x155d8` | `0x16578` | **`+0xfa0`** |
| `__TEXT.__oslogstring` | `0xae4` | `0xca4` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0xf90` | `0x10a8` | **`+0x118`** |
| `__AUTH_CONST.__cfstring` | `0xd40` | `0xda0` | **`+0x60`** |
| `__DATA.__data` | `0x4d0` | `0x500` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x6e8` | `0x700` | **`+0x18`** |
| `__TEXT.__const` | `0xa84` | `0xa94` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x638` | `0x648` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x38` | `0x3c` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x2a6` | `0x2aa` | **`+0x4`** |

### Other Changes

```diff

-624.0.4.0.0
+624.0.13.0.0

-  Functions: 559
-  Symbols:   699
-  CStrings:  261
+  Functions: 562
+  Symbols:   701
+  CStrings:  278
Symbols:
+ _CFAbsoluteTimeGetCurrent
+ _symbolic Sd
CStrings:
+ "%s.%s: XPC reply received after %.*fs"
+ "%s.%s: requested by %lu for serial %{private}s. Dispatching XPC to ndoagent..."
+ ".AppleAccount/SUBSCRIPTIONS"
+ ".General/COVERAGE/"
+ "/account/manage/section/subscriptions"
+ "Converting account.apple.com manage subscriptions URL: %s"
+ "Converting manage-subscriptions action URL: %s"
+ "NewDeviceOutreach/NDOACCoverageDetails.swift"
+ "Not converting URL, unrecognized account.apple.com path: %s"
+ "account.apple.com"
+ "getCachedCoverageDetails(forSerialNumber:requester:completion:)"
+ "getCoverageInfoForSerialNumber: XPC connection error: %@"
+ "getCoverageInfoForSerialNumber: XPC reply received (data=%@, error=%@)"
+ "getCoverageInfoForSerialNumber: dispatching XPC for serial %{private}@ policy %lu"
+ "manage-subscriptions"
+ "nil"
+ "non-nil"
+ "none"
+ "settings-navigation://com.apple.Settings"
- "Cached coverage details requested by %lu for serial number %s"
- "settings-navigation://com.apple.Settings.General/COVERAGE/"
```
