## libcmph.dylib

> `/usr/lib/libcmph.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfd8c` | `0xfafc` | **`-0x290`** |

### Other Changes

```text
Functions:
~ _select_query_packed : 164 -> 156
~ _select_next_query_packed : 136 -> 128
~ _bdz_new : 2964 -> 2804
~ _bdz_search_packed : 504 -> 472
~ _bdz_dump_graph : 176 -> 188
~ _bdz_ph_new : 2656 -> 2524
~ _bdz_ph_dump_graph : 240 -> 248
~ _bmz_new : 3276 -> 3272
~ _bmz_load : 400 -> 404
~ _bmz_traverse : 320 -> 308
~ _bmz8_new : 3492 -> 3420
~ _bmz8_search : 136 -> 132
~ _bmz8_search_packed : 184 -> 180
~ _bmz8_traverse : 328 -> 308
~ _brz_config_set_hashfuncs : 60 -> 48
~ _brz_load : 784 -> 764
~ _brz_destroy : 204 -> 192
~ _brz_pack : 436 -> 416
~ _brz_packed_size : 248 -> 240
~ _buffer_manager_new : 212 -> 208
~ _buffer_manager_destroy : 112 -> 108
~ _chd_ph_new : 2712 -> 2704
~ _place_bucket_probe : 376 -> 368
~ _chm_new : 1048 -> 1040
~ _chm_traverse : 252 -> 244
~ _chm_load : 400 -> 404
~ ___cmph_load : 264 -> 260
~ _compressed_rank_generate : 440 -> 436
~ _compressed_seq_generate : 700 -> 688
~ _fch_new : 1940 -> 1936
~ _fch_buckets_new : 160 -> 168
~ _fch_buckets_get_indexes_sorted_by_size : 316 -> 312
~ _fch_buckets_print : 212 -> 204
~ _fch_buckets_destroy : 180 -> 164
~ _graph_clear_edges : 116 -> 104
~ _graph_is_cyclic : 228 -> 224
~ _cyclic_del_edge : 196 -> 192
~ _graph_node_is_critical : 48 -> 44
~ _graph_obtain_critical_nodes : 472 -> 448
~ _find_degree1_edge : 180 -> 172
~ _select_query : 144 -> 136
~ _select_next_query : 136 -> 128
```
