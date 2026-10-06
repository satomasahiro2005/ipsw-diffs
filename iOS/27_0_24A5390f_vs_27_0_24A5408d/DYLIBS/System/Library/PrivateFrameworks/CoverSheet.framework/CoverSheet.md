## CoverSheet

> `/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c878` | `0x18cbe4` | **`+0x36c`** |
| `__TEXT.__cstring` | `0xca68` | `0xcb1a` | **`+0xb2`** |
| `__AUTH_CONST.__cfstring` | `0xc7c0` | `0xc860` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x3c6c0` | `0x3c750` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x8e9a` | `0x8ef6` | **`+0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0xc638` | `0xc688` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x16474` | `0x164bc` | **`+0x48`** |
| `__DATA.__objc_ivar` | `0x1b98` | `0x1ba4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1588` | `0x1590` | **`+0x8`** |
| `__TEXT.__const` | `0x40f4` | `0x40fc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4848` | `0x4850` | **`+0x8`** |

### Other Changes

```diff

-154.100.0.0.0
+159.0.2.0.0

-  Functions: 7937
-  Symbols:   14069
-  CStrings:  2657
+  Functions: 7943
+  Symbols:   14078
+  CStrings:  2663
Symbols:
+ -[CSCameraExtensionViewController _consumePendingLaunchActions]
+ -[CSCameraExtensionViewController didDeliverActionsToHostableEntity]
+ -[CSCameraExtensionViewController setDidDeliverActionsToHostableEntity:]
+ -[CSLockScreenPearlSettings matchPasscodeFallbackFailureSettings]
+ -[CSLockScreenPearlSettings matchPasscodeFallbackInterval]
+ -[CSLockScreenPearlSettings setMatchPasscodeFallbackFailureSettings:]
+ -[CSLockScreenPearlSettings setMatchPasscodeFallbackInterval:]
+ _OBJC_IVAR_$_CSCameraExtensionViewController._didDeliverActionsToHostableEntity
+ _OBJC_IVAR_$_CSLockScreenPearlSettings._matchPasscodeFallbackFailureSettings
+ _OBJC_IVAR_$_CSLockScreenPearlSettings._matchPasscodeFallbackInterval
- -[CSCameraExtensionViewController _launchActions]
CStrings:
+ "Face ID Match Passcode Fallback"
+ "Passcode Fallback Feedback"
+ "Passcode Fallback Interval (seconds, 0 disables)"
+ "[Notification Long Press Gesture] Window Scene is nil, will not send unocclude prox signal."
+ "matchPasscodeFallbackFailureSettings"
+ "matchPasscodeFallbackInterval"
```
