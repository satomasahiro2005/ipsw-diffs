## AppleMSG

> `/System/Library/PrivateFrameworks/AppleMSG.framework/AppleMSG`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x142e0` | `0x142f0` | **`+0x10`** |

### Other Changes

```diff

-418.0.0.0.1
+420.0.0.0.0
Symbols:
+ __ZNKSt3__114default_deleteI34msg_local_timing_info_subscriptionEclB9fqe220106EPS1_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt16invalid_argumentC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJRFvvEEEEEEvPv
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
- __ZNKSt3__114default_deleteI34msg_local_timing_info_subscriptionEclB9fqe220100EPS1_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt16invalid_argumentC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__117__call_once_proxyB9fqe220100INS_5tupleIJRFvvEEEEEEvPv
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
Functions:
~ _MSGGetFutureSyncTiming : 584 -> 600
~ _MSGLookupSyncNamesBatch : 972 -> 984
~ _MSGGetEventTriggerTimings : 556 -> 568
~ _MSGLookupEventTriggerNamesBatch : 972 -> 984
~ _MSGGetDevices : 488 -> 496
~ __ZN8AppleMSG24getSyncConfigDescriptionEPNS_13sync_config_tE : 668 -> 660
~ __ZN8AppleMSG26getEventTriggerDescriptionEjPNS_19event_trigger_cfg_tE : 324 -> 320
~ __ZN13MSGControllerD2Ev : 212 -> 216
~ __ZN13MSGControllerC2EOS_ : 400 -> 440
~ __ZN13MSGController17extractDeviceInfoEjR20applemsg_device_info : 248 -> 244
~ __ZN13MSGController21getCurrentMasterFrameERyS0_S0_ : 264 -> 288
~ __ZN13MSGController13getMSGDevicesEP20applemsg_device_infojPj : 584 -> 580
~ __ZN13MSGController21registerForTimingInfoEjyRhb : 796 -> 760
~ __ZN13MSGController23unregisterForTimingInfoEh : 212 -> 216
~ __ZN13MSGController27registerForEventTriggerInfoEjRh : 540 -> 516
~ __ZN13MSGController27dumpMostRecentEventTriggersEhRmPN8AppleMSG24msg_event_trigger_timingE : 404 -> 408
~ __ZN13MSGController29registerForVirtualFrameIDInfoEjRh : 608 -> 580
~ __ZN13MSGController27getNextNFramesWithVirtualIDEhhyPyRyhS0_ : 320 -> 316
~ _OUTLINED_FUNCTION_25 : 16 -> 20
~ _OUTLINED_FUNCTION_26 : 32 -> 16
~ _OUTLINED_FUNCTION_27 : 16 -> 32
~ _OUTLINED_FUNCTION_28 : 12 -> 16
~ __ZN23MSGExternalSyncTargeter31getTargetAlignmentFromRawTimingEPKN8AppleMSG24msg_event_trigger_timingEmRNS0_15gtb_full_time_tERNS0_10gtb_time_tERl : 1664 -> 1660
~ __ZN13MSGControllerC2Ebb.cold.1 : 136 -> 124
```
