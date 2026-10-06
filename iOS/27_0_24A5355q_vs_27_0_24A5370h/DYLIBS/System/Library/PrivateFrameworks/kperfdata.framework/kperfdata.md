## kperfdata

> `/System/Library/PrivateFrameworks/kperfdata.framework/kperfdata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8320` | `0x82ec` | **`-0x34`** |

### Other Changes

```text
Functions:
~ __kpdecode_cursor_next_kevent : 516 -> 512
~ _batch_get_bytes : 716 -> 688
~ _kpep_config_create : 404 -> 400
~ _kpep_config_decode_event : 740 -> 752
~ _kpep_config_remove_event : 316 -> 312
~ _kpep_config_kpc_map : 120 -> 112
~ _kpep_config_events : 68 -> 76
~ _kpep_config_kpc_periods : 212 -> 216
~ _init_db_from_plist : 1576 -> 1544
~ _kpep_db_free : 192 -> 184
~ _init_db_from_aliases_dict : 412 -> 400
~ _get_to_stage_body : 496 -> 492
~ _kpfile_read_threadmap : 360 -> 376
~ _kpfile_write_threadmap : 600 -> 608
~ _kpfile_read_events : 1172 -> 1180
~ _kpfile_write_events : 936 -> 940
~ _add_string_data : 300 -> 304
~ _safe_encode : 1000 -> 996
~ _kdbg_comp_decode : 436 -> 432
~ _encode_row : 100 -> 96
```
