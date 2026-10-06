## SEService

> `/System/Library/PrivateFrameworks/SEService.framework/SEService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113e68` | `0x11433c` | **`+0x4d4`** |
| `__AUTH_CONST.__cfstring` | `0x4560` | `0x46a0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x8d65` | `0x8e75` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x2db7` | `0x2e57` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b18` | `0x1b68` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x83d0` | `0x83f8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3c8c` | `0x3cb4` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x5360` | `0x5388` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x730` | `0x740` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x38c` | `0x390` | **`+0x4`** |

### Other Changes

```diff

-70.35.1.0.0
+70.37.0.0.0

-  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

-  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 7225
-  Symbols:   4695
-  CStrings:  1340
+  Functions: 7228
+  Symbols:   4701
+  CStrings:  1353
Symbols:
+ -[SEProxyWithManagerSession _checkPairing:]
+ -[SEProxyWithManagerSession validatePairing:callback:]
+ -[SEProxyWithRemoteTransceiver validatePairing:callback:]
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_IVAR_$_SESTapToRadar._pendingRequestTimestamp
CStrings:
+ "%@\n\n"
+ "EEE MMM d HH:mm:ss yyyy"
+ "Failed pairing check 1"
+ "Failed to deleteAllApplets"
+ "Failed to recheck after deleteAll %d %@"
+ "Got ambiguous pairing result %d"
+ "Issue Time: %@\n\n"
+ "Missing key and/or applet identifier"
+ "Missing key identifier"
+ "Pairing state (after) %{public}x / %{public}@"
+ "Pairing state (before) %{public}x / %{public}@"
+ "Please fill out the following information to assist with triage:\n\nVehicle Make:\nVehicle Model:\nAdditional Context:"
+ "STSRemoteTransceiver doesn't support validatePairing"
+ "Validate pairing re-paired with result %{public}d / %{public}@"
+ "en_US_POSIX"
- "%@\n\nPlease fill out the following information to assist with triage:\n\nVehicle Make:\nVehicle Model:\nAdditional Context:"
- "Invalid reader ID"
```
