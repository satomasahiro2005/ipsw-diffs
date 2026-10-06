## libperfcheck.dylib

> `/usr/lib/libperfcheck.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2ec` | `0xa3bc` | **`+0xd0`** |
| `__AUTH_CONST.__auth_got` | `0x440` | `0x438` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x208` | `0x200` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   308
+  Symbols:   307
Symbols:
- _objc_retain_x28
Functions:
~ _pc_session_destroy : 316 -> 320
~ _pc_session_get_value : 1200 -> 1276
~ _snapshot_create : 528 -> 560
~ __add_metric : 824 -> 920
~ _measure_proc_snapshot : 956 -> 852
~ _pc_session_end : 316 -> 328
~ _pc_snapshot_destroy : 116 -> 128
~ _session_find_custom_metric_id : 56 -> 68
~ _pc_session_create_snapshot_buf : 984 -> 968
~ _dump_compare_metrics : 716 -> 712
~ _create_meas_metrics : 188 -> 204
~ __print_compare_meas : 548 -> 556
~ _print_metric_value : 1792 -> 1804
~ _findPIDForProcName : 448 -> 452
~ _pc_handle_ep_help_args : 372 -> 384
~ _pc_session_config_with_ep_args : 2848 -> 2840
~ _run_easyperf : 1040 -> 1036
~ _pc_session_set_snapshots_bufs : 804 -> 808
~ _pc_session_process_pdfile : 1668 -> 1660
~ _snapshot_create_with_buf : 1388 -> 1436
~ ____processContainer_block_invoke_2 : 1784 -> 1780
~ _makePDContainers : 1140 -> 1136
~ _makeMeasurementFooter : 1456 -> 1448
~ __outputVarValues : 468 -> 464
~ __variableDisplayStringWithDiffs : 620 -> 616
~ _pc_session_record_values : 556 -> 552
~ _emit_perfdata_v1 : 768 -> 760
~ _get_name_metricid : 96 -> 92
~ _get_metricid_name : 124 -> 144
~ _pc_session_set_threshold : 264 -> 260
~ _pc_session_set_default_thresholds : 168 -> 180
~ _pc_session_clear_thresholds : 80 -> 84
~ _get_thresholds : 104 -> 100
~ _pc_session_add_custom_metric : 384 -> 400
```
