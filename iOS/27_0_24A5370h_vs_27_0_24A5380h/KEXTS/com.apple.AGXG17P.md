## com.apple.AGXG17P

> `com.apple.AGXG17P`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xd4980` | `0xd4ff8` | **`+0x678`** |
| `__TEXT.__cstring` | `0xf9cc` | `0xfae0` | **`+0x114`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1aa0` | `0x1a90` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xd50` | `0xd48` | **`-0x8`** |

### Other Changes

```diff

-360.27.3.1.0
+360.31.1.0.0

-  CStrings:  2025
+  CStrings:  2029
Functions:
~ __ZN14AGXAccelerator5startEP9IOService : 22384 -> 22380
~ __ZN14AGXAccelerator27setCommandSubmissionEnabledEb : 672 -> 704
~ sub_fffffff008441870 -> sub_fffffff00843988c : 204 -> 368
~ sub_fffffff00845224c -> __ZN16AGXCommandBuffer18updateBarrierEventEjP10IOGPUEventS1_y : 400 -> 448
~ sub_fffffff0084523dc -> __ZN16AGXCommandBuffer24mergeSubmitEventForStageEjPK10IOGPUEventS2_y : 328 -> 376
~ sub_fffffff00845c1f0 -> sub_fffffff008454310 : 1776 -> 1676
~ sub_fffffff0084675b8 -> sub_fffffff00845f674 : 416 -> 404
~ sub_fffffff0084716ac -> sub_fffffff00846975c : 1976 -> 1984
~ sub_fffffff008472298 -> sub_fffffff00846a350 : 5204 -> 5136
~ __ZN11AGXFirmware11setupConfigEv : 3380 -> 3364
~ sub_fffffff008481680 -> sub_fffffff0084796e4 : 356 -> 364
~ sub_fffffff00848183c -> sub_fffffff0084798a8 : 16 -> 20
~ sub_fffffff00848184c -> sub_fffffff0084798bc : 220 -> 224
~ __ZN14AGXArmFirmware24updateMRCConfigOverridesEP12OSDictionary21AGFAControlDomainType : 1852 -> 1820
~ sub_fffffff008483dc4 -> sub_fffffff00847be18 : 24 -> 20
~ sub_fffffff008483ddc -> sub_fffffff00847be2c : 24 -> 20
~ sub_fffffff008483df4 -> sub_fffffff00847be40 : 24 -> 20
~ sub_fffffff008483e0c -> sub_fffffff00847be54 : 24 -> 20
~ sub_fffffff008483e24 -> sub_fffffff00847be68 : 24 -> 20
~ sub_fffffff008483e3c -> sub_fffffff00847be7c : 24 -> 20
~ sub_fffffff008484658 -> sub_fffffff00847c694 : 152 -> 148
~ sub_fffffff0084846f0 -> sub_fffffff00847c728 : 152 -> 148
~ sub_fffffff008493cc4 -> sub_fffffff00848bcf8 : 532 -> 528
~ __ZN14AGXArmFirmware12kickFirmwareEj15AGFAMessageTypeb : 292 -> 316
~ __ZN14AGXArmFirmware15submitCLChannelEP10AGXChannelRK22_AGXChannelSubmitInfo_jjb : 540 -> 544
~ __ZN14AGXArmFirmware15submit3DChannelEP10AGXChannelRK22_AGXChannelSubmitInfo_jjbb : 568 -> 572
~ __ZN14AGXArmFirmware15submitTAChannelEP10AGXChannelRK22_AGXChannelSubmitInfo_jjb : 536 -> 540
~ sub_fffffff008495434 -> sub_fffffff00848d488 : 576 -> 592
~ __ZN14AGXArmFirmware27initPowerAndPerformanceDataEv : 9592 -> 9588
~ __ZN14AGXArmFirmware11setupConfigEv : 9056 -> 8948
~ sub_fffffff00849d198 -> sub_fffffff00849518c : 904 -> 860
~ sub_fffffff0084a8c58 -> sub_fffffff0084a0c20 : 7832 -> 8124
~ sub_fffffff0084aaaf0 -> sub_fffffff0084a2bdc : 108 -> 112
~ sub_fffffff0084aab5c -> sub_fffffff0084a2c4c : 324 -> 316
~ sub_fffffff0084aacf0 -> sub_fffffff0084a2dd8 : 9692 -> 10028
~ sub_fffffff0084ad2cc -> sub_fffffff0084a5504 : 2684 -> 2772
~ sub_fffffff0084add48 -> sub_fffffff0084a5fd8 : 7500 -> 7788
~ sub_fffffff0084afa94 -> sub_fffffff0084a7e44 : 5116 -> 5288
~ __ZN22AGXParameterManagement15growImmediatelyEv : 860 -> 828
~ sub_fffffff0084d3df8 -> sub_fffffff0084cc234 : 3620 -> 3628
~ sub_fffffff0084db3d4 -> sub_fffffff0084d3818 : 1288 -> 1276
~ __ZN13AGXKTelemetry4initEP14AGXAcceleratorP10IOWorkLoop : 536 -> 540
~ __ZN13AGXKTelemetry15periodicCollectEP18IOTimerEventSource : 1268 -> 1832
~ sub_fffffff0084f26d8 -> sub_fffffff0084ead48 : 316 -> 324
CStrings:
+ "121111122"
+ "3.44.10"
+ "AGXk: %s:%d:%s: !!! Out-of-range command_stage_mask 0x%x\n"
+ "Jun 30 2026 21:11:44"
+ "com.apple.agx.thmcounters"
+ "sfe_tier3"
+ "thm_activations"
+ "void AGXCommandBuffer::mergeSubmitEventForStage(uint32_t, const sIOGPUEvent *, const sIOGPUEvent *, uint64_t)"
+ "void AGXCommandBuffer::updateBarrierEvent(uint32_t, sIOGPUEvent *, sIOGPUEvent *, uint64_t)"
- "1211111"
- "3.44.9"
- "Jun 18 2026 20:26:32"
- "cltmlimit_qp"
- "gpu-cltm-limit-mrc-period"
```
