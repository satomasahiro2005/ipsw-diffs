## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72608` | `0x72de0` | **`+0x7d8`** |
| `__TEXT.__cstring` | `0x1a864` | `0x1aac4` | **`+0x260`** |
| `__AUTH_CONST.__cfstring` | `0x5580` | `0x5600` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1960` | `0x19d8` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x2dc0` | `0x2e10` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0xc18` | `0xc58` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1860` | `0x18a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x294` | `0x2b8` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0x3474` | `0x3494` | **`+0x20`** |
| `__DATA.__bss` | `0x7d0` | `0x7e0` | **`+0x10`** |
| `__TEXT.__const` | `0x478` | `0x488` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |

### Other Changes

```diff

-405.10.29.0.0
+405.10.34.1.1

-  Functions: 3069
-  Symbols:   3336
-  CStrings:  3113
+  Functions: 3080
+  Symbols:   3348
+  CStrings:  3127
Symbols:
+ -[HDSSetupService _applySetupTimeIfClockImplausible:]
+ -[HDSSetupSession _shouldTransferLoggingProfile]
+ GCC_except_table379
+ GCC_except_table429
+ _OBJC_CLASS_$_NSDateFormatter
+ __HDSBuildDateFloor.sFloor
+ __HDSBuildDateFloor.sOnce
+ ___53-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_6
+ ___53-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_7
+ ____HDSBuildDateFloor_block_invoke
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- GCC_except_table426
CStrings:
+ "  "
+ "-[HDSSetupService _applySetupTimeIfClockImplausible:]"
+ "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_4"
+ "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_7"
+ "Clock %@ predates build, applying setup time %@ (%@)\n"
+ "Ignoring setup time %@, predates build floor %@\n"
+ "Logging Profile install failed, logging will stay disabled\n"
+ "Logging Profile unreadable at %@, logging will stay disabled\n"
+ "Logging profile transfer timed out"
+ "MMM d yyyy"
+ "No build date floor, not applying setup time %@\n"
+ "Sep 30 2026"
+ "_startSysDropLoggingProfileRequest timed out after %g s\n"
+ "_startSysDropLoggingProfileRequest timeout fired but transfer state is %d, ignoring\n"
+ "en_US_POSIX"
- "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_5"
```
