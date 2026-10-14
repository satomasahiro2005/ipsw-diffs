## UIAccessibility

> `/System/Library/PrivateFrameworks/UIAccessibility.framework/UIAccessibility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d460` | `0x6d774` | **`+0x314`** |
| `__TEXT.__oslogstring` | `0x2d31` | `0x2dc5` | **`+0x94`** |
| `__DATA_CONST.__const` | `0x15a0` | `0x15c8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x6c2c` | `0x6c54` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x5770` | `0x5788` | **`+0x18`** |
| `__TEXT.__const` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1b50` | `0x1b58` | **`+0x8`** |

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 2627
-  Symbols:   4592
-  CStrings:  1189
+  Functions: 2631
+  Symbols:   4597
+  CStrings:  1191
Symbols:
+ -[NSObject(AXAutoscrolling) _accessibilityShouldRetryScrollToBottom]
+ -[UIAccessibilityAutoscrollManager _bottomContentOffset]
+ -[UIAccessibilityAutoscrollManager _scrollToBottomWithRetriesRemaining:]
+ GCC_except_table1877
+ GCC_except_table1939
+ GCC_except_table1994
+ GCC_except_table2012
+ GCC_except_table2166
+ GCC_except_table2213
+ GCC_except_table2219
+ GCC_except_table2228
+ GCC_except_table2445
+ GCC_except_table2464
+ GCC_except_table2554
+ GCC_except_table2565
+ ___72-[UIAccessibilityAutoscrollManager _scrollToBottomWithRetriesRemaining:]_block_invoke
+ ___block_descriptor_72_e8_32s40s_e5_v8?0ls32l8s40l8
- GCC_except_table1876
- GCC_except_table1938
- GCC_except_table1993
- GCC_except_table2011
- GCC_except_table2165
- GCC_except_table2212
- GCC_except_table2218
- GCC_except_table2226
- GCC_except_table2441
- GCC_except_table2460
- GCC_except_table2550
- GCC_except_table2561
CStrings:
+ "cannot scroll to bottom, no autoscroll target was set"
+ "scrolling to bottom %{public}@ from %{public}@, content size %{public}@, %ld retries left: %@"
```
