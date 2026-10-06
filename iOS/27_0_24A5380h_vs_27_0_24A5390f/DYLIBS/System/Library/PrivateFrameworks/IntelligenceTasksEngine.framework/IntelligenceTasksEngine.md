## IntelligenceTasksEngine

> `/System/Library/PrivateFrameworks/IntelligenceTasksEngine.framework/IntelligenceTasksEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1efb0` | `0x1f94c` | **`+0x99c`** |
| `__DATA.__bss` | `0x900` | `0xa00` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0xb09` | `0xb99` | **`+0x90`** |
| `__TEXT.__const` | `0xed8` | `0xf38` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x11b0` | `0x11f8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x4e3` | `0x523` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x8a0` | `0x8d8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x428` | `0x45c` | **`+0x34`** |
| `__TEXT.__eh_frame` | `0x1834` | `0x1864` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x208` | `0x230` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x4d4` | `0x4f0` | **`+0x1c`** |
| `__TEXT.__swift5_capture` | `0x3dc` | `0x3cc` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x339` | `0x349` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x6c6` | `0x6d4` | **`+0xe`** |
| `__TEXT.__swift_as_cont` | `0x134` | `0x140` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x7c0` | `0x7c8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x74` | `0x7c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x54` | `0x58` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xb8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc0` | `0xc4` | **`+0x4`** |

### Other Changes

```diff

-243.0.0.0.0
+247.0.1.0.0

-  Functions: 858
-  Symbols:   493
-  CStrings:  79
+  Functions: 862
+  Symbols:   494
+  CStrings:  83
Symbols:
+ _OBJC_CLASS_$_BGSystemTaskCheckpoints
+ _OBJC_CLASS_$_BGSystemTaskProgressMetrics
+ _OBJC_CLASS_$_BGSystemTaskWorkload
+ ___swift_memcpy163_8
+ _associated conformance 23IntelligenceTasksEngine21SpotlightVerificationO7RunModeOSHAASQ
+ _objc_retain_x1
+ _symbolic _____ 23IntelligenceTasksEngine21SpotlightVerificationO7RunModeO
- _OUTLINED_FUNCTION_121
- _OUTLINED_FUNCTION_122
- _OUTLINED_FUNCTION_123
- _OUTLINED_FUNCTION_124
- _OUTLINED_FUNCTION_125
- ___swift_memcpy155_8
CStrings:
+ "%s: reportFeatureCheckpoint(%lu) failed: %@"
+ "%s: reportProgressMetrics failed: %@"
+ "%s: reportSystemWorkload failed: %@"
+ "com.apple.intelligencetasksd.spotlight-verification"
```
