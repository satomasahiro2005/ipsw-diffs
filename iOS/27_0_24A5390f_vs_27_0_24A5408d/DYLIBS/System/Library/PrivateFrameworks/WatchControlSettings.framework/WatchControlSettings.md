## WatchControlSettings

> `/System/Library/PrivateFrameworks/WatchControlSettings.framework/WatchControlSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x606` | `0x6ea` | **`+0xe4`** |
| `__TEXT.__text` | `0x9ef4` | `0x9fc4` | **`+0xd0`** |
| `__TEXT.__const` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-196.0.0.0.0
+198.0.0.0.0

-  Symbols:   506
-  CStrings:  317
+  Symbols:   507
+  CStrings:  319
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
Functions:
~ -[WatchControlSettings(Onboarding) setRequestToShowPracticeGrey:] : 352 -> 492
~ -[WCGesturesOverviewViewController_iOS _tryItOutOnAppleWatch] : 76 -> 144
CStrings:
+ "rdar://164150381 WCGesturesOverviewViewController_iOS _tryItOutOnAppleWatch tapped; requesting practice grey on watch"
+ "rdar://164150381 setRequestToShowPracticeGrey NPS write+sync issued value=%d domain=%{public}@ key=%{public}@"
```
