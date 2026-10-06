## NANDTaskScheduler

> `/usr/libexec/NANDTaskScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf290` | `0xf5e8` | **`+0x358`** |
| `__TEXT.__oslogstring` | `0x2e6b` | `0x2f6f` | **`+0x104`** |
| `__DATA_CONST.__cfstring` | `0xa20` | `0xa60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1235` | `0x1259` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0x318` | `0x310` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-843.0.0.0.0
+847.0.0.0.0

-  Functions: 251
+  Functions: 249

-  CStrings:  741
+  CStrings:  749
CStrings:
+ "Failed to deregister inlineGC throughput: %@"
+ "Failed to register inlineGC throughput tracking: %@"
+ "IS High will skip lists."
+ "No new slowInlineGC this round."
+ "dLastInlineGCMiB"
+ "idlestack.inlineGC"
+ "idlestack_update_pre_round_stats - unexpected buf len %zu\n"
+ "nts_prst_log internal=%d, bootArgSet/Val=%d/%d"
```
