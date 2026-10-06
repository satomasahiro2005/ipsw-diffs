## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1be614` | `0x1befd0` | **`+0x9bc`** |
| `__TEXT.__oslogstring` | `0xf873` | `0xfce3` | **`+0x470`** |
| `__TEXT.__cstring` | `0x9f1c` | `0x9fac` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x7e40` | `0x7ea0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1ac64` | `0x1ac9c` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x41a0` | `0x41d0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xcae8` | `0xcb08` | **`+0x20`** |
| `__TEXT.__const` | `0x4384` | `0x43a4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7458` | `0x7468` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1590` | `0x1598` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x26c08` | `0x26c10` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2d24` | `0x2d28` | **`+0x4`** |

### Other Changes

```diff

-1053.0.0.0.0
+1061.0.0.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 10967
-  Symbols:   14402
-  CStrings:  2131
+  Functions: 10972
+  Symbols:   14409
+  CStrings:  2149
Symbols:
+ -[NCCarPlayBannerSource _handleBannerWillPresentForPresentable:]
+ -[NCCarPlayBannerSource _isLinwoodCarPlayPreprocessEnabled]
+ -[NCCarPlayBannerSource _startDismissTimerWithTimeInterval:reason:]
+ -[NCCarPlayBannerSource presentableWillAppearAsBanner:]
+ -[NCNotificationContentContainerViewController scrollsOwnContent]
+ _AFIsLinwoodEnabledAndAvailable
+ _NCCarPlayBannerRevocationReasonAnnounceDismissal
+ ___67-[NCCarPlayBannerSource _startDismissTimerWithTimeInterval:reason:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e17_v16?0"NSTimer"8lw40l8s32l8
- -[NCCarPlayBannerSource _startDismissTimerWithTimeInterval:]
- ___60-[NCCarPlayBannerSource _startDismissTimerWithTimeInterval:]_block_invoke
CStrings:
+ "#DismissTimer FIRED timer=%p storedTimer=%p reason=%{public}@"
+ "#DismissTimer _cancelDismissTimer: timer=%p (will invalidate if non-nil)"
+ "#DismissTimer _handleBannerPresentedForPresentable: presentable=%p sticky=%d existingDismissTimer=%p existingReplaceTimer=%p"
+ "#DismissTimer _startAnnounceDismissalTimer (interval=%d) currentTimer=%p"
+ "#DismissTimer _startDismissTimerWithTimeInterval: SCHEDULED timer=%p interval=%f reason=%{public}@"
+ "#DismissTimer _startDismissTimerWithTimeInterval: SKIPPED (already have timer=%p), requestedInterval=%f reason=%{public}@"
+ "#DismissTimer didBeginAnnounceForNotificationRequest: requestID=%{public}@ dismissTimer=%p replaceTimer=%p"
+ "#DismissTimer didFinishAnnounceForNotificationRequest: requestID=%{public}@ dismissTimer=%p replaceTimer=%p"
+ "#DismissTimer presentableDidAppearAsBanner: presentable=%p linwoodPreprocess=%d takingHandlePath=%d"
+ "#DismissTimer presentableDidDisappearAsBanner: presentable=%p reason=%{public}@ dismissTimer=%p"
+ "#DismissTimer presentableWillAppearAsBanner: presentable=%p linwoodPreprocess=%d takingHandlePath=%d"
+ "#DismissTimer setSuspended: suspended=%d reason=PresentingAlert -> %@"
+ "IntelligenceFlow"
+ "Linwood"
+ "NCCarPlayBannerRevocationReasonAnnounceDismissal"
+ "cancel dismiss timer"
+ "linwood_carplay_banner_preprocess"
+ "start dismiss timer"
```
