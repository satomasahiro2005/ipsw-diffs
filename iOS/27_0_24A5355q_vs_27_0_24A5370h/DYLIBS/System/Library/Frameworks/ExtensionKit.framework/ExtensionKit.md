## ExtensionKit

> `/System/Library/Frameworks/ExtensionKit.framework/ExtensionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x318b4` | `0x31998` | **`+0xe4`** |
| `__AUTH_CONST.__auth_got` | `0xca0` | `0xc98` | **`-0x8`** |

### Other Changes

```diff

-289.1.0.0.0
+289.2.0.0.0

-  Symbols:   1615
+  Symbols:   1614
Symbols:
- _objc_retain_x10
Functions:
~ ___60-[_EXHostViewControllerSession _internalQueue_prepareToHost]_block_invoke_3 : 128 -> 124
~ -[_EXHostSessionDriver invalidateDeactivatingSessions] : 452 -> 448
~ sub_209d9ac58 -> sub_20a98ec50 : 584 -> 628
~ sub_209d9bdb8 -> sub_20a98fddc : 108 -> 112
~ ___swift_closure_destructorTm : 120 -> 128
~ sub_209d9be9c -> sub_20a98fecc : 124 -> 128
~ sub_209d9f2c4 -> sub_20a9932f8 : 1408 -> 1416
~ sub_209da0144 -> sub_20a994180 : 1056 -> 1068
~ sub_209da2614 -> sub_20a99665c : 480 -> 484
~ sub_209da2aa4 -> sub_20a996af0 : 1656 -> 1688
~ sub_209da311c -> sub_20a997188 : 404 -> 424
~ sub_209da32b0 -> sub_20a997330 : 628 -> 648
~ sub_209da3524 -> sub_20a9975b8 : 1064 -> 1072
~ sub_209da3db0 -> sub_20a997e4c : 416 -> 412
~ sub_209da402c -> sub_20a9980c4 : 392 -> 396
~ sub_209da41b4 -> sub_20a998250 : 360 -> 372
~ sub_209da70c0 -> sub_20a99b168 : 88 -> 84
~ ___swift_closure_destructor.19 : 140 -> 148
~ sub_209dab284 -> sub_20a99f330 : 104 -> 108
~ sub_209dab57c -> sub_20a99f62c : 124 -> 128
~ sub_209daf89c -> sub_20a9a3950 : 408 -> 416
~ sub_209daff44 -> sub_20a9a4000 : 1344 -> 1356
~ sub_209db04b0 -> sub_20a9a4578 : 104 -> 108
~ sub_209db0518 -> sub_20a9a45e4 : 104 -> 108
~ ___swift_closure_destructor.28Tm : 140 -> 148
~ sub_209db7500 -> sub_20a9ab5d8 : 408 -> 416
~ sub_209db8580 -> sub_20a9ac660 : 104 -> 108
~ sub_209db87a8 -> sub_20a9ac88c : 280 -> 276
~ sub_209db9190 -> sub_20a9ad270 : 196 -> 188
~ ___swift_closure_destructor.17Tm : 140 -> 148
~ sub_209dbca44 -> sub_20a9b0b24 : 108 -> 112
```
