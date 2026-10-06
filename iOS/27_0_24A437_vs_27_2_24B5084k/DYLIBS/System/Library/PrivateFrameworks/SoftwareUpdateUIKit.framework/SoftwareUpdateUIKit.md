## SoftwareUpdateUIKit

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIKit.framework/SoftwareUpdateUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x262278` | `0x2625fc` | **`+0x384`** |
| `__TEXT.__oslogstring` | `0x50c0` | `0x5140` | **`+0x80`** |
| `__TEXT.__cstring` | `0x68ea` | `0x68ca` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7700` | `0x7710` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x6c0` | `0x6c8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x45f4` | `0x45fc` | **`+0x8`** |

### Other Changes

```diff

-772.0.20.0.0
+772.40.11.0.0

-  Functions: 12398
-  Symbols:   2139
+  Functions: 12401
+  Symbols:   2140
Symbols:
+ GCC_except_table20
+ GCC_except_table24
+ ___os_log_helper_16_2_3_8_32_8_32_8_66
- GCC_except_table19
- GCC_except_table23
CStrings:
+ "%s: %s is nil in %{public}@. Stopping."
+ "%s: Could not resolve a host to present the Apple Account Terms and Conditions agreement confirmation; ending the flow to avoid stranding it."
+ "self"
- "%s: Self is nil in %{public}@. Stopping."
- "Unable to download"
- "Unable to install"
```
