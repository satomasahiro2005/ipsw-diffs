## com.apple.AGXG17P

> `com.apple.AGXG17P`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xd6d4c` | `0xd70c8` | **`+0x37c`** |
| `__TEXT.__cstring` | `0xfb11` | `0xfb13` | **`+0x2`** |

### Other Changes

```diff

-362.2.0.0.0
+362.3.1.0.0
Functions:
~ __ZN14AGXAccelerator16restartWorkQueueEP12AGXWorkQueue : 11592 -> 12004
~ __ZN14AGXAccelerator15configureDeviceEP9IOService : 10284 -> 10332
~ __ZN14AGXAccelerator5startEP9IOService : 22384 -> 22400
~ __ZN10AGXChannel23allocateSpillBufferDataEP20AGXCommandDescriptorP12AGXSpillDescbP24AGXSpillBufferAllocError : 6324 -> 6576
~ sub_fffffff0084b1c64 -> sub_fffffff0084a5f3c : 136 -> 148
~ sub_fffffff0084b1cec -> sub_fffffff0084a5fd0 : 68 -> 80
~ sub_fffffff0084b6174 -> sub_fffffff0084aa464 : 3144 -> 3168
~ __ZN20AGXFamilyAccelerator5probeEP9IOServicePi : 2704 -> 2764
~ sub_fffffff0084bb0a0 -> sub_fffffff0084af3e4 : 592 -> 596
~ sub_fffffff0084e10fc -> sub_fffffff0084d5444 : 532 -> 540
~ __ZN14AGXArmFirmware27initPowerAndPerformanceDataEv : 9868 -> 9872
~ __ZN14AGXArmFirmware11setupConfigEv : 8904 -> 8920
~ sub_fffffff008503014 -> sub_fffffff0084f7378 : 152 -> 160
~ sub_fffffff0085030ac -> sub_fffffff0084f7418 : 132 -> 140
~ sub_fffffff008503130 -> sub_fffffff0084f74a4 : 808 -> 800
~ __ZN17AGXUSCPrivMemPool13prepareLockedEP20AGXCommandDescriptor24AGXIOFenceDataMasterTypeiP13AGXUMADataRecyP10IOGPUEventPyPi : 2708 -> 2704
~ sub_fffffff008543408 -> sub_fffffff008537770 : 1064 -> 1056
~ sub_fffffff008543d60 -> sub_fffffff0085380c0 : 376 -> 372
~ sub_fffffff008544480 -> sub_fffffff0085387dc : 896 -> 928
CStrings:
+ "12111111212112222222222111122211122222111112111222222111122212222122222221"
+ "Sep 27 2026 20:44:15"
- "121111112121122222222221111222111222221111121112222111122212222122222221"
- "Sep 13 2026 21:52:02"
```
