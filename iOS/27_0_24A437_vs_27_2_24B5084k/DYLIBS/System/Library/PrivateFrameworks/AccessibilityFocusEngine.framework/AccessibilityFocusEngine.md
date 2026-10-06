## AccessibilityFocusEngine

> `/System/Library/PrivateFrameworks/AccessibilityFocusEngine.framework/AccessibilityFocusEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x367c` | `0x38f4` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x481` | `0x545` | **`+0xc4`** |
| `__TEXT.__gcc_except_tab` | `0x34` | `0x5c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x128` | `0x130` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 71
-  Symbols:   181
-  CStrings:  35
+  Functions: 72
+  Symbols:   183
+  CStrings:  38
Symbols:
+ GCC_except_table48
+ ___54-[AXFocusManager _moveFocusContainerFocusInDirection:]_block_invoke
CStrings:
+ "Could not find currently focus container %@ in list %@. Recovering by moving into an available focus container."
+ "Disable focus in stale starting focus container: %@"
+ "Recovered focus into container: %@"
+ "Skipping empty focus container while recovering: %@"
- "Could not find currently focus container %@ in list %@"
```
