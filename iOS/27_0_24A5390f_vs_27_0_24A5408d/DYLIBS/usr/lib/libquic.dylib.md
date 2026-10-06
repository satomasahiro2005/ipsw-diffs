## libquic.dylib

> `/usr/lib/libquic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0174` | `0xd01cc` | **`+0x58`** |
| `__TEXT.__cstring` | `0x87e1` | `0x8823` | **`+0x42`** |
| `__DATA_CONST.__const` | `0x2590` | `0x25b0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x670` | `0x660` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdd0` | `0xdd8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd28` | `0xd30` | **`+0x8`** |

### Other Changes

```diff

-6681.0.514.502.1
+6681.2.2.0.0

-  Functions: 1153
-  Symbols:   1657
-  CStrings:  2604
+  Functions: 1156
+  Symbols:   1660
+  CStrings:  2606
Symbols:
+ _nw_parameters_is_fallback
+ _quic_conn_is_cellular_fallback
+ _quic_path_set_is_preferred_address
CStrings:
+ "quic_conn_is_cellular_fallback"
+ "quic_path_set_is_preferred_address"
```
