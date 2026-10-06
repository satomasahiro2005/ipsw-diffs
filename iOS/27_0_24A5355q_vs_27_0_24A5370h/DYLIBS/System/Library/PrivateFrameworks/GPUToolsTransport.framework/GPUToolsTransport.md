## GPUToolsTransport

> `/System/Library/PrivateFrameworks/GPUToolsTransport.framework/GPUToolsTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x57b08` | `0x584e4` | **`+0x9dc`** |
| `__AUTH_CONST.__objc_const` | `0x15008` | `0x15198` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x9554` | `0x962c` | **`+0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x4bc0` | `0x4c60` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x46fb` | `0x4767` | **`+0x6c`** |
| `__AUTH.__objc_data` | `0x52d0` | `0x5320` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f78` | `0x2fa8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x12d4` | `0x12fd` | **`+0x29`** |
| `__TEXT.__unwind_info` | `0x1690` | `0x16a8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xb70` | `0xb80` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x848` | `0x850` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x790` | `0x798` | **`+0x8`** |

### Other Changes

```diff

-2027.0.28.0.0
+2027.0.31.0.0

-  Functions: 2942
-  Symbols:   6600
-  CStrings:  809
+  Functions: 2960
+  Symbols:   6632
+  CStrings:  814
Symbols:
+ +[GTDebugFetchResponseEntry entryWithFilename:data:]
+ +[GTDebugFetchResponseEntry supportsSecureCoding]
+ -[GTDebugFetchResponse entries]
+ -[GTDebugFetchResponse setEntries:]
+ -[GTDebugFetchResponseEntry .cxx_destruct]
+ -[GTDebugFetchResponseEntry data]
+ -[GTDebugFetchResponseEntry encodeWithCoder:]
+ -[GTDebugFetchResponseEntry hash]
+ -[GTDebugFetchResponseEntry initWithCoder:]
+ -[GTDebugFetchResponseEntry isEqual:]
+ -[GTDebugFetchResponseEntry setData:]
+ -[GTDebugFetchResponseEntry setSuggestedFilename:]
+ -[GTDebugFetchResponseEntry suggestedFilename]
+ -[GTDebugSessionStatus init]
+ -[GTDebugSessionStatus loadedProfileSessionIndex]
+ -[GTDebugSessionStatus setLoadedProfileSessionIndex:]
+ -[GTMLReplayCompileIdentifiers delegateId]
+ -[GTMLReplayCompileIdentifiers setDelegateId:]
+ -[GTMLReplayIntermediate index]
+ -[GTMLReplayIntermediate intermediateType]
+ -[GTMLReplayIntermediate setIndex:]
+ -[GTMLReplayIntermediate setIntermediateType:]
+ -[GTMTLReplayServiceXPCProxy bulkDataProxy]
+ _FailRequestNoBulkData
+ _OBJC_CLASS_$_GTDebugFetchResponseEntry
+ _OBJC_IVAR_$_GTDebugFetchResponse._entries
+ _OBJC_IVAR_$_GTDebugFetchResponseEntry._data
+ _OBJC_IVAR_$_GTDebugFetchResponseEntry._suggestedFilename
+ _OBJC_IVAR_$_GTDebugSessionStatus._loadedProfileSessionIndex
+ _OBJC_IVAR_$_GTMLReplayCompileIdentifiers._delegateId
+ _OBJC_IVAR_$_GTMLReplayIntermediate._index
+ _OBJC_IVAR_$_GTMLReplayIntermediate._intermediateType
+ _OBJC_IVAR_$_GTMTLReplayServiceXPCProxy._bulkDataProxyLock
+ _OBJC_METACLASS_$_GTDebugFetchResponseEntry
+ __OBJC_$_CLASS_METHODS_GTDebugFetchResponseEntry
+ __OBJC_$_CLASS_PROP_LIST_GTDebugFetchResponseEntry
+ __OBJC_$_INSTANCE_METHODS_GTDebugFetchResponseEntry
+ __OBJC_$_INSTANCE_VARIABLES_GTDebugFetchResponseEntry
+ __OBJC_$_PROP_LIST_GTDebugFetchResponseEntry
+ __OBJC_CLASS_PROTOCOLS_$_GTDebugFetchResponseEntry
+ __OBJC_CLASS_RO_$_GTDebugFetchResponseEntry
+ __OBJC_METACLASS_RO_$_GTDebugFetchResponseEntry
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- -[GTDebugFetchResponse data]
- -[GTDebugFetchResponse setData:]
- -[GTDebugFetchResponse setSuggestedFilename:]
- -[GTDebugFetchResponse suggestedFilename]
- -[GTMLReplayCompileIdentifiers .cxx_destruct]
- -[GTMLReplayCompileIdentifiers debugInfoIds]
- -[GTMLReplayCompileIdentifiers setDebugInfoIds:]
- _OBJC_IVAR_$_GTDebugFetchResponse._data
- _OBJC_IVAR_$_GTDebugFetchResponse._suggestedFilename
- _OBJC_IVAR_$_GTMLReplayCompileIdentifiers._debugInfoIds
- _OBJC_IVAR_$_GTMTLReplayServiceXPCProxy._acceleratorStructureSessionToDispatcherId
- _objc_retain_x9
CStrings:
+ "Failed to serialize profile response: %@"
+ "GTBulkDataService"
+ "GTMLReplayCompileIdentifiers(odixId: %llu, delegateId: %llu)"
+ "_delegateId"
+ "_index"
+ "_intermediateType"
+ "loadedProfileSessionIndex"
- "GTMLReplayCompileIdentifiers(odixId: %llu, debugInfoIds: %@)"
- "_debugInfoIds"
```
