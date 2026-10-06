## Rhine

> `/System/Library/ScreenReader/BrailleTables/Rhine.brailletable/Rhine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e994` | `0x1f218` | **`+0x884`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_e9c : 412 -> 408
~ _find_in : 76 -> 108
~ _equals_nocase : 72 -> 88
~ _equals : 56 -> 72
~ _zweiformig_enabled : 224 -> 216
~ _equals_zweiformig : 356 -> 352
~ _equals_mehrformig : 196 -> 192
~ _is_url : 620 -> 624
~ _no_exception : 336 -> 368
~ _init_index : 84 -> 64
~ _reset_index : 32 -> 28
~ _create_buffer : 148 -> 140
~ _is_common_abbrev : 480 -> 476
~ _is_measurement : 728 -> 724
~ _timespec_follows : 220 -> 228
~ _upperchar_follows : 396 -> 384
~ _brl_add_exception : 896 -> 924
~ _brl_clear_exceptions : 76 -> 100
~ _brl_convert_to_utf : 516 -> 512
~ _brl_process_command : 2172 -> 2248
~ _upper_digit : 184 -> 188
~ _map_char : 652 -> 656
~ _add_num : 240 -> 256
~ _is_newline : 104 -> 100
~ _is_date : 180 -> 176
~ _is_lower_num : 2076 -> 2104
~ _add_seg : 5832 -> 5892
~ _add_whitespace : 112 -> 120
~ _no_abbrev : 616 -> 648
~ _no_locution : 272 -> 284
~ _process_quotes : 708 -> 740
~ _process_supersub : 1304 -> 1300
~ _wh_forward_translate : 44228 -> 44756
~ _backward_disabled : 168 -> 180
~ _bwd_fetch_char : 900 -> 888
~ _bwd_fetch_ueb_char : 120 -> 116
~ _bwd_rightchar_follows : 340 -> 356
~ _bwd_keep_contraction : 192 -> 208
~ _bwd_add_seg : 3980 -> 4048
~ _bwd_resolve_nospace : 308 -> 324
~ _bwd_add_rightchars : 668 -> 684
~ _bwd_no_locution : 832 -> 868
~ _bwd_generic_abbrev : 88 -> 84
~ _bwd_no_abbrev : 696 -> 712
~ _wh_backward_translate : 32388 -> 33520
~ sub_1ecc4 -> sub_1f548 : 168 -> 172
~ sub_1edfc -> sub_1f684 : 940 -> 936
```
