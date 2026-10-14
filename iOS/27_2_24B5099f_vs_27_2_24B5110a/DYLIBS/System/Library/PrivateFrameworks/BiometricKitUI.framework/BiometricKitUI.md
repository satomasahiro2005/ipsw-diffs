## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70fd0` | `0x70eac` | **`-0x124`** |
| `__TEXT.__oslogstring` | `0x6b13` | `0x6a63` | **`-0xb0`** |
| `__DATA_CONST.__const` | `0x1260` | `0x1210` | **`-0x50`** |
| `__TEXT.__cstring` | `0x3036` | `0x2fe6` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3440` | `0x3400` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x10790` | `0x107c0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7368` | `0x7378` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1ad8` | `0x1ad0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa08` | `0xa0c` | **`+0x4`** |

### Other Changes

```diff

-685.1.4.0.0
+685.1.5.200.0

-  Functions: 2887
+  Functions: 2889

-  CStrings:  1085
+  CStrings:  1079
Symbols:
+ -[BKUIPearlEnrollAudioManager hapticsEngineStarted]
+ -[BKUIPearlEnrollAudioManager setHapticsEngineStarted:]
+ _OBJC_IVAR_$_BKUIPearlEnrollAudioManager._hapticsEngineStarted
- -[BKUIHostedDynamicallySizedJindoPresentable _sweepStalePresentablesFromBannerSource:]
- ___block_descriptor_56_e8_32s40bs48w_e5_v8?0ls32l8w48l8s40l8
- ___block_descriptor_56_e8_32s40bs48w_e5_v8?0lw48l8s32l8s40l8
CStrings:
+ "Unable to clean up Haptics: %{public}@"
- "CaptureSession: Updating selfie session with: %@"
- "Error revoking presentables %{public}@"
- "Revoking current presentable"
- "Swept %{public}lu orphaned presentable(s) after a stale request identifier"
- "Unable to clean up Haptics %@."
- "com.apple.biometrickitui.revoke"
- "com.apple.biometrickitui.staleIdentifierSweep"
```
