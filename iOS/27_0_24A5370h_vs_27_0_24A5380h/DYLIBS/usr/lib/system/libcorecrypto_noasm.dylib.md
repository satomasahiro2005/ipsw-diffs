## libcorecrypto_noasm.dylib

> `/usr/lib/system/libcorecrypto_noasm.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8743c` | `0x87290` | **`-0x1ac`** |
| `__TEXT.__unwind_info` | `0x1c40` | `0x1c38` | **`-0x8`** |

### Other Changes

```diff

-2109.0.7.0.0
+2109.0.11.0.0
Functions:
~ _ccmlkem_poly_compress_encode_d4 : 1296 -> 1300
~ _ccmlkem_poly_compress_encode_d5 : 1824 -> 1816
~ _ccmlkem_poly_compress_encode_d10 : 1028 -> 1024
~ _ccmlkem_poly_compress_encode_d11 : 284 -> 280
~ _ccmlkem_poly_decode_decompress_d1 : 260 -> 256
~ _ccmlkem_poly_decode_decompress_d4 : 88 -> 84
~ _ccmlkem_poly_decode_decompress_d5 : 288 -> 284
~ _ccmlkem_poly_decode_decompress_d10 : 188 -> 184
~ _ccmlkem_poly_decode_decompress_d11 : 376 -> 356
~ _eay_RC4 : 604 -> 616
~ _deskey : 612 -> 608
~ _desfunc : 532 -> 528
~ _desfunc3 : 1020 -> 1004
~ _cckeccak_squeeze_internal : 932 -> 616
~ _ccrsa_decrypt_oaep_blinded_ws : 300 -> 308
~ _ccmldsa_poly_bitunpack_eta2 : 160 -> 156
~ _ccmldsa_poly_bitunpack_eta4 : 56 -> 48
~ _ccmldsa_poly_bitpack_t0 : 224 -> 220
~ _ccmldsa_poly_bitunpack_t0 : 300 -> 296
~ _ccmldsa_poly_bitpack_t1 : 140 -> 136
~ _ccmldsa_poly_bitunpack_t1 : 128 -> 124
~ _ccmldsa_poly_bitpack_z : 104 -> 100
~ _ccaes_gladman_encrypt : 3108 -> 3092
~ _ccaes_gladman_decrypt : 3292 -> 3268
~ _ccpolyzp_po2cyc_ctx_init_ws : 1784 -> 1796
```
