## DriverKit

> `/System/Library/Frameworks/DriverKit.framework/DriverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37c40` | `0x37cbc` | **`+0x7c`** |

### Other Changes

```diff

-508.0.0.0.0
+509.0.0.0.0
Functions:
~ __Z21OSUnserializeXMLparsePv : 3908 -> 3864
~ _IOLogBuffer : 320 -> 308
~ __ZL27PE_parse_boot_argn_internalPKcPvib : 1144 -> 1196
~ _OSReportWithBacktrace : 352 -> 348
~ __ZL6getTagP12parser_statePcPiPA32_cS4_ : 1084 -> 1076
~ __ZL16getCFEncodedDataP12parser_statePj : 540 -> 536
~ __ZN12CompactArrayIP15IODispatchQueueE5resetEv : 192 -> 184
~ __ZN15OSMetaClassBase8DispatchE5IORPC : 504 -> 500
~ __ZN15OSMetaClassBase6InvokeE5IORPC : 1540 -> 1548
~ __ZL15OSCopyInObjectsP18IOUserServer_IVarsP16IORPCMessageMachP12IORPCMessageb : 568 -> 552
~ _IOUserServerMain : 1512 -> 1524
~ __ZN15IODispatchQueue6CreateEPKcyyPPS_ : 420 -> 436
~ __ZN15IODispatchQueue4freeEv : 248 -> 268
~ __ZL21_IODispatchQueueSleepP26IODispatchQueue_LocalIVarsyPv8timespecb : 444 -> 452
~ __ZN15IODispatchQueue17WakeupWithOptionsEPvy : 180 -> 196
~ __ZN21IOTimerDispatchSource4freeEv : 320 -> 340
~ ____ZN21IOTimerDispatchSource11Cancel_ImplEU13block_pointerFvvE_block_invoke : 544 -> 568
~ __ZN8OSBundle10mainBundleEv : 344 -> 348
~ __ZL16OSConsumeObjectsP16IORPCMessageMachb : 96 -> 108
~ __ZL15_OSObjectCopyInP18IOUserServer_IVarsybPP8OSObject : 1064 -> 1080
~ _OSCreateObjectFromSerialization : 2208 -> 2196
~ __ZL12OSStringHashPKcm : 80 -> 84
~ __ZL25OSDictionaryInternalApplyP12OSDictionaryU13block_pointerFbmP15OSSerialization17OSCollectionEntryS3_E : 260 -> 252
~ __ZL20OSArrayInternalApplyP7OSArrayjU13block_pointerFbmP15OSSerialization17OSCollectionEntryE : 256 -> 252
~ __ZL23OSArraySetValueInternalP7OSArraymP8OSObjectb : 460 -> 476
~ __ZN12OSDictionary15flushCollectionEv : 256 -> 240
~ __ZN7OSArray15flushCollectionEv : 192 -> 188
~ __ZN7OSArray11withObjectsEPPK8OSObjectjj : 148 -> 164
~ __ZN5OSSet11withObjectsEPPK8OSObjectjj : 140 -> 156
~ __ZN16IOReporter_IVars21handleConfigureReportEP19IOReportChannelListjRj : 292 -> 288
~ __ZN16IOReporter_IVars18handleUpdateReportEP19IOReportChannelListjRjRPhRm : 292 -> 288
~ __ZN16IOReporter_IVars17getChannelIndicesEyPiS0_ : 136 -> 128
~ __ZN25IOHistogramReporter_IVarsC2EP9IOService19IOReportChannelTypeyPK8OSStringtyiP24IOHistogramSegmentConfig : 896 -> 904
~ __ZN19IOHistogramReporter10tallyValueEx : 316 -> 312
~ __ZN18IOMemoryDescriptor27CreateWithMemoryDescriptorsEyjPPS_S1_ : 416 -> 432
~ __ZN18IOMemoryDescriptor34CreateWithMemoryDescriptors_InvokeE5IORPCPFiyjPPS_S2_E : 284 -> 288
```
