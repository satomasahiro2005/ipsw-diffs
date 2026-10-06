## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9631c` | `0x966cc` | **`+0x3b0`** |
| `__TEXT.__oslogstring` | `0x7b5a` | `0x7ec5` | **`+0x36b`** |
| `__TEXT.__objc_methlist` | `0x799c` | `0x78d4` | **`-0xc8`** |
| `__DATA_CONST.__const` | `0x1618` | `0x1568` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x31b8` | `0x312b` | **`-0x8d`** |
| `__AUTH_CONST.__objc_const` | `0xe540` | `0xe4c8` | **`-0x78`** |
| `__TEXT.__gcc_except_tab` | `0x19cc` | `0x1954` | **`-0x78`** |
| `__AUTH_CONST.__cfstring` | `0x4b40` | `0x4ae0` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3148` | `0x30e8` | **`-0x60`** |
| `__AUTH_CONST.__auth_got` | `0x12e8` | `0x1330` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0xb28` | `0xb6e` | **`+0x46`** |
| `__AUTH_CONST.__objc_intobj` | `0x90` | `0x60` | **`-0x30`** |
| `__DATA.__data` | `0x2794` | `0x27c4` | **`+0x30`** |
| `__TEXT.__const` | `0x2ff8` | `0x3018` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x3148` | `0x3130` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x3198` | `0x3180` | **`-0x18`** |
| `__DATA_DIRTY.__objc_ivar` | `0x5b0` | `0x59c` | **`-0x14`** |
| `__DATA_CONST.__got` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x41a` | `0x42a` | **`+0x10`** |

### Other Changes

