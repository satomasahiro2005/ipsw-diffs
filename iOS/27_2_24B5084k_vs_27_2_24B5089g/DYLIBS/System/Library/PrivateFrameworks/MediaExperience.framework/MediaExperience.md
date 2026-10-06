## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f3adc` | `0x2f3c38` | **`+0x15c`** |
| `__TEXT.__oslogstring` | `0x7b604` | `0x7b6a8` | **`+0xa4`** |
| `__TEXT.__cstring` | `0x4f4eb` | `0x4f544` | **`+0x59`** |
| `__AUTH_CONST.__const` | `0x49a8` | `0x49c8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8a68` | `0x8a80` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x55d0` | `0x55d8` | **`+0x8`** |

### Other Changes

```diff

-385.6.1.0.0
+385.7.1.0.0

-  Functions: 11688
-  Symbols:   13898
-  CStrings:  14387
+  Functions: 11689
+  Symbols:   13900
+  CStrings:  14389
Symbols:
+ +[MXSessionResumptionContext canExcludeSessionFromActiveSessionList:forResumingSession:]
+ __OBJC_$_CLASS_METHODS_MXSessionResumptionContext
CStrings:
+ "+[MXSessionResumptionContext canExcludeSessionFromActiveSessionList:forResumingSession:]"
+ "-MXSessionContext- %s: Client '%{public}@' is not added to active session list as it is the CarSession reclaiming mainAudio for '%{public}@' AirPlay Video playback"
+ "05:12:21"
+ "Sep 12 2026"
- "01:08:17"
- "Sep  4 2026"
```
