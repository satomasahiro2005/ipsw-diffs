## SampleAnalysis

> `/System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10d424` | `0x1058ac` | **`-0x7b78`** |
| `__AUTH_CONST.__objc_const` | `0x112e8` | `0xfd50` | **`-0x1598`** |
| `__TEXT.__gcc_except_tab` | `0x213dc` | `0x20540` | **`-0xe9c`** |
| `__AUTH_CONST.__cfstring` | `0xda00` | `0xcee0` | **`-0xb20`** |
| `__TEXT.__objc_methlist` | `0x645c` | `0x5d8c` | **`-0x6d0`** |
| `__TEXT.__cstring` | `0x18ff6` | `0x18aa0` | **`-0x556`** |
| `__DATA_DIRTY.__objc_data` | `0x2990` | `0x2440` | **`-0x550`** |
| `__TEXT.__unwind_info` | `0x3f40` | `0x3c98` | **`-0x2a8`** |
| `__TEXT.__oslogstring` | `0xc26e` | `0xc3fc` | **`+0x18e`** |
| `__DATA_CONST.__const` | `0x3b60` | `0x3aa0` | **`-0xc0`** |
| `__DATA.__objc_ivar` | `0xe84` | `0xde0` | **`-0xa4`** |
| `__DATA_CONST.__objc_classlist` | `0x428` | `0x3a0` | **`-0x88`** |
| `__AUTH_CONST.__const` | `0xae0` | `0xa80` | **`-0x60`** |
| `__TEXT.__const` | `0x358` | `0x2f8` | **`-0x60`** |
| `__AUTH_CONST.__auth_got` | `0xbe8` | `0xbf0` | **`+0x8`** |
| `__DATA.__bss` | `0x48` | `0x40` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c10` | `0x2c08` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2c0` | `0x2b8` | **`-0x8`** |

### Other Changes

