## SoftwareUpdateUIBridge

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIBridge.framework/SoftwareUpdateUIBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33250` | `0x3346c` | **`+0x21c`** |
| `__TEXT.__cstring` | `0x2ab7` | `0x2ac7` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x890` | `0x898` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-772.0.20.0.0
+772.40.11.0.0

-  Functions: 714
-  Symbols:   1198
-  CStrings:  381
+  Functions: 715
+  Symbols:   1199
+  CStrings:  382
Symbols:
+ GCC_except_table17
+ GCC_except_table19
+ ___os_log_helper_16_2_3_8_32_8_32_8_66
- GCC_except_table18
- GCC_except_table29
CStrings:
+ "%s: %s is nil in %{public}@. Stopping."
+ "self"
- "%s: Self is nil in %{public}@. Stopping."
```
