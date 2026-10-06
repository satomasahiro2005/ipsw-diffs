## AppleEthernetRL

> `/System/Library/Extensions/AppleEthernetRL.kext/AppleEthernetRL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2818c` | `0x2821c` | **`+0x90`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`

### Other Changes

```diff

-175.40.1.0.0
-  Functions: 580
+175.40.2.0.0
+  Functions: 581
Symbols:
+ __Z10re_rar_setP8re_softcPh
+ __ZN15AppleEthernetRL18setHardwareAddressEP10ether_addr
- __ZL10re_rar_setP8re_softcPh
- __ZN26IOSkywalkEthernetInterface18setHardwareAddressEP10ether_addr
Functions:
+ __Z10re_rar_setP8re_softcPh
- __ZL10re_rar_setP8re_softcPh
+ __ZN15AppleEthernetRL18setHardwareAddressEP10ether_addr
```
