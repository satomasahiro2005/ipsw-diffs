## Polaris

> `/System/Library/PrivateFrameworks/Polaris.framework/Polaris`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18e16c` | `0x18df70` | **`-0x1fc`** |
| `__TEXT.__cstring` | `0x1697a` | `0x169da` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x35ac` | `0x35dc` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x26c0` | `0x26d0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2410` | `0x2418` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2010` | `0x2018` | **`+0x8`** |

### Other Changes

```diff

-256.0.3.0.0
+256.0.5.0.0

-  Functions: 7539
+  Functions: 7540

-  CStrings:  3681
+  CStrings:  3682
CStrings:
+ "08:51:35"
+ "Aug  4 2026"
+ "Cannot restart deployments as we have already established a connection to polarisd"
- "00:50:40"
- "Jul 11 2026"
```
