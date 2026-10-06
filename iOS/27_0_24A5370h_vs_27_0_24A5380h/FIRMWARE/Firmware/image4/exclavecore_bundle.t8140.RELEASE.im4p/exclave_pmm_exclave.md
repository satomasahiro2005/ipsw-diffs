## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_pmm_exclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x4f238` | `0x4edf8` | **`-0x440`** |
| `__TEXT.__text` | `0x4ce98` | `0x4d054` | **`+0x1bc`** |
| `__TEXT.__cstring` | `0x11d83` | `0x11e26` | **`+0xa3`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1485.0.0.0.3
+1490.0.5.0.0

-  CStrings:  1510
+  CStrings:  1514
Functions:
~ sub_7fff574 : 456 -> 364
~ sub_7fff73c -> sub_7fff6e0 : 44 -> 144
~ sub_8002e24 -> sub_8002e2c : 2176 -> 2204
~ sub_8007f68 -> sub_8007f8c : 1100 -> 1076
~ sub_80089f4 -> sub_8008a00 : 1380 -> 1500
~ sub_800b50c -> sub_800b590 : 112 -> 108
~ sub_8017838 -> sub_80178b8 : 476 -> 484
~ sub_801d94c -> sub_801d9d4 : 1408 -> 1380
~ sub_80207ac -> sub_8020818 : 3152 -> 3156
~ sub_8032828 -> sub_8032898 : 496 -> 524
~ sub_80360b8 -> sub_8036144 : 80 -> 84
~ sub_8036178 -> sub_8036208 : 272 -> 256
~ sub_8036c00 -> sub_8036c80 : 484 -> 480
~ sub_80378f8 -> sub_8037974 : 936 -> 960
~ sub_8037ca0 -> sub_8037d34 : 988 -> 1100
~ sub_803807c -> sub_8038180 : 304 -> 248
~ sub_80381ac -> sub_8038278 : 32 -> 212
~ sub_80381cc -> sub_803834c : 248 -> 232
~ sub_80382c4 -> sub_8038434 : 556 -> 568
~ sub_8038774 -> sub_80388f0 : 668 -> 672
~ sub_8039230 -> sub_80393b0 : 540 -> 544
~ sub_803944c -> sub_80395d0 : 108 -> 124
~ sub_803b528 -> sub_803b6bc : 788 -> 828
~ sub_80499f4 -> sub_8049bb0 : 36 -> 40
CStrings:
+ "!os_mul_overflow(nu + PAD_ALLOC(align), UNIT_SIZE, &nb)"
+ "morecore"
+ "no fixup data for faultable range [%#lx, %#lx) found"
+ "pmmtag_l4_decode: unknown tagtype %zu"
+ "write_float_string"
- "write_float"
```
