## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6ee4` | `0x6f53` | **`+0x6f`** |
| `__TEXT.__text` | `0x4e770` | `0x4e7d0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1050` | `0x1048` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x3734` | `0x3735` | **`+0x1`** |

### Other Changes

```diff

-570.0.0.0.0
+573.0.0.0.0

-  Functions: 2009
-  Symbols:   2724
-  CStrings:  1227
+  Functions: 2010
+  Symbols:   2723
+  CStrings:  1229
Symbols:
- _OUTLINED_FUNCTION_101
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-573~1109, %s file: %s, line: %d\n\n"
+ "generate_wrapping_key_curve25519"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-570~896, %s file: %s, line: %d\n\n"
```
