## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72750` | `0x729fc` | **`+0x2ac`** |
| `__TEXT.__cstring` | `0x1aa54` | `0x1aae4` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x7878` | `0x78b8` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x5580` | `0x55a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3444` | `0x345c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2da0` | `0x2db0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa48` | `0xa50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1868` | `0x1870` | **`+0x8`** |

### Other Changes

```diff

-405.0.7.0.0
+405.0.11.0.0

-  Functions: 3076
-  Symbols:   3333
-  CStrings:  3118
+  Functions: 3080
+  Symbols:   3338
+  CStrings:  3122
Symbols:
+ -[HDSSetupSession _armTRAuthenticationTimeout]
+ -[HDSSetupSession _runTRAuthenticationTimeout]
+ GCC_except_table372
+ GCC_except_table424
+ _OBJC_IVAR_$_HDSSetupSession._trAuthTimedOut
+ _OBJC_IVAR_$_HDSSetupSession._trAuthTimeoutTimer
+ ___46-[HDSSetupSession _armTRAuthenticationTimeout]_block_invoke
- GCC_except_table369
- GCC_except_table421
CStrings:
+ "### TRAuthentication timed out after %d seconds (stage %@)\n"
+ "-[HDSSetupSession _runTRAuthenticationTimeout]"
+ "TRAuth timed out after %d secs"
+ "TRAuthTimeout"
```
