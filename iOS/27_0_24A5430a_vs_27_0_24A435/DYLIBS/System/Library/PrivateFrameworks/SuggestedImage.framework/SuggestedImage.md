## SuggestedImage

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/SuggestedImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8060` | `0xf80dc` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__TEXT.__const` | `0x7a6d` | `0x7aad` | **`+0x40`** |
| `__TEXT.__cstring` | `0x5a06` | `0x5a26` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1330` | `0x1340` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c0` | `0x4c8` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   1695
-  CStrings:  459
+  Symbols:   1699
+  CStrings:  461
Symbols:
+ _MGCopyAnswer
+ _MGIsDeviceOfType
+ _OUTLINED_FUNCTION_3
+ _prefersGenericWallpaperSizes.prefersGenericWallpaperSizes
Functions:
~ __ZNSt3__16vectorIjNS_9allocatorIjEEE6resizeEm : 284 -> 288
~ +[SIWallpaperUtilities prefersGenericWallpaperSizes] : 52 -> 56
~ ___52+[SIWallpaperUtilities prefersGenericWallpaperSizes]_block_invoke : 4 -> 252
~ sub_2342ed95c -> sub_234bf5a5c : 544 -> 548
~ sub_234306c8c -> sub_234c0ed90 : 692 -> 696
~ sub_2343271dc -> sub_234c2f2e4 : 860 -> 856
~ sub_2343403cc -> sub_234c484d0 : 5336 -> 5340
~ sub_234343734 -> sub_234c4b83c : 1144 -> 1148
~ sub_234360eb0 -> sub_234c68fbc : 1456 -> 1464
~ sub_234362738 -> sub_234c6a84c : 1336 -> 1348
~ sub_23436413c -> sub_234c6c25c : 1576 -> 1580
~ sub_23436518c -> sub_234c6d2b0 : 1544 -> 1548
~ sub_2343661a8 -> sub_234c6e2d0 : 1212 -> 1220
~ sub_234381938 -> sub_234c89a68 : 1108 -> 1100
~ sub_2343a91b8 -> sub_234cb12e0 : 8512 -> 8296
~ sub_2343b73fc -> sub_234cbf44c : 2572 -> 2584
~ sub_2343baf10 -> sub_234cc2f6c : 648 -> 652
~ sub_2343bb198 -> sub_234cc31f8 : 352 -> 356
~ sub_2343bb484 -> sub_234cc34e8 : 356 -> 360
~ sub_2343bb744 -> sub_234cc37ac : 680 -> 684
~ __ZNSt3__16vectorImNS_9allocatorImEEE6resizeEm : 284 -> 288
~ __ZNSt3__114__split_bufferIPN8internal6marisa8grimoire4trie5RangeENS_9allocatorIS6_EEE12emplace_backIJS6_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__114__split_bufferIPN8internal6marisa8grimoire4trie5RangeERNS_9allocatorIS6_EEE12emplace_backIJS6_EEEvDpOT_ : 256 -> 260
~ __ZNSt3__122__rotate_random_accessB9fqe220106INS_17_ClassicAlgPolicyEPN8internal6marisa8grimoire4trie13WeightedRangeES7_EET0_S8_S8_T1_ : 216 -> 212
~ __ZN8internal6marisa8grimoire9algorithm7details4sortIPNS1_4trie5EntryEEEmT_S8_m : 1000 -> 1004
~ __ZN8internal6marisa8grimoire6vector12_GLOBAL__N_110select_bitEmmy : 128 -> 132
CStrings:
+ "TargetSubType"
+ "V68"
```
