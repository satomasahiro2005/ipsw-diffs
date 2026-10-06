## sirireaderd

> `/usr/libexec/sirireaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c7c8` | `0x2c924` | **`+0x15c`** |
| `__TEXT.__cstring` | `0x537` | `0x557` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x233a` | `0x234a` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x99a` | `0x9aa` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xe78` | `0xe84` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x7b0` | `0x7bc` | **`+0xc`** |
| `__DATA.__data` | `0xfc0` | `0xfb8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x7e8` | `0x7e0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x750` | `0x758` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  CStrings:  428
+  CStrings:  429
Symbols:
+ _$s12FeatureFlags0aB3KeyP6domains12StaticStringVvgTj
+ _$s12FeatureFlags0aB3KeyP7features12StaticStringVvgTj
- _$s14SiriTTSService27SynthesizingRequestProtocolPAAE17optInNextGenVoiceSbvs
- _$sSS10describingSSx_tclufC
Functions:
~ sub_1000055a8 : 1100 -> 1088
~ sub_10000ca70 -> sub_10000ca64 : 2280 -> 2264
~ sub_100013e44 -> sub_100013e28 : 420 -> 416
~ sub_10001a580 -> sub_10001a560 : 1212 -> 1240
~ sub_10001aa3c -> sub_10001aa38 : 236 -> 268
~ sub_10001ab28 -> sub_10001ab44 : 232 -> 264
~ sub_10001ac10 -> sub_10001ac4c : 108 -> 128
~ sub_10001adb8 -> sub_10001ae08 : 1008 -> 992
~ sub_10001b4d4 -> sub_10001b514 : 2428 -> 2436
~ sub_10001c204 -> sub_10001c24c : 672 -> 680
~ sub_10001c4a4 -> sub_10001c4f4 : 3588 -> 3596
~ sub_1000227c4 -> sub_10002281c : 412 -> 388
~ sub_1000245c0 -> sub_100024600 : 2780 -> 2792
~ sub_1000250ac -> sub_1000250f8 : 592 -> 692
~ sub_10002867c -> sub_10002872c : 280 -> 276
~ sub_100028dd0 -> sub_100028e7c : 628 -> 764
~ sub_1000290e0 -> sub_100029214 : 424 -> 436
~ sub_100029288 -> sub_1000293c8 : 88 -> 92
~ sub_100029d04 -> sub_100029e48 : 388 -> 384
~ sub_100029e88 -> sub_100029fc8 : 436 -> 432
~ sub_10002a03c -> sub_10002a178 : 220 -> 232
~ sub_10002a118 -> sub_10002a260 : 224 -> 228
~ sub_10002a760 -> sub_10002a8ac : 784 -> 780
~ sub_10002ad44 -> sub_10002ae8c : 2420 -> 2400
~ sub_10002ba9c -> sub_10002bbd0 : 2712 -> 2704
~ sub_10002d140 -> sub_10002d26c : 476 -> 480
~ sub_10002d770 -> sub_10002d8a0 : 472 -> 476
~ sub_10002d948 -> sub_10002da7c : 256 -> 276
~ sub_10002da48 -> sub_10002db90 : 236 -> 256
CStrings:
+ "%s\\%s enabled=%{bool}d"
+ "siri_read_this_v3"
- "%s"
```
