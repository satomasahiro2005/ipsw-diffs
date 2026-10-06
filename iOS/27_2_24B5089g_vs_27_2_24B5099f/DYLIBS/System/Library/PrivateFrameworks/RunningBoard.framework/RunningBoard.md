## RunningBoard

> `/System/Library/PrivateFrameworks/RunningBoard.framework/RunningBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b184` | `0x7b384` | **`+0x200`** |
| `__TEXT.__cstring` | `0x7d46` | `0x7d83` | **`+0x3d`** |
| `__TEXT.__oslogstring` | `0xba9e` | `0xbad9` | **`+0x3b`** |
| `__AUTH_CONST.__cfstring` | `0x6c60` | `0x6c80` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f50` | `0x2f60` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x640c` | `0x6414` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e70` | `0x1e78` | **`+0x8`** |

### Other Changes

```diff

-1084.40.6.0.0
+1084.40.7.0.0

-  Functions: 2826
+  Functions: 2827

-  CStrings:  1860
+  CStrings:  1863
Symbols:
+ -[RBSLaunchContext(RBLaunchChecks) _installationHoldActive:]
+ GCC_except_table38
+ GCC_except_table54
- GCC_except_table17
- GCC_except_table37
- GCC_except_table53
Functions:
~ __addRBProperties : 1172 -> 1228
~ _OUTLINED_FUNCTION_5 : 12 -> 16
~ _OUTLINED_FUNCTION_5 : 16 -> 20
~ _OUTLINED_FUNCTION_5 : 20 -> 40
~ _OUTLINED_FUNCTION_5 : 40 -> 32
- _OUTLINED_FUNCTION_5
~ -[RBSLaunchContext(RBLaunchChecks) _passesPreflightChecksWithError:] : 476 -> 592
+ -[RBSLaunchContext(RBLaunchChecks) _installationHoldActive:]
~ -[RBSLaunchContext(RBLaunchChecks) _preflightEligibility:].cold.2 : 84 -> 72
+ -[RBSLaunchContext(RBLaunchChecks) _installationHoldActive:].cold.1
~ ___70-[RBProcessManager _enqueueGuaranteedRunningLaunchForIdentity:atTime:]_block_invoke.cold.1 : 88 -> 76
~ ___70-[RBProcessManager _enqueueGuaranteedRunningLaunchForIdentity:atTime:]_block_invoke.cold.2 : 84 -> 88
~ -[RBProcessManager _resolveProcessWithIdentifier:auditToken:properties:].cold.1 : 84 -> 88
CStrings:
+ "Launch prevented due to active installation hold"
+ "_BundlePath"
+ "unable to find extension record for %{public}@: %{public}@"
```
