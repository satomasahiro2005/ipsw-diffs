## AppleEthernetRL

> `/System/Library/Extensions/AppleEthernetRL.kext/AppleEthernetRL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x48958` | `0x498b8` | **`+0xf60`** |
| `__TEXT_EXEC.__text` | `0x27bf4` | `0x27bf8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-168.0.0.0.0
+169.0.0.0.0
Functions:
~ __ZN18AppleEthernetRLIPC17mailboxClientCallEjPvPi : 524 -> 520
~ __ZN15AppleEthernetRL5probeEP9IOServicePi : 1216 -> 1224
```
