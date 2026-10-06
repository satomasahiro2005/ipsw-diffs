## libtailspin.dylib

> `/usr/lib/libtailspin.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2862c` | `0x28b4c` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x2cbe` | `0x2d4a` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x1e20` | `0x1ea0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x34cd` | `0x3539` | **`+0x6c`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a0` | `0x5b8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1c08` | `0x1c18` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xad0` | `0xad8` | **`+0x8`** |
| `__TEXT.__const` | `0x181` | `0x189` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa80` | `0xa88` | **`+0x8`** |

### Other Changes

```diff

-262.0.0.0.0
+264.0.0.0.0

-  Symbols:   552
-  CStrings:  632
+  Symbols:   555
+  CStrings:  638
Symbols:
+ _OBJC_CLASS_$_NSCompoundPredicate
+ _OBJC_CLASS_$_NSPredicate
+ _TSPDumpOptions_OSSignpostLogSubsystemCategories
Functions:
~ sub_2be909cc4 -> sub_2bfe7acc4 : 1164 -> 1160
~ sub_2be90a150 -> sub_2bfe7b14c : 792 -> 788
~ sub_2be90a984 -> sub_2bfe7b97c : 764 -> 772
~ sub_2be90c4ac -> sub_2bfe7d4ac : 292 -> 288
~ _tailspin_write_metadata_chunk : 8356 -> 8348
~ _tailspin_write_os_signpost_support_chunks : 588 -> 1416
~ _create_and_start_cputrace_live_recording : 5088 -> 5084
~ sub_2be9123cc -> sub_2bfe836f8 : 5272 -> 5268
~ sub_2be913880 -> sub_2bfe84ba8 : 2256 -> 2296
~ sub_2be91427c -> sub_2bfe855cc : 500 -> 496
~ _main_binary_for_pid_in_ktrace : 2048 -> 2008
~ sub_2be916714 -> sub_2bfe87a38 : 84 -> 80
~ sub_2be917ab4 -> sub_2bfe88dd4 : 616 -> 612
~ sub_2be918b14 -> sub_2bfe89e30 : 648 -> 644
~ sub_2be919f64 -> sub_2bfe8b27c : 332 -> 328
~ _tailspin_kdbg_filter_subclass_set : 72 -> 76
~ _tailspin_kdbg_filter_subclass_get : 28 -> 32
~ _tailspin_cputrace_enabled_set_with_options : 556 -> 552
~ _tailspin_augment_output_with_request_id : 1552 -> 1660
~ sub_2be91cba4 -> sub_2bfe8df28 : 2672 -> 2676
~ sub_2be91dd54 -> sub_2bfe8f0dc : 616 -> 612
~ sub_2be922714 -> sub_2bfe93a98 : 2776 -> 2792
~ sub_2be9231ec -> sub_2bfe94580 : 352 -> 368
~ sub_2be92334c -> sub_2bfe946f0 : 236 -> 240
~ sub_2be923438 -> sub_2bfe947e0 : 252 -> 264
~ sub_2be923ac8 -> sub_2bfe94e7c : 996 -> 1020
~ sub_2be923eac -> sub_2bfe95278 : 492 -> 504
~ sub_2be92420c -> sub_2bfe955e4 : 836 -> 832
~ sub_2be924550 -> sub_2bfe95924 : 588 -> 620
~ sub_2be92479c -> sub_2bfe95b90 : 184 -> 180
~ sub_2be924868 -> sub_2bfe95c58 : 3872 -> 3880
~ sub_2be925788 -> sub_2bfe96b80 : 1056 -> 1068
~ sub_2be926d7c -> sub_2bfe98180 : 496 -> 560
~ sub_2be926f6c -> sub_2bfe983b0 : 484 -> 508
~ sub_2be927150 -> sub_2bfe985ac : 644 -> 632
~ sub_2be9273d4 -> sub_2bfe98824 : 668 -> 652
~ sub_2be927670 -> sub_2bfe98ab0 : 1064 -> 1112
~ sub_2be9281dc -> sub_2bfe9964c : 244 -> 256
~ sub_2be92a10c -> sub_2bfe9b588 : 248 -> 252
~ sub_2be92a5b4 -> sub_2bfe9ba34 : 260 -> 272
~ sub_2be92b46c -> sub_2bfe9c8f8 : 544 -> 616
~ sub_2be92b68c -> sub_2bfe9cb60 : 536 -> 552
~ sub_2be92b8a4 -> sub_2bfe9cd88 : 712 -> 704
~ sub_2be92bb6c -> sub_2bfe9d048 : 708 -> 728
~ sub_2be92be30 -> sub_2bfe9d320 : 1160 -> 1208
~ sub_2be92c904 -> sub_2bfe9de24 : 268 -> 272
~ sub_2be92e988 -> sub_2bfe9feac : 120 -> 116
CStrings:
+ "*"
+ "Skipping malformed subsystem/category filter entry: %{public}@"
+ "Skipping subsystem/category filter entry with non-string members: %{public}@"
+ "subsystem == %@"
+ "subsystem == %@ AND category == %@"
+ "tailspin_dump_option_signpost_log_subsystem_categories"
```
