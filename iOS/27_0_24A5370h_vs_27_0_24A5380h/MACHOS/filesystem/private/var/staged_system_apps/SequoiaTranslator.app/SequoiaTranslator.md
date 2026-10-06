## SequoiaTranslator

> `/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2faa28` | `0x2faf0c` | **`+0x4e4`** |
| `__TEXT.__oslogstring` | `0xdabb` | `0xdafb` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x8000` | `0x8020` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4008` | `0x4018` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8b88` | `0x8b90` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-384.1.0.0.0
+384.3.0.0.0

-  Symbols:   3810
-  CStrings:  4518
+  Symbols:   3812
+  CStrings:  4519
Symbols:
+ _$s13TranslationUI13LanguageModelV10modalitiesSo25_LTLanguageStatusModalityVvg
+ _$sSo25_LTLanguageStatusModalityV13TranslationUIE12hasSpeechOutSbvg
Functions:
~ sub_100031680 : 896 -> 892
~ sub_10004c8c0 -> sub_10004c8bc : 2280 -> 3132
~ sub_1000e21ec -> sub_1000e253c : 720 -> 712
~ sub_1001c57e0 -> sub_1001c5b28 : 2216 -> 2232
~ sub_1001e69e4 -> sub_1001e6d3c : 1552 -> 1520
~ sub_10021b410 -> sub_10021b748 : 624 -> 616
~ sub_1002e5434 -> sub_1002e5764 : 916 -> 900
~ sub_1002ea14c -> sub_1002ea46c : 436 -> 576
~ sub_1002ea300 -> sub_1002ea6ac : 408 -> 536
~ sub_1002ea8c4 -> sub_1002eacf0 : 284 -> 364
~ sub_1002eaae4 -> sub_1002eaf60 : 328 -> 452
~ sub_1002eaf30 -> sub_1002eb428 : 344 -> 324
~ sub_1002eb0b4 -> sub_1002eb598 : 356 -> 336
~ sub_1002eb504 -> sub_1002eb9d4 : 300 -> 380
~ sub_1002f5ab4 -> sub_1002f5fd4 : 856 -> 852
~ sub_1002f6d84 -> sub_1002f72a0 : 972 -> 964
~ sub_1002f72f8 -> sub_1002f780c : 412 -> 408
~ sub_1002f7494 -> sub_1002f79a4 : 396 -> 392
~ sub_1002f7620 -> sub_1002f7b2c : 412 -> 408
~ sub_1002f77bc -> sub_1002f7cc4 : 392 -> 388
~ sub_1002f7944 -> sub_1002f7e48 : 392 -> 388
~ sub_1002fa4d8 -> sub_1002fa9d8 : 1032 -> 1020
~ sub_1002fa8e0 -> sub_1002fadd4 : 700 -> 692
~ sub_1002fab9c -> sub_1002fb088 : 800 -> 792
CStrings:
+ "%{public}s: not in availableLanguages"
+ "%{public}s: traditional Translate pair not installed"
+ "2026-06-29 22:16:17"
- "%s: traditional Translate pair not installed"
- "2026-06-17 23:48:48"
```
