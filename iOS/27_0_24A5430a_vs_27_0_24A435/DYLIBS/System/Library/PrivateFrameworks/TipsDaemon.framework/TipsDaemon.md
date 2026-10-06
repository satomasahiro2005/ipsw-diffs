## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0730` | `0xa0878` | **`+0x148`** |
| `__AUTH_CONST.__objc_intobj` | `0x168` | `0x1c8` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x2a00` | `0x2a40` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x78` | `0xa8` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x78` | **`+0x20`** |
| `__TEXT.__cstring` | `0x427c` | `0x428c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1230` | `0x1238` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   3457
-  CStrings:  807
+  Symbols:   3458
+  CStrings:  809
Symbols:
+ _MGGetProductType
Functions:
~ sub_2416dad68 -> sub_24202ed68 : 124 -> 144
~ -[TPSTipsManager welcomeCollectionFromContentPackage:] : 620 -> 732
~ +[TPSPairedDeviceValidation airPodsDeviceInfo] : 736 -> 832
~ -[TPSPairedDeviceValidation _validationForDeviceNumber:] : 552 -> 584
~ sub_241718d68 -> sub_24206ce6c : 360 -> 364
~ sub_24171906c -> sub_24206d174 : 340 -> 344
~ sub_24171951c -> sub_24206d628 : 352 -> 356
~ sub_24171b444 -> sub_24206f554 : 264 -> 272
~ sub_241720f48 -> sub_242075060 : 852 -> 856
~ sub_2417224f0 -> sub_24207660c : 340 -> 344
~ sub_241723f40 -> sub_242078060 : 576 -> 580
~ sub_24172e3e8 -> sub_24208250c : 2964 -> 2968
~ sub_241740390 -> sub_2420944b8 : 680 -> 684
~ sub_241740638 -> sub_242094764 : 680 -> 684
~ sub_241740a8c -> sub_242094bbc : 364 -> 368
~ sub_241746468 -> sub_24209a59c : 1780 -> 1752
~ sub_2417476d4 -> sub_24209b7ec : 692 -> 684
~ sub_24174803c -> sub_24209c14c : 1052 -> 1032
~ sub_24174c354 -> sub_2420a0450 : 852 -> 856
~ sub_2417628a0 -> sub_2420b69a0 : 1320 -> 1328
~ sub_241764444 -> sub_2420b854c : 76 -> 80
~ sub_241764490 -> sub_2420b859c : 228 -> 232
~ sub_241764574 -> sub_2420b8684 : 228 -> 232
~ sub_24176fd5c -> sub_2420c3e70 : 180 -> 184
~ sub_24176fed0 -> sub_2420c3fe8 : 1340 -> 1352
~ sub_241773b2c -> sub_2420c7c50 : 712 -> 716
~ sub_241773df4 -> sub_2420c7f1c : 416 -> 420
~ sub_241773f94 -> sub_2420c80c0 : 408 -> 412
~ sub_24177412c -> sub_2420c825c : 388 -> 392
~ sub_2417742b0 -> sub_2420c83e4 : 412 -> 416
~ sub_241777b8c -> sub_2420cbcc4 : 772 -> 776
~ -[TPSSystemVersionUpdateValidation validateWithCompletion:].cold.1 : 80 -> 88
~ -[TPSSystemVersionUpdateValidation validateLastMajorSystemVersionUpdateSinceTimeInterval:desiredOrder:].cold.1 : 80 -> 88
~ -[TPSSystemVersionUpdateValidation validateLastMajorSystemVersionUpdateSinceTimeInterval:desiredOrder:].cold.2 : 68 -> 64
CStrings:
+ "27"
+ "Hardware"
```