```diff

-434.0.0.0.0
+435.0.0.0.0

-  Functions: 2980
-  Symbols:   6087
-  CStrings:  3789
+  Functions: 2829
+  Symbols:   5728
+  CStrings:  3712
Symbols:
+ GCC_except_table169
+ GCC_except_table199
+ GCC_except_table266
+ GCC_except_table268
+ GCC_except_table308
+ GCC_except_table325
+ GCC_except_table326
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table370
+ GCC_except_table371
+ GCC_except_table378
+ GCC_except_table383
+ GCC_except_table384
+ GCC_except_table385
+ GCC_except_table386
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table562
+ GCC_except_table570
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table593
+ GCC_except_table594
+ GCC_except_table598
+ _objc_opt_new
- +[SABinaryLoadInfo binaryLoadInfoWithoutReferencesFromPAStyleSerializedImageInfo:]
- +[SAFanSpeed fanSpeedWithPAStyleSerializedFanSpeed:]
- +[SAFrame frameWithPAStyleSerializedFrame:]
- +[SAHIDEvent hidEventWithoutReferencesFromPAStyleSerializedHIDEvent:]
- +[SAHIDStep hidStepWithDebugId:pid:tid:]
- +[SAMountSnapshot mountSnapshotWithoutReferencesFromPAStyleMountSnapshot:]
- +[SAPAStyleFanSpeed classDictionaryKey]
- +[SAPAStyleFanSpeed newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleFrame classDictionaryKey]
- +[SAPAStyleFrame newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleHIDEvent classDictionaryKey]
- +[SAPAStyleHIDEvent newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleImageInfo classDictionaryKey]
- +[SAPAStyleImageInfo newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleMountSnapshot classDictionaryKey]
- +[SAPAStyleMountSnapshot newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleMountStatus classDictionaryKey]
- +[SAPAStyleMountStatus newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleMountStatusTracker classDictionaryKey]
- +[SAPAStyleMountStatusTracker newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleSample classDictionaryKey]
- +[SAPAStyleSample newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleSourceInfo classDictionaryKey]
- +[SAPAStyleSourceInfo newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleSymbol classDictionaryKey]
- +[SAPAStyleSymbol newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleSymbolDataStore classDictionaryKey]
- +[SAPAStyleSymbolDataStore newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleSymbolOwner classDictionaryKey]
- +[SAPAStyleSymbolOwner newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleTaskData classDictionaryKey]
- +[SAPAStyleTaskData newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleTaskPrivateData classDictionaryKey]
- +[SAPAStyleTaskPrivateData newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleThreadData classDictionaryKey]
- +[SAPAStyleThreadData newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleTimeInsensitiveTaskData classDictionaryKey]
- +[SAPAStyleTimeInsensitiveTaskData newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SAPAStyleWaitInfo classDictionaryKey]
- +[SAPAStyleWaitInfo newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]
- +[SATask taskWithoutReferencesFromPAStyleSerializedTask:]
- +[SATaskState stateWithPAStyleTaskPrivateData:donatingUniquePids:]
- +[SAThreadState stateWithoutReferencesFromPAStyleSerializedThread:]
- +[SAWaitInfo stateWithPAStyleSerializedWaitInfo:]
- -[SABinary addSymbolWithOffsetIntoBinary:length:name:]
- -[SABinary setName:]
- -[SABinaryLoadInfo populateReferencesUsingPAStyleSerializedImageInfo:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAFrame populateReferencesUsingPAStyleSerializedFrame:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAMountStatus populateReferencesUsingPAStyleSerializedMountStatus:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAMountStatusTracker populateReferencesUsingPAStyleSerializedMountStatusTracker:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleFanSpeed .cxx_destruct]
- -[SAPAStyleFanSpeed addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleFanSpeed addSelfToSerializationDictionary:]
- -[SAPAStyleFanSpeed populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleFanSpeed sizeInBytesForSerializedVersion]
- -[SAPAStyleFrame .cxx_destruct]
- -[SAPAStyleFrame addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleFrame addSelfToSerializationDictionary:]
- -[SAPAStyleFrame populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleFrame sizeInBytesForSerializedVersion]
- -[SAPAStyleHIDEvent .cxx_destruct]
- -[SAPAStyleHIDEvent addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleHIDEvent addSelfToSerializationDictionary:]
- -[SAPAStyleHIDEvent populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleHIDEvent sizeInBytesForSerializedVersion]
- -[SAPAStyleImageInfo .cxx_destruct]
- -[SAPAStyleImageInfo addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleImageInfo addSelfToSerializationDictionary:]
- -[SAPAStyleImageInfo populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleImageInfo sizeInBytesForSerializedVersion]
- -[SAPAStyleMountSnapshot .cxx_destruct]
- -[SAPAStyleMountSnapshot addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleMountSnapshot addSelfToSerializationDictionary:]
- -[SAPAStyleMountSnapshot populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleMountSnapshot sizeInBytesForSerializedVersion]
- -[SAPAStyleMountStatus .cxx_destruct]
- -[SAPAStyleMountStatus addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleMountStatus addSelfToSerializationDictionary:]
- -[SAPAStyleMountStatus populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleMountStatus sizeInBytesForSerializedVersion]
- -[SAPAStyleMountStatusTracker .cxx_destruct]
- -[SAPAStyleMountStatusTracker addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleMountStatusTracker addSelfToSerializationDictionary:]
- -[SAPAStyleMountStatusTracker populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleMountStatusTracker sizeInBytesForSerializedVersion]
- -[SAPAStyleSample .cxx_destruct]
- -[SAPAStyleSample addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleSample addSelfToSerializationDictionary:]
- -[SAPAStyleSample populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleSample sizeInBytesForSerializedVersion]
- -[SAPAStyleSourceInfo .cxx_destruct]
- -[SAPAStyleSourceInfo addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleSourceInfo addSelfToSerializationDictionary:]
- -[SAPAStyleSourceInfo populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleSourceInfo sizeInBytesForSerializedVersion]
- -[SAPAStyleSymbol .cxx_destruct]
- -[SAPAStyleSymbol addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleSymbol addSelfToSerializationDictionary:]
- -[SAPAStyleSymbol populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleSymbol sizeInBytesForSerializedVersion]
- -[SAPAStyleSymbolDataStore .cxx_destruct]
- -[SAPAStyleSymbolDataStore addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleSymbolDataStore addSelfToSerializationDictionary:]
- -[SAPAStyleSymbolDataStore populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleSymbolDataStore sizeInBytesForSerializedVersion]
- -[SAPAStyleSymbolOwner addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleSymbolOwner addSelfToSerializationDictionary:]
- -[SAPAStyleSymbolOwner populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleSymbolOwner sizeInBytesForSerializedVersion]
- -[SAPAStyleTaskData .cxx_destruct]
- -[SAPAStyleTaskData addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleTaskData addSelfToSerializationDictionary:]
- -[SAPAStyleTaskData populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleTaskData sizeInBytesForSerializedVersion]
- -[SAPAStyleTaskPrivateData addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleTaskPrivateData addSelfToSerializationDictionary:]
- -[SAPAStyleTaskPrivateData populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleTaskPrivateData sizeInBytesForSerializedVersion]
- -[SAPAStyleThreadData .cxx_destruct]
- -[SAPAStyleThreadData addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleThreadData addSelfToSerializationDictionary:]
- -[SAPAStyleThreadData populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleThreadData sizeInBytesForSerializedVersion]
- -[SAPAStyleTimeInsensitiveTaskData .cxx_destruct]
- -[SAPAStyleTimeInsensitiveTaskData addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleTimeInsensitiveTaskData addSelfToSerializationDictionary:]
- -[SAPAStyleTimeInsensitiveTaskData populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleTimeInsensitiveTaskData sizeInBytesForSerializedVersion]
- -[SAPAStyleWaitInfo .cxx_destruct]
- -[SAPAStyleWaitInfo _initWithSerializedWaitInfo:]
- -[SAPAStyleWaitInfo addSelfToBuffer:bufferLength:withCompletedSerializationDictionary:]
- -[SAPAStyleWaitInfo addSelfToSerializationDictionary:]
- -[SAPAStyleWaitInfo populateReferencesUsingBuffer:bufferLength:andDeserializationDictionary:andDataBufferDictionary:]
- -[SAPAStyleWaitInfo sizeInBytesForSerializedVersion]
- -[SASampleStore initWithPAStyleCoder:]
- -[SATask guessArchitectureGivenMachineArchitecture:dataSource:]
- -[SATask populateReferencesUsingPAStyleSerializedTask:andDeserializationDictionary:andDataBufferDictionary:]
- -[SATask removeStacksOutsideThisProcess]
- -[SATaskState applyPAStyleSampleTimestamp:]
- -[SAThreadState applyPAStyleSampleTimestamp:]
- -[SAThreadState populateReferencesUsingPAStyleSerializedThread:andDeserializationDictionary:andDataBufferDictionary:]
- GCC_except_table140
- GCC_except_table254
- GCC_except_table263
- GCC_except_table267
- GCC_except_table327
- GCC_except_table330
- GCC_except_table331
- GCC_except_table333
- GCC_except_table361
- GCC_except_table365
- GCC_except_table367
- GCC_except_table374
- GCC_except_table379
- GCC_except_table381
- GCC_except_table382
- GCC_except_table387
- GCC_except_table388
- GCC_except_table394
- GCC_except_table397
- GCC_except_table400
- GCC_except_table401
- GCC_except_table561
- GCC_except_table564
- GCC_except_table568
- GCC_except_table569
- GCC_except_table573
- GCC_except_table577
- GCC_except_table579
- GCC_except_table581
- GCC_except_table582
- GCC_except_table600
- GCC_except_table601
- GCC_except_table605
- _OBJC_CLASS_$_SAPAStyleFanSpeed
- _OBJC_CLASS_$_SAPAStyleFrame
- _OBJC_CLASS_$_SAPAStyleHIDEvent
- _OBJC_CLASS_$_SAPAStyleImageInfo
- _OBJC_CLASS_$_SAPAStyleMountSnapshot
- _OBJC_CLASS_$_SAPAStyleMountStatus
- _OBJC_CLASS_$_SAPAStyleMountStatusTracker
- _OBJC_CLASS_$_SAPAStyleSample
- _OBJC_CLASS_$_SAPAStyleSourceInfo
- _OBJC_CLASS_$_SAPAStyleSymbol
- _OBJC_CLASS_$_SAPAStyleSymbolDataStore
- _OBJC_CLASS_$_SAPAStyleSymbolOwner
- _OBJC_CLASS_$_SAPAStyleTaskData
- _OBJC_CLASS_$_SAPAStyleTaskPrivateData
- _OBJC_CLASS_$_SAPAStyleThreadData
- _OBJC_CLASS_$_SAPAStyleTimeInsensitiveTaskData
- _OBJC_CLASS_$_SAPAStyleWaitInfo
- _OBJC_IVAR_$_SAPAStyleFanSpeed._fanSpeed
- _OBJC_IVAR_$_SAPAStyleFrame._frame
- _OBJC_IVAR_$_SAPAStyleHIDEvent._hidEvent
- _OBJC_IVAR_$_SAPAStyleImageInfo._binaryLoadInfo
- _OBJC_IVAR_$_SAPAStyleMountSnapshot._mountSnapshot
- _OBJC_IVAR_$_SAPAStyleMountStatus._mountStatus
- _OBJC_IVAR_$_SAPAStyleMountStatusTracker._tracker
- _OBJC_IVAR_$_SAPAStyleSample._timestamp
- _OBJC_IVAR_$_SAPAStyleSourceInfo._columnNum
- _OBJC_IVAR_$_SAPAStyleSourceInfo._filePath
- _OBJC_IVAR_$_SAPAStyleSourceInfo._length
- _OBJC_IVAR_$_SAPAStyleSourceInfo._lineNum
- _OBJC_IVAR_$_SAPAStyleSourceInfo._offsetIntoTextSegment
- _OBJC_IVAR_$_SAPAStyleSymbol._length
- _OBJC_IVAR_$_SAPAStyleSymbol._name
- _OBJC_IVAR_$_SAPAStyleSymbol._offsetIntoTextSegment
- _OBJC_IVAR_$_SAPAStyleSymbol._sourceInfos
- _OBJC_IVAR_$_SAPAStyleSymbolDataStore._kernelCache
- _OBJC_IVAR_$_SAPAStyleSymbolDataStore._sharedCache32Bit
- _OBJC_IVAR_$_SAPAStyleSymbolDataStore._sharedCache64Bit
- _OBJC_IVAR_$_SAPAStyleSymbolOwner._hasTextExecSegment
- _OBJC_IVAR_$_SAPAStyleSymbolOwner._textSegmentLength
- _OBJC_IVAR_$_SAPAStyleTaskData._taskState
- _OBJC_IVAR_$_SAPAStyleTaskData._threadStates
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._cow_faults
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._faults
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._latency_qos
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._pageins
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._ss_flags
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._suspend_count
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._task_size_bytes
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._terminatedThreadsCycles
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._terminatedThreadsInstructions
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._terminatedThreadsSystemTimeInNs
- _OBJC_IVAR_$_SAPAStyleTaskPrivateData._terminatedThreadsUserTimeInNs
- _OBJC_IVAR_$_SAPAStyleThreadData._dispatchQueueId
- _OBJC_IVAR_$_SAPAStyleThreadData._isGlobalForcedIdle
- _OBJC_IVAR_$_SAPAStyleThreadData._threadId
- _OBJC_IVAR_$_SAPAStyleThreadData._threadState
- _OBJC_IVAR_$_SAPAStyleTimeInsensitiveTaskData._task
- _OBJC_IVAR_$_SAPAStyleWaitInfo._waitInfo
- _OBJC_METACLASS_$_SAPAStyleFanSpeed
- _OBJC_METACLASS_$_SAPAStyleFrame
- _OBJC_METACLASS_$_SAPAStyleHIDEvent
- _OBJC_METACLASS_$_SAPAStyleImageInfo
- _OBJC_METACLASS_$_SAPAStyleMountSnapshot
- _OBJC_METACLASS_$_SAPAStyleMountStatus
- _OBJC_METACLASS_$_SAPAStyleMountStatusTracker
- _OBJC_METACLASS_$_SAPAStyleSample
- _OBJC_METACLASS_$_SAPAStyleSourceInfo
- _OBJC_METACLASS_$_SAPAStyleSymbol
- _OBJC_METACLASS_$_SAPAStyleSymbolDataStore
- _OBJC_METACLASS_$_SAPAStyleSymbolOwner
- _OBJC_METACLASS_$_SAPAStyleTaskData
- _OBJC_METACLASS_$_SAPAStyleTaskPrivateData
- _OBJC_METACLASS_$_SAPAStyleThreadData
- _OBJC_METACLASS_$_SAPAStyleTimeInsensitiveTaskData
- _OBJC_METACLASS_$_SAPAStyleWaitInfo
- _SASerializableNewMutableDictionaryFromIndexList
- __OBJC_$_CLASS_METHODS_SAPAStyleFanSpeed
- __OBJC_$_CLASS_METHODS_SAPAStyleFrame
- __OBJC_$_CLASS_METHODS_SAPAStyleHIDEvent
- __OBJC_$_CLASS_METHODS_SAPAStyleImageInfo
- __OBJC_$_CLASS_METHODS_SAPAStyleMountSnapshot
- __OBJC_$_CLASS_METHODS_SAPAStyleMountStatus
- __OBJC_$_CLASS_METHODS_SAPAStyleMountStatusTracker
- __OBJC_$_CLASS_METHODS_SAPAStyleSample
- __OBJC_$_CLASS_METHODS_SAPAStyleSourceInfo
- __OBJC_$_CLASS_METHODS_SAPAStyleSymbol
- __OBJC_$_CLASS_METHODS_SAPAStyleSymbolDataStore
- __OBJC_$_CLASS_METHODS_SAPAStyleSymbolOwner
- __OBJC_$_CLASS_METHODS_SAPAStyleTaskData
- __OBJC_$_CLASS_METHODS_SAPAStyleTaskPrivateData
- __OBJC_$_CLASS_METHODS_SAPAStyleThreadData
- __OBJC_$_CLASS_METHODS_SAPAStyleTimeInsensitiveTaskData
- __OBJC_$_CLASS_METHODS_SAPAStyleWaitInfo
- __OBJC_$_INSTANCE_METHODS_SAPAStyleFanSpeed
- __OBJC_$_INSTANCE_METHODS_SAPAStyleFrame
- __OBJC_$_INSTANCE_METHODS_SAPAStyleHIDEvent
- __OBJC_$_INSTANCE_METHODS_SAPAStyleImageInfo
- __OBJC_$_INSTANCE_METHODS_SAPAStyleMountSnapshot
- __OBJC_$_INSTANCE_METHODS_SAPAStyleMountStatus
- __OBJC_$_INSTANCE_METHODS_SAPAStyleMountStatusTracker
- __OBJC_$_INSTANCE_METHODS_SAPAStyleSample
- __OBJC_$_INSTANCE_METHODS_SAPAStyleSourceInfo
- __OBJC_$_INSTANCE_METHODS_SAPAStyleSymbol
- __OBJC_$_INSTANCE_METHODS_SAPAStyleSymbolDataStore
- __OBJC_$_INSTANCE_METHODS_SAPAStyleSymbolOwner
- __OBJC_$_INSTANCE_METHODS_SAPAStyleTaskData
- __OBJC_$_INSTANCE_METHODS_SAPAStyleTaskPrivateData
- __OBJC_$_INSTANCE_METHODS_SAPAStyleThreadData
- __OBJC_$_INSTANCE_METHODS_SAPAStyleTimeInsensitiveTaskData
- __OBJC_$_INSTANCE_METHODS_SAPAStyleWaitInfo
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleFanSpeed
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleFrame
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleHIDEvent
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleImageInfo
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleMountSnapshot
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleMountStatus
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleMountStatusTracker
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleSample
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleSourceInfo
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleSymbol
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleSymbolDataStore
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleSymbolOwner
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleTaskData
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleTaskPrivateData
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleThreadData
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleTimeInsensitiveTaskData
- __OBJC_$_INSTANCE_VARIABLES_SAPAStyleWaitInfo
- __OBJC_$_PROP_LIST_SAPAStyleFanSpeed
- __OBJC_$_PROP_LIST_SAPAStyleFrame
- __OBJC_$_PROP_LIST_SAPAStyleHIDEvent
- __OBJC_$_PROP_LIST_SAPAStyleImageInfo
- __OBJC_$_PROP_LIST_SAPAStyleMountSnapshot
- __OBJC_$_PROP_LIST_SAPAStyleMountStatus
- __OBJC_$_PROP_LIST_SAPAStyleMountStatusTracker
- __OBJC_$_PROP_LIST_SAPAStyleSample
- __OBJC_$_PROP_LIST_SAPAStyleSourceInfo
- __OBJC_$_PROP_LIST_SAPAStyleSymbol
- __OBJC_$_PROP_LIST_SAPAStyleSymbolDataStore
- __OBJC_$_PROP_LIST_SAPAStyleSymbolOwner
- __OBJC_$_PROP_LIST_SAPAStyleTaskData
- __OBJC_$_PROP_LIST_SAPAStyleTaskPrivateData
- __OBJC_$_PROP_LIST_SAPAStyleThreadData
- __OBJC_$_PROP_LIST_SAPAStyleTimeInsensitiveTaskData
- __OBJC_$_PROP_LIST_SAPAStyleWaitInfo
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleFanSpeed
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleFrame
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleHIDEvent
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleImageInfo
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleMountSnapshot
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleMountStatus
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleMountStatusTracker
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleSample
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleSourceInfo
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleSymbol
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleSymbolDataStore
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleSymbolOwner
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleTaskData
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleTaskPrivateData
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleThreadData
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleTimeInsensitiveTaskData
- __OBJC_CLASS_PROTOCOLS_$_SAPAStyleWaitInfo
- __OBJC_CLASS_RO_$_SAPAStyleFanSpeed
- __OBJC_CLASS_RO_$_SAPAStyleFrame
- __OBJC_CLASS_RO_$_SAPAStyleHIDEvent
- __OBJC_CLASS_RO_$_SAPAStyleImageInfo
- __OBJC_CLASS_RO_$_SAPAStyleMountSnapshot
- __OBJC_CLASS_RO_$_SAPAStyleMountStatus
- __OBJC_CLASS_RO_$_SAPAStyleMountStatusTracker
- __OBJC_CLASS_RO_$_SAPAStyleSample
- __OBJC_CLASS_RO_$_SAPAStyleSourceInfo
- __OBJC_CLASS_RO_$_SAPAStyleSymbol
- __OBJC_CLASS_RO_$_SAPAStyleSymbolDataStore
- __OBJC_CLASS_RO_$_SAPAStyleSymbolOwner
- __OBJC_CLASS_RO_$_SAPAStyleTaskData
- __OBJC_CLASS_RO_$_SAPAStyleTaskPrivateData
- __OBJC_CLASS_RO_$_SAPAStyleThreadData
- __OBJC_CLASS_RO_$_SAPAStyleTimeInsensitiveTaskData
- __OBJC_CLASS_RO_$_SAPAStyleWaitInfo
- __OBJC_METACLASS_RO_$_SAPAStyleFanSpeed
- __OBJC_METACLASS_RO_$_SAPAStyleFrame
- __OBJC_METACLASS_RO_$_SAPAStyleHIDEvent
- __OBJC_METACLASS_RO_$_SAPAStyleImageInfo
- __OBJC_METACLASS_RO_$_SAPAStyleMountSnapshot
- __OBJC_METACLASS_RO_$_SAPAStyleMountStatus
- __OBJC_METACLASS_RO_$_SAPAStyleMountStatusTracker
- __OBJC_METACLASS_RO_$_SAPAStyleSample
- __OBJC_METACLASS_RO_$_SAPAStyleSourceInfo
- __OBJC_METACLASS_RO_$_SAPAStyleSymbol
- __OBJC_METACLASS_RO_$_SAPAStyleSymbolDataStore
- __OBJC_METACLASS_RO_$_SAPAStyleSymbolOwner
- __OBJC_METACLASS_RO_$_SAPAStyleTaskData
- __OBJC_METACLASS_RO_$_SAPAStyleTaskPrivateData
- __OBJC_METACLASS_RO_$_SAPAStyleThreadData
- __OBJC_METACLASS_RO_$_SAPAStyleTimeInsensitiveTaskData
- __OBJC_METACLASS_RO_$_SAPAStyleWaitInfo
- ___55-[SATask(Serialization) removeStacksOutsideThisProcess]_block_invoke
- ___55-[SATask(Serialization) removeStacksOutsideThisProcess]_block_invoke_2
- ___55-[SATask(Serialization) removeStacksOutsideThisProcess]_block_invoke_3
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke_2
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke_3
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke_4
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke_5
- ___61-[SASampleStore(SASampleStoreNSCoding) initWithPAStyleCoder:]_block_invoke_6
- ___90+[SAPAStyleTaskPrivateData newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:]_block_invoke
- ___block_descriptor_32_e21_B24?0"SAFrame"8^B16l
- ___block_descriptor_48_ea8_32s40r_e28_v32?0"SATaskState"8Q16^B24ls32l8r40l8
- ___block_descriptor_48_ea8_32s40r_e35_v32?0"NSNumber"8"SAThread"16^B24lr40l8s32l8
- ___block_descriptor_56_ea8_32s40s48r_e20_v24?0"SATask"8^B16ls32l8s40l8r48l8
- ___block_descriptor_56_ea8_32s40s48s_e30_v32?0"SAThreadState"8Q16^B24ls32l8s40l8s48l8
- _newInstanceWithoutReferencesFromSerializedBuffer:bufferLength:.onceToken
CStrings:
+ "Bad compressed size %lu"
+ "SASafeBufferSize: addition overflow"
+ "SASafeBufferSize: multiplication overflow"
+ "SAWSUpdate: min size %lu < buffer length %lu"
+ "SAWSUpdate: size %llu < buffer length %lu"
+ "SAWSUpdate: size %lu != buffer length %lu"
+ "Unable to allocate buffer for binary format length %llu: %{errno}d"
+ "Unable to decode binary format: PASampling binary format is no longer supported. Try an older build\n"
+ "Unreasonable uncompressed size %llu (max %llu)"
+ "bad length SANSString"
+ "bufLength >= sizeof(uint64_t)"
+ "bufStart + bufLength >= startOfSerializedInstances"
+ "bufStart + buffer.length >= bufAndLen.buf + bufAndLen.len"
+ "bufferLength %lu < serialized SAHIDEvent v2 struct with %u steps"
+ "bufferLength %lu < serialized SAInstruction struct v3 %lu with %u inline symbols"
+ "bufferLength %lu < serialized SAInstruction struct v4 %lu with %u inline symbols"
+ "bufferLength == sizeof(SASerializedWSUpdate)"
+ "bufferLength >= SASafeAddSize(SASafeBufferSize(sizeof(*serializedHIDEvent), sizeof(SASerializedHIDStep), serializedHIDEvent->numSteps), sizeof(*additions_v2))"
+ "bufferLength >= SASafeAddSize(SASafeBufferSize(sizeof(*serializedInstruction_v3), sizeof(SASerializedSymbolAndSource), serializedInstruction_v3->numInlineSymbolAndSources), sizeof(*additions_v4))"
+ "bufferLength >= SASafeAddSize(SASafeIndexBufferSize(sizeof(*serializedSharedCache), serializedSharedCache->numBinaryLoadInfos), sizeof(SASerializedSharedCache_v2_additions))"
+ "bufferLength >= SASafeAddSize(SASafeIndexBufferSize(sizeof(*serializedSharedCache), serializedSharedCache->numBinaryLoadInfos), sizeof(SASerializedSharedCache_v3_additions))"
+ "bufferLength >= SASafeAddSize(SASafeIndexBufferSize(sizeof(*serializedSharedCache), serializedSharedCache->numBinaryLoadInfos), sizeof(SASerializedSharedCache_v4_additions))"
+ "bufferLength >= SASafeAddSize(SASafeIndexBufferSize(sizeof(*serializedThread), serializedThread->numThreadStates), sizeof(*additions_v2))"
+ "bufferLength >= SASafeAddSize(SASafeIndexBufferSize(sizeof(*serializedThread), serializedThread->numThreadStates), sizeof(*additions_v3))"
+ "bufferLength >= SASafeBufferSize(sizeof(*serializedHIDEvent), sizeof(SASerializedHIDStep), serializedHIDEvent->numSteps)"
+ "bufferLength >= SASafeBufferSize(sizeof(*serializedInstruction_v3), sizeof(SASerializedSymbolAndSource), serializedInstruction_v3->numInlineSymbolAndSources)"
+ "bufferLength >= SASafeBufferSize(sizeof(*serializedMountSnapshot), sizeof(uint64_t), serializedMountSnapshot->numBlockedThreads)"
+ "bufferLength >= SASafeBufferSize(sizeof(*serializedMountStatusTracker), sizeof(SASerializedMountStatusTrackerDictionaryEntry), serializedMountStatusTracker->numMounts)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedDispatchQueue), serializedDispatchQueue->numDispatchQueueStates)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedFrame), serializedFrame->numChildFrames)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedGesture), serializedGesture->numHIDEvents)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedKernelCache), serializedKernelCache->numBinaryLoadInfos)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedModel), (uint64_t)serializedModel->numLoadedChanges + serializedModel->numExecutions)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedModelLoadedChange), serializedModelLoadedChange->numRequesters)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedMountStatus), serializedMountStatus->numSnapshots)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedSharedCache), serializedSharedCache->numBinaryLoadInfos)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedSwiftTask), serializedSwiftTask->numSwiftTaskStates)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedTask), (uint64_t)serializedTask->numRootUserFrames + serializedTask->numImageInfos + serializedTask->numTaskStates + serializedTask->numThreads + serializedTask->numDispatchQueues)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedTaskState), serializedTaskState->numDonatineUniquePids)"
+ "bufferLength >= SASafeIndexBufferSize(sizeof(*serializedThread), serializedThread->numThreadStates)"
+ "bufferLength >= size"
+ "bufferLength >= sizeof(SASerializedWSUpdateDataStore)"
+ "data buffer invalid size %llu"
+ "data buffer of size %llu does not contain object %ld-%ld"
+ "data buffer of size %llu doesn't contain %llu instances"
+ "data buffer of size %llu index %llu at invalid offset %llu"
+ "data buffer of size %llu too small for %llu instance index table entries"
+ "index %llu (%llu) <= index %llu (%llu), or over %llu"
+ "instanceOffset < maxOffset"
+ "nextInstanceOffset > instanceOffset && nextInstanceOffset < maxOffset"
+ "numInstances <= (bufLength - sizeof(uint64_t)) / sizeof(uint64_t)"
+ "serializedFrame_length >= SASafeIndexBufferSize(sizeof(*serializedFrame), serializedFrame->numChildFrames)"
- "%s: %u mounts"
- "%s: already know architecture %s, but guessing from machine architecture %s (data source 0x%llx)"
- "Bad PAFanSpeed magic"
- "Bad PAMountStatus magic"
- "Bad PAMountStatusTracker magic"
- "Bad PASampleFrame magic"
- "Bad PASerializedSymbolOwner magic"
- "Bad PASymbol magic"
- "Bad PASymbolDataStore magic"
- "Bad PASymbolOwner magic"
- "Bad PASymbolSourceInfo magic"
- "Bad SAPAStyleHIDEvent magic"
- "Bad SAPAStyleTaskData magic"
- "Bad SAPAStyleTaskPrivateData magic"
- "Bad SAPAStyleTimeInsensitiveTaskData magic"
- "Bad SASample magic"
- "Bad SASerializedIndexKeyValuePair magic"
- "Bad leaf frame index"
- "Bad leaf kernel frame index"
- "Bad leaf user frame index"
- "Bad magic"
- "Bad magic for SAPAStyleImageInfo"
- "Bad thread name index"
- "Bad uncompressed size %llu"
- "Bad wait info index"
- "Could not create new sample from buffer"
- "Could not deserialize key"
- "Could not deserialize mount status"
- "Could not deserialize value"
- "Could not get time insensitive instance"
- "Decoding PASampling spindumps is no longer supported"
- "Encoded version too old"
- "Failed to deserialize paImageInfo"
- "Failed to deserialize root frame"
- "FanSpeedIndices"
- "HIDEventIndices"
- "Invalid index found"
- "MountStatusTrackerIndex"
- "NULL buffer for SAPAStyleImageInfo"
- "NULL serializedFanSpeed"
- "NULL serializedHIDEvent"
- "NULL serializedTaskPrivateData"
- "NULL serializedTask_v2"
- "PASample"
- "PASampleFrame"
- "PASampleTaskData"
- "PASampleTaskDataPrivateData"
- "PASampleThreadData"
- "PASampleTimeInsensitiveTaskData"
- "PASampleWaitInfo"
- "PASerializedFanSpeed"
- "PASerializedHIDEvent"
- "PASerializedMountSnapshot"
- "PASerializedMountStatus"
- "PAStackshotImageInfo"
- "PASymbol"
- "PASymbolDataStore"
- "PASymbolOwner"
- "PASymbolSourceInfo"
- "Passed NULL buffer"
- "Passed NULL serializedTimeInsensitiveTask_v5"
- "Passed in NULL buffer"
- "RootKernelFrames"
- "SACSArchIsNULL(_architecture)"
- "SampleDataIndices"
- "SymbolDataStoreIndex"
- "TimeInsensitiveTaskIndices"
- "Tried to initialize with bad waitinfo"
- "Trying to encode SAPAStyleFanSpeed"
- "Trying to encode SAPAStyleFrame"
- "Trying to encode SAPAStyleHIDEvent"
- "Trying to encode SAPAStyleImageInfo"
- "Trying to encode SAPAStyleMountSnapshot"
- "Trying to encode SAPAStyleMountStatus"
- "Trying to encode SAPAStyleMountStatusTracker"
- "Trying to encode SAPAStyleSample"
- "Trying to encode SAPAStyleSourceInfo"
- "Trying to encode SAPAStyleSymbol"
- "Trying to encode SAPAStyleSymbolDataStore"
- "Trying to encode SAPAStyleSymbolOwner"
- "Trying to encode SAPAStyleTaskData"
- "Trying to encode SAPAStyleTaskPrivateData"
- "Trying to encode SAPAStyleThreadData"
- "Trying to encode SAPAStyleTimeInsensitiveTaskData"
- "Trying to encode SAPAStyleWaitInfo"
- "Trying to init with nil serializedTimeInsensitiveTask_v5"
- "Unable to allocate buffer for binary format: %{errno}d"
- "Unexpected fan index array length"
- "Unexpected hid event array length"
- "Unexpected sample index array length"
- "Unexpected task index array length"
- "WARNING: Bad magic value"
- "WARNING: Passed NULL serializedImageInfo"
- "WSUpdateDataStoreIndex"
- "Warning: Assuming page size is %lu bytes for task size\n"
- "_cpuPercent"
- "_machineArchitecture"
- "_wakeupsPerSec"
- "bufferLength >= ((uintptr_t)additions_v2) + sizeof(*additions_v2) - ((uintptr_t)buffer)"
- "bufferLength >= sizeof(*serializedDispatchQueue) + (sizeof(SASerializedIndex) * (serializedDispatchQueue->numDispatchQueueStates))"
- "bufferLength >= sizeof(*serializedFrame) + (sizeof(SASerializedIndex) * serializedFrame->numChildFrames)"
- "bufferLength >= sizeof(*serializedGesture) + (sizeof(SASerializedIndex) * serializedGesture->numHIDEvents)"
- "bufferLength >= sizeof(*serializedHIDEvent) + (sizeof(SASerializedIndex) * serializedHIDEvent->numSteps)"
- "bufferLength >= sizeof(*serializedKernelCache) + (sizeof(SASerializedIndex) * serializedKernelCache->numBinaryLoadInfos)"
- "bufferLength >= sizeof(*serializedModel) + (sizeof(SASerializedIndex) * (serializedModel->numLoadedChanges + serializedModel->numExecutions))"
- "bufferLength >= sizeof(*serializedModelLoadedChange) + (sizeof(SASerializedIndex) * (serializedModelLoadedChange->numRequesters))"
- "bufferLength >= sizeof(*serializedModelLoadedChange) + (sizeof(SASerializedIndex) * serializedModelLoadedChange->numRequesters)"
- "bufferLength >= sizeof(*serializedMountSnapshot) + (sizeof(SASerializedIndex) * serializedMountSnapshot->numBlockedThreads)"
- "bufferLength >= sizeof(*serializedMountStatus) + (sizeof(SASerializedIndex) * serializedMountStatus->numSnapshots)"
- "bufferLength >= sizeof(*serializedMountStatusTracker) + (sizeof(SASerializedIndex) * serializedMountStatusTracker->numMounts)"
- "bufferLength >= sizeof(*serializedSharedCache) + (sizeof(SASerializedIndex) * serializedSharedCache->numBinaryLoadInfos)"
- "bufferLength >= sizeof(*serializedSharedCache) + (sizeof(SASerializedIndex) * serializedSharedCache->numBinaryLoadInfos) + sizeof(SASerializedSharedCache_v2_additions)"
- "bufferLength >= sizeof(*serializedSharedCache) + (sizeof(SASerializedIndex) * serializedSharedCache->numBinaryLoadInfos) + sizeof(SASerializedSharedCache_v3_additions)"
- "bufferLength >= sizeof(*serializedSharedCache) + (sizeof(SASerializedIndex) * serializedSharedCache->numBinaryLoadInfos) + sizeof(SASerializedSharedCache_v4_additions)"
- "bufferLength >= sizeof(*serializedSwiftTask) + (sizeof(SASerializedIndex) * (serializedSwiftTask->numSwiftTaskStates))"
- "bufferLength >= sizeof(*serializedTask) + (sizeof(SASerializedIndex) * (serializedTask->numRootUserFrames + serializedTask->numImageInfos + serializedTask->numTaskStates + serializedTask->numThreads + serializedTask->numDispatchQueues))"
- "bufferLength >= sizeof(*serializedTaskState) + (sizeof(SASerializedIndex) * (serializedTaskState->numDonatineUniquePids))"
- "bufferLength >= sizeof(*serializedThread) + (sizeof(SASerializedIndex) * (serializedThread->numThreadStates))"
- "bufferLength >= sizeof(*serializedThread) + (sizeof(SASerializedIndex) * (serializedThread->numThreadStates)) + sizeof(*additions_v2)"
- "bufferLength >= sizeof(*serializedThread) + (sizeof(SASerializedIndex) * (serializedThread->numThreadStates)) + sizeof(*additions_v3)"
- "encodedVersion %ld for PAStyleCoder"
- "encodedVersion < 16"
- "hid event with %u steps"
- "index %llu (%llu) <= index %llu (%llu)"
- "indexTable[index + 1] > indexTable[index]"
- "nil leaf frame"
- "serializedFrame_length >= sizeof(*serializedFrame) + (sizeof(SASerializedIndex) * serializedFrame->numChildFrames)"
- "serializedHIDEvent->numSteps < UINT16_MAX"
- "serializedMountStatusTracker_v1->numMounts < UINT16_MAX"
```
