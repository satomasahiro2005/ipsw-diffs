## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e70c` | `0x6eae0` | **`+0x3d4`** |
| `__TEXT.__objc_methlist` | `0x6e34` | `0x6ea4` | **`+0x70`** |
| `__TEXT.__cstring` | `0xc952` | `0xc9a2` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4f60` | `0x4fa0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x8fac` | `0x8f6f` | **`-0x3d`** |
| `__AUTH_CONST.__objc_const` | `0xafe0` | `0xb010` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x3498` | `0x34c8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1e00` | `0x1e28` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xc68` | `0xc88` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x17f0` | `0x17f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x710` | `0x714` | **`+0x4`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 2861
-  Symbols:   4589
-  CStrings:  1779
+  Functions: 2869
+  Symbols:   4601
+  CStrings:  1781
Symbols:
+ +[SRUIFSiriUIFeatureFlag(SWEFeatureFlags) isSiriReadThisV3Enabled]
+ -[SASLockStateMonitor isThermallyBlocked]
+ -[SASOverriddenSystemState deviceIsThermallyBlocked]
+ -[SASSystemState deviceIsThermallyBlocked]
+ -[SiriContextOverride deviceIsThermallyBlockedForSystemState:]
+ -[SiriContextOverride deviceIsThermallyBlocked]
+ -[SiriContextOverride overrideDeviceIsThermallyBlocked:]
+ -[SiriContextOverride setDeviceIsThermallyBlocked:]
+ GCC_except_table11
+ GCC_except_table14
+ GCC_except_table28
+ GCC_except_table42
+ GCC_except_table76
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ _OBJC_IVAR_$_SiriContextOverride._deviceIsThermallyBlocked
+ ___41-[SASLockStateMonitor isThermallyBlocked]_block_invoke
- GCC_except_table10
- GCC_except_table41
- GCC_except_table75
- _AFIsLinwoodCapable
CStrings:
+ "%s #activation PTT Eligible Remote or Odeon Proxy Voice Request, Sending handleButtonTap"
+ "SASRequestSourcePullDownGesture"
+ "deviceIsThermallyBlocked"
+ "siri_read_this_v3"
- "%s #activation PTT Eligible Remote, Sending handleButtonTap"
- "%s TestAutomation activationEvent does not contain recognition text or speech file paths."
```