```diff

-1468.5.0.0.6
+1479.0.0.1.0

-  Functions: 3662
-  Symbols:   5490
-  CStrings:  1400
+  Functions: 3640
+  Symbols:   5463
+  CStrings:  1411
Symbols:
+ -[HMFDataBuilder .cxx_destruct]
+ -[HMFDataBuilder _invalidate]
+ -[HMFDataBuilder appendData:]
+ -[HMFDataBuilder copyAsMemoryMappedData]
+ -[HMFDataBuilder dealloc]
+ -[HMFDataBuilder init]
+ -[HMFDataBuilder length]
+ _HMFMapAndUnlinkFile
+ _HMFRemoveFileQuietly
+ _HMFTemporaryFileURL
+ _OBJC_CLASS_$_HMFDataBuilder
+ _OBJC_IVAR_$_HMFDataBuilder._appended
+ _OBJC_IVAR_$_HMFDataBuilder._failed
+ _OBJC_IVAR_$_HMFDataBuilder._fileHandle
+ _OBJC_IVAR_$_HMFDataBuilder._fileURL
+ _OBJC_IVAR_$_HMFDataBuilder._finalized
+ _OBJC_IVAR_$_HMFDataBuilder._length
+ _OBJC_METACLASS_$_HMFDataBuilder
+ __CATEGORY_NSError_$_HMFoundationSwift
+ __OBJC_$_CLASS_METHODS_NSError(HMFoundationSwift|HMFError|HMFoundation)
+ __OBJC_$_INSTANCE_METHODS_HMFDataBuilder
+ __OBJC_$_INSTANCE_METHODS_NSError(HMFoundationSwift|HMFError|HMFoundation)
+ __OBJC_$_INSTANCE_VARIABLES_HMFDataBuilder
+ __OBJC_$_PROP_LIST_HMFDataBuilder
+ __OBJC_CLASS_PROTOCOLS_$_NSError(HMFoundationSwift|HMFError|HMFoundation)
+ __OBJC_CLASS_RO_$_HMFDataBuilder
+ __OBJC_METACLASS_RO_$_HMFDataBuilder
+ __swiftEmptyDictionarySingleton
+ _symbolic SDyS2SG
+ _symbolic SS3key_yp5valuet
+ _symbolic _____yS2SG s18_DictionaryStorageC
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
- -[HMFKeyValueDatabase .cxx_destruct]
- -[HMFKeyValueDatabase _cancelSyncTimer]
- -[HMFKeyValueDatabase _startDelayedSyncTimerIfNeeded]
- -[HMFKeyValueDatabase _syncWithoutTimerHandling:]
- -[HMFKeyValueDatabase containsKey:]
- -[HMFKeyValueDatabase dealloc]
- -[HMFKeyValueDatabase dictionary]
- -[HMFKeyValueDatabase diskRepresentation]
- -[HMFKeyValueDatabase inMemoryDictionary]
- -[HMFKeyValueDatabase init]
- -[HMFKeyValueDatabase keys]
- -[HMFKeyValueDatabase memoryMonitor:didReceiveMemoryEvent:]
- -[HMFKeyValueDatabase queue]
- -[HMFKeyValueDatabase removeAllEntriesWithError:]
- -[HMFKeyValueDatabase setDiskRepresentation:]
- -[HMFKeyValueDatabase setInMemoryDictionary:]
- -[HMFKeyValueDatabase setQueue:]
- -[HMFKeyValueDatabase setSyncDelayInSeconds:]
- -[HMFKeyValueDatabase setSyncTimer:]
- -[HMFKeyValueDatabase setValue:forKey:error:]
- -[HMFKeyValueDatabase sync:]
- -[HMFKeyValueDatabase syncDelayInSeconds]
- -[HMFKeyValueDatabase syncTimer]
- -[HMFKeyValueDatabase valueForKey:error:]
- -[HMFKeyValueDatabase values]
- _HMFKeyValueDatabaseErrorDomain
- _HMFObjectInstanceKey
- _OBJC_CLASS_$_HMFKeyValueDatabase
- _OBJC_CLASS_$_NSTimer
- _OBJC_METACLASS_$_HMFKeyValueDatabase
- __OBJC_$_CATEGORY_NSError_$_HMFError
- __OBJC_$_CLASS_METHODS_NSError(HMFError|HMFoundation)
- __OBJC_$_INSTANCE_METHODS_HMFKeyValueDatabase
- __OBJC_$_INSTANCE_METHODS_NSError(HMFError|HMFoundation)
- __OBJC_$_INSTANCE_VARIABLES_HMFKeyValueDatabase
- __OBJC_$_PROP_LIST_HMFKeyValueDatabase
- __OBJC_CLASS_PROTOCOLS_$_HMFKeyValueDatabase
- __OBJC_CLASS_PROTOCOLS_$_NSError(HMFError|HMFoundation)
- __OBJC_CLASS_RO_$_HMFKeyValueDatabase
- __OBJC_METACLASS_RO_$_HMFKeyValueDatabase
- ___27-[HMFKeyValueDatabase keys]_block_invoke
- ___28-[HMFKeyValueDatabase sync:]_block_invoke
- ___29-[HMFKeyValueDatabase values]_block_invoke
- ___30-[HMFKeyValueDatabase dealloc]_block_invoke
- ___33-[HMFKeyValueDatabase dictionary]_block_invoke
- ___41-[HMFKeyValueDatabase valueForKey:error:]_block_invoke
- ___45-[HMFKeyValueDatabase setValue:forKey:error:]_block_invoke
- ___49-[HMFKeyValueDatabase removeAllEntriesWithError:]_block_invoke
- ___53-[HMFKeyValueDatabase _startDelayedSyncTimerIfNeeded]_block_invoke
- ___53-[HMFKeyValueDatabase _startDelayedSyncTimerIfNeeded]_block_invoke_2
- ___53-[HMFKeyValueDatabase _startDelayedSyncTimerIfNeeded]_block_invoke_3
- ___53-[HMFKeyValueDatabase _startDelayedSyncTimerIfNeeded]_block_invoke_4
- ___59-[HMFKeyValueDatabase memoryMonitor:didReceiveMemoryEvent:]_block_invoke
- ___block_descriptor_40_e8_32s_e17_v16?0"NSTimer"8ls32l8
- ___block_descriptor_48_e8_32s40r_e5_v8?0ls32l8r40l8
- ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
- ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8r48l8s40l8
- _dispatch_sync
- _kHMFKeyValueDatabaseQueueSpecificKey
- _swift_release_x9
CStrings:
+ "Notifying delegate of reachability change to %@"
+ "Parameter is required: 'URLPredicate'"
+ "Parameter is required: 'methodPredicate'"
+ "[%{public}@] Notifying delegate of reachability change to %@"
+ "[%{public}@] Parameter is required: 'URLPredicate'"
+ "[%{public}@] Parameter is required: 'methodPredicate'"
+ "[%{public}@] [HMFDataBuilder] Append called after %s"
+ "[%{public}@] [HMFDataBuilder] Failed to create temporary file at %{public}@"
+ "[%{public}@] [HMFDataBuilder] Failed to open file handle for %{public}@"
+ "[%{public}@] [HMFDataBuilder] close failed: %{public}@ code=%ld"
+ "[%{public}@] [HMFDataBuilder] copyAsMemoryMappedData called after %s"
+ "[%{public}@] [HMFDataBuilder] writeData failed: %{public}@ code=%ld"
+ "[%{public}@] [HMFMappedFile] dataWithContentsOfURL failed: %{public}@ code=%ld"
+ "[%{public}@] [HMFWiFiManagerDataSource] Device attachment callback: %@"
+ "[HMFDataBuilder] Append called after %s"
+ "[HMFDataBuilder] Failed to create temporary file at %{public}@"
+ "[HMFDataBuilder] Failed to open file handle for %{public}@"
+ "[HMFDataBuilder] close failed: %{public}@ code=%ld"
+ "[HMFDataBuilder] copyAsMemoryMappedData called after %s"
+ "[HMFDataBuilder] writeData failed: %{public}@ code=%ld"
+ "[HMFMappedFile] dataWithContentsOfURL failed: %{public}@ code=%ld"
+ "[HMFWiFiManagerDataSource] Device attachment callback: %@"
+ "finalization"
+ "write failure"
- "Failed to create memory-mapped data"
- "HMFKeyValueDatabaseErrorDomain"
- "Must be called on database serial queue"
- "Notifying delegate of reachablity change to %@"
- "Parameter is requred: 'URLPredicate'"
- "Parameter is requred: 'methodPredicate'"
- "[%{public}@] Notifying delegate of reachablity change to %@"
- "[%{public}@] Parameter is requred: 'URLPredicate'"
- "[%{public}@] Parameter is requred: 'methodPredicate'"
- "[%{public}@] [HMFWiFiManagerDataSource] Device attachement callback: %@"
- "[HMFWiFiManagerDataSource] Device attachement callback: %@"
- "com.apple.HMFoundation.HMFKeyValueDatabase"
- "v16@?0@\"NSTimer\"8"
```
