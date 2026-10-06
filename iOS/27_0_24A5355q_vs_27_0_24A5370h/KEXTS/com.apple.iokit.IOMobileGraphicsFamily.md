## com.apple.iokit.IOMobileGraphicsFamily

> `com.apple.iokit.IOMobileGraphicsFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0xb50` | **`+0xb50`** |
| `__TEXT_EXEC.__text` | `0x21b60` | `0x21e44` | **`+0x2e4`** |
| `__TEXT.__cstring` | `0x9122` | `0x9158` | **`+0x36`** |
| `__DATA_CONST.__const` | `0x6e48` | `0x6e58` | **`+0x10`** |

### Other Changes

```diff

-700.50.66.0.0
+700.50.72.0.0

-  CStrings:  1092
+  CStrings:  1094
Functions:
~ sub_fffffff00a0e0b50 -> sub_fffffff00a165500 : 832 -> 824
~ sub_fffffff00a0e0e90 -> sub_fffffff00a165838 : 340 -> 328
~ sub_fffffff00a0e2700 -> sub_fffffff00a16709c : 172 -> 180
~ sub_fffffff00a0e27ac -> sub_fffffff00a167150 : 172 -> 180
~ sub_fffffff00a0e2ad0 -> sub_fffffff00a16747c : 68 -> 76
~ sub_fffffff00a0e37fc -> sub_fffffff00a1681b0 : 268 -> 292
~ __ZN29IOMobileFramebufferUserClient24detectSetBlockClientTypeEP4taskPj : 316 -> 308
~ __ZN29IOMobileFramebufferUserClient21initIOSharedDataQueueEP4task : 272 -> 308
~ __ZN29IOMobileFramebufferUserClient5startEP9IOService : 392 -> 408
~ __ZN29IOMobileFramebufferUserClient21isSetBlockEnumAllowedEP4taskj15IOMFBClientTypej : 240 -> 272
~ __ZN29IOMobileFramebufferUserClient10set_notifyEPvS0_22IOMFB_NotificationTypej : 360 -> 384
~ sub_fffffff00a0e9280 -> sub_fffffff00a16dcb0 : 1264 -> 1268
~ __ZN5IOMFB40getIdleDetectorRTPTypeForIdleDetectorRTPENS_15RuntimePropertyE : 40 -> 44
~ __ZN5IOMFB21get_RTP_boot_arg_nameENS_15RuntimePropertyE : 5372 -> 5388
~ sub_fffffff00a0eae68 -> sub_fffffff00a16f8b0 : 1264 -> 1268
~ sub_fffffff00a0ee1c4 -> sub_fffffff00a172c10 : 76 -> 84
~ sub_fffffff00a0ee210 -> sub_fffffff00a172c64 : 80 -> 88
~ sub_fffffff00a0ee260 -> sub_fffffff00a172cbc : 124 -> 128
~ sub_fffffff00a0ee2dc -> sub_fffffff00a172d3c : 356 -> 360
~ sub_fffffff00a0ee4c0 -> sub_fffffff00a172f24 : 520 -> 524
~ __ZN24UPAsynchronousScheduler_19createArgumentEntryEv : 160 -> 172
~ __ZN24UPAsynchronousScheduler_20releaseArgumentEntryEPNS_13ArgumentEntryEb : 196 -> 208
~ __ZN23UPAsynchronousScheduler11abortThreadEj : 364 -> 376
~ __ZN23UPAsynchronousScheduler20performActions_gatedEv : 588 -> 608
~ sub_fffffff00a0efdd0 -> sub_fffffff00a174870 : 120 -> 136
~ sub_fffffff00a0efe48 -> sub_fffffff00a1748f8 : 120 -> 124
~ sub_fffffff00a0efec0 -> sub_fffffff00a174974 : 84 -> 80
~ __ZN25IOMobileFramebufferLegacy21io_fence_notify_gatedEP18IOMFBSwapIORequestP9IOSurfacei : 352 -> 336
~ __ZN25IOMobileFramebufferLegacy5startEP9IOService : 2332 -> 2372
~ sub_fffffff00a0f163c -> sub_fffffff00a176104 : 1092 -> 1112
~ sub_fffffff00a0f1f8c -> sub_fffffff00a176a68 : 708 -> 720
~ sub_fffffff00a0f2250 -> sub_fffffff00a176d38 : 528 -> 576
~ __ZN25IOMobileFramebufferLegacy19swap_complete_gatedEb : 1256 -> 1252
~ sub_fffffff00a0f4408 -> sub_fffffff00a178f1c : 1140 -> 1164
~ sub_fffffff00a0f4be8 -> sub_fffffff00a179714 : 376 -> 368
~ sub_fffffff00a0f52f8 -> sub_fffffff00a179e1c : 412 -> 396
~ __ZN25IOMobileFramebufferLegacy10swap_queueEP18IOMFBSwapIORequest : 1524 -> 1580
~ __ZN25IOMobileFramebufferLegacy17allocate_carveoutEP9IOSurfacejj : 960 -> 976
~ sub_fffffff00a0f8900 -> sub_fffffff00a17d45c : 84 -> 92
~ __ZN25IOMobileFramebufferLegacy40updateDisplayedDataFromPendingSwap_gatedEv : 864 -> 1096
~ sub_fffffff00a0f95a8 -> sub_fffffff00a17e1f4 : 444 -> 452
~ sub_fffffff00a0f97b8 -> sub_fffffff00a17e40c : 328 -> 340
~ __ZN25IOMobileFramebufferLegacy18writeSwapDebugInfoEP7OSArrayP18IOMFBSwapIORequest : 496 -> 512
~ __ZN25IOMobileFramebufferLegacy20writeDebugInfo_gatedEP12OSDictionary : 1284 -> 1296
~ __ZN25IOMobileFramebufferLegacy27write_last_swap_infos_gatedEP12OSDictionary : 1072 -> 1096
~ sub_fffffff00a0fcd50 -> sub_fffffff00a1819e4 : 256 -> 264
~ __ZN25IOMobileFramebufferLegacy17print_gamma_tableEPK15IOMFBGammaTable : 240 -> 232
~ __ZNK25IOMobileFramebufferLegacy29getCurrentActiveRegions_gatedEjPPK9IOMFBRectPj : 180 -> 188
~ __ZN5IOMFB3DCP15SurfaceContents4fromEPK9IOSurface : 1292 -> 1280
~ sub_fffffff00a0ffa78 -> sub_fffffff00a184708 : 120 -> 124
CStrings:
+ "ccMinNitsConfig"
+ "iomfb_RuntimeProperty_ccMinNitsConfig"
```
