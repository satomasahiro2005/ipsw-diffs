## libquic.dylib

> `/usr/lib/libquic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd01cc` | `0xd0200` | **`+0x34`** |

### Other Changes

```text
Functions:
~ _quic_tp_get : 648 -> 656
~ _quic_frame_alloc_ack_block : 1444 -> 1448
~ _quic_ack_for_pn_space : 2896 -> 2904
~ _quic_packet_builder_append_for_pn_space : 296 -> 300
~ _quic_ack_bitstring_xor : 804 -> 808
~ _quic_ack_bitstring_nset : 632 -> 636
~ _quic_packet_builder_flush_for_pn_space : 656 -> 660
~ _quic_cid_array_insert : 1208 -> 1212
~ _quic_packet_builder_prepend_for_pn_space : 680 -> 684
~ _quic_cid_array_find_by_srt : 540 -> 544
~ ___quic_conn_inject_packet_block_invoke_2 : 376 -> 380
```
