## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xdf69` | `0xdff9` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0xaee0` | `0xaf20` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x279a8` | `0x279d8` | **`+0x30`** |
| `__TEXT.__const` | `0x798` | `0x768` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x8e58` | `0x8e70` | **`+0x18`** |
| `__TEXT.__text` | `0x7cb6c` | `0x7cb78` | **`+0xc`** |
| `__DATA.__bss` | `0x918` | `0x910` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x8f0` | `0x8e8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x894` | `0x898` | **`+0x4`** |

### Other Changes

```diff

-4636.115.0.0.0
+4637.1.7.0.0

-  Functions: 4359
-  Symbols:   8057
-  CStrings:  2137
+  Functions: 4361
+  Symbols:   8058
+  CStrings:  2139
Symbols:
+ -[SBSRemoteAlertPresentationTarget requiresFullscreenPresentationWhenTargetAppIsResizable]
+ -[SBSRemoteAlertPresentationTarget setRequiresFullscreenPresentationWhenTargetAppIsResizable:]
+ _OBJC_IVAR_$_SBSRemoteAlertPresentationTarget._requiresFullscreenPresentationWhenTargetAppIsResizable
- _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
- _kSBSSystemApertureDisabled_block_invoke.deviceSubtype
CStrings:
+ "kSBSRemoteAlertPresentationTarget_RequiresFullscreenPresentationWhenTargetAppIsResizable"
+ "requiresFullscreenPresentationWhenTargetAppIsResizable"
```
