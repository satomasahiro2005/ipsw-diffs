## libcompression.dylib

> `/usr/lib/libcompression.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64e0c` | `0x64b88` | **`-0x284`** |

### Other Changes

```diff

-212.0.0.0.1
+212.0.1.0.0
Functions:
~ _DecodeVarLenUint8 : 456 -> 444
~ _BrotliBuildHuffmanTable : 560 -> 568
~ _DecodeContextMap : 1104 -> 1080
~ _BrotliDecoderDecompressStream : 4012 -> 4000
~ _SafeProcessCommands : 2844 -> 2796
~ _lz4raw_decode_buffer : 208 -> 168
~ _adler32 : 316 -> 308
~ _longest_match : 472 -> 484
~ _build_tree : 1168 -> 1184
~ _zlib_stream_get_encode_state_size : 60 -> 40
~ _lzbitmap_decode : 2212 -> 2220
~ sub_2be4d67bc -> sub_2bf15e744 : 4 -> 12
~ _zero_coder_decode : 280 -> 276
~ _zero_coder_encode : 320 -> 332
~ _CountsCreateWithBuffer : 404 -> 396
~ _lzx_huffman_tree_read_code : 308 -> 276
~ _lzx_huffman_tree_update_tree_using_pre_tree_encoding : 796 -> 748
~ _lzx_huffman_create_pre_tree : 272 -> 256
~ _RavGetOptimal : 4824 -> 4868
~ _BrotliSplitBlock : 13968 -> 13944
~ _BrotliSafeReadBits32Slow : 328 -> 304
~ _SafeDecodeCommandBlockSwitch : 808 -> 784
~ _SafeDecodeLiteralBlockSwitch : 884 -> 860
~ _SafeDecodeDistanceBlockSwitch : 832 -> 808
~ _yzip_jobs_encode : 1252 -> 1268
~ _LZFSEIBootBufferPushN : 224 -> 212
~ _BrotliHistogramCombineLiteral : 744 -> 748
~ _BrotliHistogramCombineCommand : 748 -> 752
~ _BrotliHistogramCombineDistance : 748 -> 752
~ _ComputeShortestPathFromNodes : 128 -> 104
~ _BrotliBuildAndStoreHuffmanTreeFast : 1792 -> 1784
~ _smb_lz77_encode_buffer : 900 -> 908
~ _cosmix_model_create : 312 -> 304
~ _lzx_decode_buffer : 2388 -> 2292
~ _CreateBackwardReferencesNH35 : 3620 -> 3568
~ _CreateBackwardReferencesNH55 : 3620 -> 3592
~ _CreateBackwardReferencesNH65 : 5500 -> 5312
~ _crc32 : 808 -> 828
~ _yzip_plane_encoder_phase1 : 1868 -> 1864
~ _deflate_rle : 828 -> 832
```
