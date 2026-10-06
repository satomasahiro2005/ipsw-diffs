## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25b94` | `0x25d60` | **`+0x1cc`** |
| `__TEXT.__objc_methname` | `0x70a6` | `0x70e6` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x4d40` | `0x4d60` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x280` | `0x28c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1a98` | `0x1aa0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x13af` | `0x13b5` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2467.1.2.0.0
+2470.0.0.0.0

-  CStrings:  1515
+  CStrings:  1516
Functions:
~ sub_3924 : 576 -> 572
~ sub_5860 -> sub_585c : 764 -> 800
~ sub_6134 -> sub_6154 : 400 -> 396
~ sub_6500 -> sub_651c : 340 -> 336
~ sub_6658 -> sub_6670 : 412 -> 408
~ sub_67f4 -> sub_6808 : 360 -> 356
~ sub_6cd0 -> sub_6ce0 : 788 -> 784
~ sub_7364 -> sub_7370 : 580 -> 576
~ sub_7690 -> sub_7698 : 544 -> 540
~ sub_88b0 -> sub_88b4 : 336 -> 332
~ sub_8a80 : 376 -> 372
~ sub_8bf8 -> sub_8bf4 : 276 -> 272
~ sub_8e78 -> sub_8e70 : 368 -> 364
~ sub_9140 -> sub_9134 : 336 -> 332
~ sub_93f0 -> sub_93e0 : 272 -> 284
~ sub_9580 -> sub_957c : 128 -> 164
~ sub_9918 -> sub_9938 : 912 -> 924
~ sub_9ee0 -> sub_9f0c : 516 -> 512
~ sub_bac4 -> sub_baec : 292 -> 288
~ sub_c2ec -> sub_c310 : 756 -> 752
~ sub_c5e0 -> sub_c600 : 736 -> 732
~ sub_d454 -> sub_d470 : 704 -> 724
~ sub_e130 -> sub_e160 : 652 -> 648
~ sub_15674 -> sub_156a0 : 400 -> 396
~ sub_18034 -> sub_1805c : 1160 -> 1220
~ sub_18e1c -> sub_18e80 : 1664 -> 1712
~ sub_19570 -> sub_19604 : 1800 -> 1848
~ sub_19d70 -> sub_19e34 : 1676 -> 1724
~ sub_2082c -> sub_20920 : 304 -> 300
~ sub_20ecc -> sub_20fbc : 280 -> 276
~ sub_21ec0 -> sub_21fac : 772 -> 796
~ sub_225b4 -> sub_226b8 : 300 -> 304
~ sub_226e0 -> sub_227e8 : 300 -> 304
~ sub_2280c -> sub_22918 : 300 -> 304
~ sub_22938 -> sub_22a48 : 300 -> 304
~ sub_22a64 -> sub_22b78 : 620 -> 604
~ sub_22f04 -> sub_23008 : 116 -> 132
~ sub_24668 -> sub_2477c : 672 -> 680
~ sub_24908 -> sub_24a24 : 2256 -> 2308
~ sub_251d8 -> sub_25328 : 116 -> 124
~ sub_25450 -> sub_255a8 : 3052 -> 3060
~ sub_26d80 -> sub_26ee0 : 2148 -> 2208
~ sub_276e8 -> sub_27884 : 456 -> 476
~ sub_27958 -> sub_27b08 : 1000 -> 1028
CStrings:
+ "kAXVOTBrailleSceneClientIdentifier"
+ "setActiveSceneTrackingEnabled:forSceneClientIdentifier:"
- "kAXZoomSceneClientIdentifier"
```
