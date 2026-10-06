## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f114` | `0x4f250` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x64c7` | `0x6536` | **`+0x6f`** |
| `__TEXT.__unwind_info` | `0x1630` | `0x1648` | **`+0x18`** |

### Other Changes

```diff

-440.1.0.0.0
+442.0.0.0.0

-  Functions: 2392
-  Symbols:   3853
-  CStrings:  1630
+  Functions: 2393
+  Symbols:   3852
+  CStrings:  1632
Symbols:
- _OUTLINED_FUNCTION_101
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "generate_wrapping_key_curve25519"
```
