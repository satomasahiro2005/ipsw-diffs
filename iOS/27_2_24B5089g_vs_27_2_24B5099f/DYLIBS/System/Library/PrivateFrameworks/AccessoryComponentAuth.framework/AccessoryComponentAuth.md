## AccessoryComponentAuth

> `/System/Library/PrivateFrameworks/AccessoryComponentAuth.framework/AccessoryComponentAuth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x568` | `0x5d0` | **`+0x68`** |
| `__TEXT.__text` | `0x12bec` | `0x12c40` | **`+0x54`** |
| `__TEXT.__unwind_info` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4b0` | `0x4b8` | **`+0x8`** |

### Other Changes

```diff

-1219.40.7.0.0
+1219.40.10.502.1

-  Functions: 497
-  Symbols:   1514
+  Functions: 506
+  Symbols:   1523
Symbols:
+ -[ACCHWComponentAuthService authenticateBatteryWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateLASWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateRCAMWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateTouchControllerWithChallenge:completionHandler:updateRegistry:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:]
+ -[ACCHWComponentAuthService authenticateVeridianWithChallenge:completionHandler:updateRegistry:updateUIProperty:logToAnalytics:]
+ -[ACCHWComponentAuthService signRCAMChallenge:completionHandler:]
+ -[ACCHWComponentAuthService signVeridianChallenge:completionHandler:]
+ GCC_except_table79
- GCC_except_table72
```
