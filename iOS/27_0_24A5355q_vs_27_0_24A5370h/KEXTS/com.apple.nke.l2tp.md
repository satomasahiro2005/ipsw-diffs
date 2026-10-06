## com.apple.nke.l2tp

> `com.apple.nke.l2tp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x510` | **`+0x510`** |
| `__TEXT_EXEC.__text` | `0x3eac` | `0x3f30` | **`+0x84`** |

### Other Changes

```diff

-1027.0.0.0.0
+1029.0.0.0.0
Functions:
~ _l2tp_rfc_init : 68 -> 88
~ sub_fffffff00a786904 -> sub_fffffff00a81ebe8 : 96 -> 100
~ _l2tp_rfc_command : 2336 -> 2352
~ _l2tp_udp_init_threads : 372 -> 380
~ _l2tp_udp_dispose_threads : 380 -> 448
~ sub_fffffff00a789208 -> sub_fffffff00a82154c : 476 -> 492
```
