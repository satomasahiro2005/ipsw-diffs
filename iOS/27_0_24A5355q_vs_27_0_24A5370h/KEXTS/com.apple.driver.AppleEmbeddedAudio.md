## com.apple.driver.AppleEmbeddedAudio

> `com.apple.driver.AppleEmbeddedAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xa10` | **`+0xa10`** |
| `__TEXT_EXEC.__text` | `0x35248` | `0x352ac` | **`+0x64`** |

### Other Changes

```diff

-1000.40.0.0.0
+1000.41.0.0.0
Functions:
~ __ZN28AppleSpeakerArrayCalibration24addCalibrationPropertiesEP9IOServiceS1_PjPP8OSString : 916 -> 912
~ __ZN13AppleI2CAudio13_writeRegBaseEjh : 476 -> 484
~ __ZN13AppleI2CAudio8_readRegEj : 596 -> 604
~ sub_fffffff008acff34 -> sub_fffffff008aea620 : 604 -> 612
~ __ZN13AppleI2CAudio13_readMultipleEjPhy : 560 -> 580
~ __ZN13AppleI2CAudio14_writeMultipleEjPKhy : 508 -> 516
~ __ZN13AppleI2CAudio18debugCopyRegistersEb : 928 -> 920
~ __ZN21AppleI2CMultipleAudio13_transferDataEjjyjyPh : 760 -> 768
~ __ZN18AppleI2CPagedAudio18debugCopyRegistersEb : 636 -> 648
~ __ZN27AppleI2CRangedMultipleAudio14_writeMultipleEjjPKhy : 488 -> 500
~ __ZN18AppleEmbeddedAudio5startEP9IOService : 5948 -> 6012
~ sub_fffffff008ad861c -> sub_fffffff008af2d84 : 600 -> 596
~ __ZNK18AppleEmbeddedAudio29getAcousticScaleForTransducerEjPx : 664 -> 668
~ __ZN17AppleCSSPIv2Audio15_writeDataBlockEjybPKhb : 2376 -> 2372
~ __ZN17AppleCSSPIv2Audio14_readDataBlockEyybPhb : 2580 -> 2548
~ sub_fffffff008aecb68 -> sub_fffffff008b072ac : 372 -> 368
~ sub_fffffff008aef348 -> sub_fffffff008b09a88 : 392 -> 396
~ __ZN24AppleEmbeddedAudioDevice34createControlDataSourceSelectorMapEPKjj : 1764 -> 1772
~ __ZN19AppleSecondaryAudio5startEP9IOService : 8788 -> 8780
~ sub_fffffff008af4b34 -> sub_fffffff008b0f278 : 588 -> 584
~ sub_fffffff008af548c -> sub_fffffff008b0fbcc : 208 -> 204
~ sub_fffffff008af743c -> sub_fffffff008b11b78 : 1204 -> 1188
~ sub_fffffff008af7e18 -> sub_fffffff008b12544 : 3192 -> 3168
~ __ZN19AppleSecondaryAudio28registerPrimaryFunctionGatedEP27AppleSecondaryAudioFunctionj : 936 -> 924
~ sub_fffffff008afa734 -> sub_fffffff008b14e3c : 428 -> 424
~ sub_fffffff008afa974 -> sub_fffffff008b15078 : 100 -> 108
~ sub_fffffff008afa9d8 -> sub_fffffff008b150e4 : 96 -> 104
~ sub_fffffff008afaa38 -> sub_fffffff008b1514c : 160 -> 168
~ sub_fffffff008afaad8 -> sub_fffffff008b151f4 : 404 -> 412
~ sub_fffffff008afac6c -> sub_fffffff008b15390 : 232 -> 240
~ sub_fffffff008afad54 -> sub_fffffff008b15480 : 148 -> 156
~ sub_fffffff008afade8 -> sub_fffffff008b1551c : 176 -> 184
~ sub_fffffff008b0033c -> sub_fffffff008b1aa78 : 288 -> 296
```
