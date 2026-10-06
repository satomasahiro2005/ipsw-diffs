## AccessoryTransportExtension

> `/System/Library/Frameworks/AccessoryTransportExtension.framework/AccessoryTransportExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25330` | `0x25280` | **`-0xb0`** |
| `__TEXT.__unwind_info` | `0xab0` | `0xaa8` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x8aa` | `0x8b0` | **`+0x6`** |

### Other Changes

```diff

-2700.34.0.0.0
+2701.2.0.0.0
Functions:
~ sub_247518210 -> sub_24b298210 : 2376 -> 2888
~ sub_247518b58 -> sub_24b298d58 : 4848 -> 280
~ sub_247519e48 -> sub_24b298e70 : 280 -> 184
~ sub_247519f60 -> sub_24b298f28 : 184 -> 296
~ sub_24751a018 -> sub_24b299050 : 296 -> 104
~ sub_24751a140 -> sub_24b2990b8 : 104 -> 636
~ sub_24751a1a8 -> sub_24b299334 : 636 -> 4160
~ sub_24751cab0 -> ___swift_closure_destructor.74 : 4 -> 72
~ _block_copy_helper -> sub_24b29ca48 : 16 -> 192
~ _block_destroy_helper -> sub_24b29cb08 : 8 -> 4
~ sub_24751cadc -> _block_destroy_helper : 28 -> 8
~ sub_24751caf8 -> ___swift_closure_destructor.84 : 28 -> 16
~ sub_24751cb14 -> sub_24b29cb34 : 88 -> 28
~ __swift_implicitisolationactor_to_executor_cast -> sub_24b29cb50 : 64 -> 28
~ sub_24751cbac -> sub_24b29cb6c : 104 -> 88
~ ___swift_closure_destructor.85 -> __swift_implicitisolationactor_to_executor_cast : 72 -> 64
~ sub_24751cc5c -> sub_24b29cc04 : 192 -> 104
```
