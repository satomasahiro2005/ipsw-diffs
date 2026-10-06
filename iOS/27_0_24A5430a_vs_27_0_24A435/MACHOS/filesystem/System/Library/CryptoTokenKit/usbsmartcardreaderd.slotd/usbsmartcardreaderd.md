## usbsmartcardreaderd

> `/System/Library/CryptoTokenKit/usbsmartcardreaderd.slotd/usbsmartcardreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x670` | `0x680` | **`+0x10`** |
| `__TEXT.__text` | `0x176c0` | `0x176b4` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x348` | `0x350` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   150
+  Symbols:   151
Symbols:
+ _objc_retain_x28
Functions:
~ sub_100003f88 : 2676 -> 2672
~ sub_100009ae0 -> sub_100009adc : 1108 -> 1100
```
