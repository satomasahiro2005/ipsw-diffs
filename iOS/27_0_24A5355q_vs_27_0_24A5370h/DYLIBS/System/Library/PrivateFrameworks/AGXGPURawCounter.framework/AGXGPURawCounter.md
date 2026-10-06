## AGXGPURawCounter

> `/System/Library/PrivateFrameworks/AGXGPURawCounter.framework/AGXGPURawCounter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf670` | `0xf644` | **`-0x2c`** |
| `__TEXT.__gcc_except_tab` | `0x598` | `0x594` | **`-0x4`** |

### Other Changes

```diff

-360.27.0.0.0
+360.27.3.1.0
Symbols:
+ __ZNSt3__127__throw_bad_optional_accessB9fqn220106Ev
- __ZNSt3__127__throw_bad_optional_accessB9fqn220100Ev
Functions:
~ __ZN20AGXGPURawCounterImpl10SourceImplC2EPS_jPKNS_10SourceInfoEPKjjPKNS_17ChipDispatchTableE : 996 -> 980
~ __ZNK20AGXGPURawCounterImpl10SourceImpl24copyAvailableCounterListEPPN16AGXGPURawCounter11CounterDescE : 180 -> 184
~ __ZN20AGXGPURawCounterImpl10SourceImpl10addCounterERN16AGXGPURawCounter14CounterReqDescE : 3676 -> 3692
~ __ZN20AGXGPURawCounterImpl10SourceImpl15postProcessDataEjPKhyPyyPhyyS3_b : 4616 -> 4548
~ __ZN20AGXGPURawCounterImpl10SourceImpl28generateKickTimestampSamplesEjyyPKhjPNS0_13KickslotStateEPj : 1604 -> 1584
~ __ZN20AGXGPURawCounterImpl10SourceImpl24emitKickTimestampSamplesEjPNS0_13KickslotStateEjyPvy : 1176 -> 1172
~ __ZL19copyMetaCounterListP14StackAllocatorPKN16AGXGPURawCounter12SampleHeaderEPKN20AGXGPURawCounterImpl13CounterSelectEj : 536 -> 548
~ __ZN20AGXGPURawCounterImpl10SourceImpl16postProcessResetEj : 804 -> 852
~ __ZN20AGXGPURawCounterImpl10SourceImpl14ringBufferInitEyPvj : 216 -> 212
~ __ZN20AGXGPURawCounterImpl10SourceImpl14ringBufferFreeEv : 140 -> 132
~ __ZN20AGXGPURawCounterImpl4freeEv : 420 -> 416
~ __ZZN20AGXGPURawCounterImpl4initEjENK3$_6clEv : 1868 -> 1876
~ __ZNK20AGXGPURawCounterImpl26chipDispatchTableForSourceEjjjPKc : 1604 -> 1616
~ __ZN20AGXGPURawCounterImpl10sourceListEPPN16AGXGPURawCounter6SourceEj : 536 -> 528
~ __ZN20AGXGPURawCounterImpl13startSamplingEv : 2344 -> 2336
~ __ZN20AGXGPURawCounterImpl12stopSamplingEv : 712 -> 700
~ __ZNK20AGXGPURawCounterImpl13SourceAPSImpl21getEventSelectsNumMaxEPKc : 196 -> 192
~ __ZN20AGXGPURawCounterImpl13SourceAPSImpl21setOptionsPerUSCMasksEP12NSDictionary : 1136 -> 1132
~ __ZN20AGXGPURawCounterImpl13SourceAPSImpl20fillKernelConfigDataEP28AGXSPerfCtrSamplerControlRec : 388 -> 380
~ ____ZN20AGXGPURawCounterImpl13SourceAPSImpl20fillKernelConfigDataEP28AGXSPerfCtrSamplerControlRec_block_invoke : 348 -> 380
~ __ZN20AGXGPURawCounterImpl13SourceAPSImpl14ringBufferInitEyPvj : 300 -> 296
~ __ZN11AGXGRC_G14XL26ParseSampleHeaderInheritedEPKyP17AGXSPerfCtrSamplePy : 320 -> 316
```
