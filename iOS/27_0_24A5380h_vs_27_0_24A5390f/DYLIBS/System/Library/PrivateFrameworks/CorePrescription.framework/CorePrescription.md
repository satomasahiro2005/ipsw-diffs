## CorePrescription

> `/System/Library/PrivateFrameworks/CorePrescription.framework/CorePrescription`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ab74` | `0x4ad88` | **`+0x214`** |
| `__TEXT.__objc_methlist` | `0x3c14` | `0x3c30` | **`+0x1c`** |
| `__AUTH_CONST.__objc_const` | `0x8bc8` | `0x8bd8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x17c8` | `0x17d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1728` | `0x1730` | **`+0x8`** |

### Other Changes

```diff

-230.0.2.0.0
+230.0.3.0.0

-  Functions: 2536
-  Symbols:   2372
+  Functions: 2540
+  Symbols:   2375
Symbols:
+ -[CRXFCorePrescriptionServiceClient setPreferredLanguages:completionHandler:]
+ GCC_except_table149
+ GCC_except_table151
+ ___77-[CRXFCorePrescriptionServiceClient setPreferredLanguages:completionHandler:]_block_invoke
+ ___77-[CRXFCorePrescriptionServiceClient setPreferredLanguages:completionHandler:]_block_invoke_2
- GCC_except_table146
- GCC_except_table148
```
