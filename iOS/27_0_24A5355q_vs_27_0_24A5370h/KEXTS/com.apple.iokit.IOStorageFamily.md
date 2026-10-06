## com.apple.iokit.IOStorageFamily

> `com.apple.iokit.IOStorageFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x860` | **`+0x860`** |
| `__TEXT_EXEC.__text` | `0x1b81c` | `0x1babc` | **`+0x2a0`** |

### Other Changes

```text
Functions:
~ __ZN24IOUserBlockStorageDevice13willTerminateEP9IOServicej_0 : 320 -> 336
~ __ZN24IOUserBlockStorageDevice16doAsyncReadWriteEP18IOMemoryDescriptoryyP19IOStorageAttributesP19IOStorageCompletion_0 : 600 -> 588
~ sub_fffffff00a261c48 -> sub_fffffff00a2ee02c : 56 -> 52
~ __ZN24IOUserBlockStorageDevice13doSynchronizeEyyj : 372 -> 368
~ __ZN24IOUserBlockStorageDevice13Complete_ImplEji : 356 -> 348
~ sub_fffffff00a261fc0 -> sub_fffffff00a2ee394 : 56 -> 52
~ __ZN24IOUserBlockStorageDevice7doUnmapEP26IOBlockStorageDeviceExtentjj : 280 -> 276
~ __ZN24IOUserBlockStorageDevice12doEjectMediaEv : 652 -> 672
~ __ZN24IOUserBlockStorageDevice15getVendorStringEv : 448 -> 440
~ __ZN20IOBlockStorageDriver18systemWillShutdownEj : 1280 -> 1292
~ sub_fffffff00a265658 -> sub_fffffff00a2f1a3c : 412 -> 416
~ sub_fffffff00a265b8c -> sub_fffffff00a2f1f74 : 304 -> 288
~ sub_fffffff00a265cbc -> sub_fffffff00a2f2094 : 72 -> 68
~ sub_fffffff00a265d04 -> sub_fffffff00a2f20d8 : 72 -> 68
~ sub_fffffff00a265d4c -> sub_fffffff00a2f211c : 116 -> 132
~ __ZN20IOBlockStorageDriver20mediaStateHasChangedEj : 2316 -> 2312
~ sub_fffffff00a268c28 -> sub_fffffff00a2f5004 : 272 -> 292
~ sub_fffffff00a268d38 -> sub_fffffff00a2f5128 : 292 -> 316
~ sub_fffffff00a268f14 -> sub_fffffff00a2f531c : 200 -> 220
~ sub_fffffff00a2697b4 -> sub_fffffff00a2f5bd0 : 160 -> 164
~ sub_fffffff00a269950 -> sub_fffffff00a2f5d70 : 156 -> 160
~ sub_fffffff00a2699ec -> sub_fffffff00a2f5e10 : 152 -> 180
~ sub_fffffff00a269a84 -> sub_fffffff00a2f5ec4 : 1272 -> 1640
~ sub_fffffff00a26afe8 -> sub_fffffff00a2f7598 : 640 -> 608
~ sub_fffffff00a26c3ac -> sub_fffffff00a2f893c : 1104 -> 1112
~ sub_fffffff00a26e3f0 -> sub_fffffff00a2fa988 : 1624 -> 1672
~ __ZN7IOMedia10handleOpenEP9IOServicejPv : 1076 -> 1072
~ sub_fffffff00a26fd2c -> sub_fffffff00a2fc2f0 : 1240 -> 1236
~ sub_fffffff00a270db8 -> sub_fffffff00a2fd378 : 332 -> 356
~ sub_fffffff00a270f04 -> sub_fffffff00a2fd4dc : 344 -> 360
~ sub_fffffff00a2712a8 -> sub_fffffff00a2fd890 : 316 -> 340
~ __ZN11AnchorTable6locateEP9IOServicePv : 1212 -> 1216
~ sub_fffffff00a2723d0 -> sub_fffffff00a2fe9d4 : 776 -> 780
~ __ZN15OSMetaClassBase12safeMetaCastEPKS_PK11OSMetaClass : 120 -> 124
~ sub_fffffff00a272a70 -> sub_fffffff00a2ff07c : 244 -> 248
~ sub_fffffff00a272b64 -> sub_fffffff00a2ff174 : 92 -> 96
~ sub_fffffff00a272bc0 -> sub_fffffff00a2ff1d4 : 64 -> 68
~ sub_fffffff00a272c2c -> sub_fffffff00a2ff244 : 364 -> 368
~ __ZL11dkreadwritePv9dkrtype_t : 760 -> 776
~ sub_fffffff00a27335c -> sub_fffffff00a2ff988 : 92 -> 104
~ sub_fffffff00a2733b8 -> sub_fffffff00a2ff9f0 : 160 -> 192
~ sub_fffffff00a273458 -> sub_fffffff00a2ffab0 : 580 -> 588
~ __ZN10MinorTable6insertEP7IOMediajP16IOMediaBSDClientPc_0 : 1352 -> 1336
~ sub_fffffff00a2742cc -> sub_fffffff00a30091c : 68 -> 72
~ __ZL11dkreadwritePv9dkrtype_t_0 : 1680 -> 1688
~ __ZL21dkreadwritecompletionPvS_iy : 7436 -> 7448
~ sub_fffffff00a2767e0 -> sub_fffffff00a302e48 : 108 -> 112
~ sub_fffffff00a27684c -> sub_fffffff00a302eb8 : 1284 -> 1280
~ sub_fffffff00a276d50 -> sub_fffffff00a3033b8 : 88 -> 92
~ sub_fffffff00a276db8 -> sub_fffffff00a303424 : 144 -> 128
~ sub_fffffff00a276e48 -> sub_fffffff00a3034a4 : 256 -> 272
~ sub_fffffff00a276f78 -> sub_fffffff00a3035e4 : 80 -> 92
~ sub_fffffff00a276fc8 -> sub_fffffff00a303640 : 100 -> 104
~ __ZL21dkreadwritecompletionPvS_iy_0 : 536 -> 540
```
