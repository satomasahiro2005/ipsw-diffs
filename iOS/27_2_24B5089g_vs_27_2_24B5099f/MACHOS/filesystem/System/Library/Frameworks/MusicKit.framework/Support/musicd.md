## musicd

> `/System/Library/Frameworks/MusicKit.framework/Support/musicd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a010` | `0x29c5c` | **`-0x3b4`** |
| `__DATA_CONST.__got` | `0x478` | `0x468` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1470` | `0x1460` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xa40` | `0xa38` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4026.200.22.0.0
+4026.200.27.0.0

-  Symbols:   579
+  Symbols:   578
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _swift_conformsToProtocol2
Functions:
~ sub_1000116b0 : 692 -> 552
~ sub_1000168a8 -> sub_10001681c : 688 -> 548
~ sub_100019610 -> sub_1000194f8 : 696 -> 556
~ sub_10001adec -> sub_10001ac48 : 696 -> 556
~ sub_10001ca68 -> sub_10001c838 : 960 -> 768
~ sub_10001f814 -> sub_10001f524 : 408 -> 352
~ sub_1000205f8 -> sub_1000202d0 : 672 -> 532
```
