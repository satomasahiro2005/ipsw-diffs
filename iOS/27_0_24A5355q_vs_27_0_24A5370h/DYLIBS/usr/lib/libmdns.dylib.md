## libmdns.dylib

> `/usr/lib/libmdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30e1c` | `0x310e8` | **`+0x2cc`** |
| `__AUTH_CONST.__auth_got` | `0xf10` | `0xf18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0x9e0` | **`-0x8`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1

-  Functions: 852
-  Symbols:   2069
+  Functions: 853
+  Symbols:   2071
Symbols:
+ GCC_except_table415
+ GCC_except_table419
+ GCC_except_table682
+ _mdns_querier_set_privacy_policy
+ _nw_resolver_config_get_oblivious_proxy_url
- GCC_except_table422
- GCC_except_table426
- GCC_except_table685
```
