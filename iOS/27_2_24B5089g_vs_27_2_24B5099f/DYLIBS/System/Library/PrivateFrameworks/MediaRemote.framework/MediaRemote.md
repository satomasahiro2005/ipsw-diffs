## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x317ca8` | `0x318190` | **`+0x4e8`** |
| `__AUTH_CONST.__cfstring` | `0x24a40` | `0x24b40` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x47fa8` | `0x48050` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x2de57` | `0x2deda` | **`+0x83`** |
| `__TEXT.__gcc_except_tab` | `0x6364` | `0x63b4` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xbb98` | `0xbbe0` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x2c890` | `0x2c8c8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x3460` | `0x3480` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xf9b0` | `0xf9d0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x528` | `0x540` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x33f0` | `0x33fc` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0xbe28` | `0xbe20` | **`-0x8`** |

### Other Changes

```diff

-4026.200.15.0.0
+4026.200.23.0.0

-  Functions: 21040
-  Symbols:   30278
-  CStrings:  6776
+  Functions: 21045
+  Symbols:   30285
+  CStrings:  6784
Symbols:
+ -[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]
+ -[MRGroupComposition setSpeakerGroupCount:]
+ -[MRGroupComposition setTvAndSpeakerCount:]
+ -[MRGroupComposition speakerGroupCount]
+ -[MRGroupComposition tvAndSpeakerCount]
+ -[_MRCommandOptionsProtobuf hasRequestDetails]
+ -[_MRCommandOptionsProtobuf requestDetails]
+ -[_MRCommandOptionsProtobuf setRequestDetails:]
+ OBJC_IVAR_$__MRCommandOptionsProtobuf._requestDetails
+ _OBJC_IVAR_$_MRGroupComposition._speakerGroupCount
+ _OBJC_IVAR_$_MRGroupComposition._tvAndSpeakerCount
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_2
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_3
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_4
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_5
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_6
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_7
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_8
+ ___75-[MRActiveRoutesObserver _handleActiveSystemEndpointDidRemoveOutputDevice:]_block_invoke_4
+ ___block_descriptor_176_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8r160l8r168l8
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleEndpointsForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleOutputDevicesForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]
- -[MRAVRoutingDiscoverySessionWrapper _shouldNotify]
- ___50-[MRRapportTransportConnection _registerCallbacks]_block_invoke_3
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_2
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_3
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_4
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_5
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_6
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_7
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_8
- ___block_descriptor_160_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24lr32l8r40l8r48l8r56l8r64l8r72l8r80l8r88l8r96l8r104l8r112l8r120l8r128l8r136l8r144l8r152l8
CStrings:
+ "GracePeriod"
+ "OA"
+ "SpeakerGroup"
+ "TVAndSpeaker"
+ "hifispeaker.2"
+ "requestDetails"
+ "speakerGroup: %lu;"
+ "tv.and.hifispeaker.fill"
+ "tvAndSpeaker: %lu;"
- "O"
```
