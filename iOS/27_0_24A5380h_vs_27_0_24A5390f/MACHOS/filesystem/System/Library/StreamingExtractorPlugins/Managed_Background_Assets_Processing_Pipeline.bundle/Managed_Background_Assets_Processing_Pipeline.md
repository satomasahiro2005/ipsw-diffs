## Managed Background Assets Processing Pipeline

> `/System/Library/StreamingExtractorPlugins/Managed Background Assets Processing Pipeline.bundle/Managed Background Assets Processing Pipeline`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6f4` | `0x47d60` | **`+0x2966c`** |
| `__TEXT.__eh_frame` | `0x11c0` | `0x2e38` | **`+0x1c78`** |
| `__DATA.__bss` | `0x880` | `0x2000` | **`+0x1780`** |
| `__TEXT.__const` | `0x924` | `0x1af8` | **`+0x11d4`** |
| `__TEXT.__oslogstring` | `0xf38` | `0x1ac8` | **`+0xb90`** |
| `__DATA.__data` | `0x8a0` | `0xfb8` | **`+0x718`** |
| `__TEXT.__unwind_info` | `0x630` | `0xd00` | **`+0x6d0`** |
| `__TEXT.__auth_stubs` | `0xe80` | `0x1470` | **`+0x5f0`** |
| `__TEXT.__swift5_typeref` | `0x495` | `0x890` | **`+0x3fb`** |
| `__DATA.__objc_const` | `0x5a8` | `0x928` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x21c` | `0x51c` | **`+0x300`** |
| `__DATA_CONST.__auth_got` | `0x748` | `0xa40` | **`+0x2f8`** |
| `__TEXT.__objc_stubs` | `0x100` | `0x340` | **`+0x240`** |
| `__DATA_CONST.__got` | `0x198` | `0x358` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x2aa` | `0x46a` | **`+0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0x260` | `0x410` | **`+0x1b0`** |
| `__TEXT.__swift_as_cont` | `0xc0` | `0x240` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x23a` | `0x390` | **`+0x156`** |
| `__DATA_CONST.__auth_ptr` | `0x238` | `0x348` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x2c0` | `0x1b0` | **`-0x110`** |
| `__TEXT.__objc_methname` | `0x62d` | `0x71a` | **`+0xed`** |
| `__TEXT.__swift5_acfuncs` | `—` | `0xdc` | **`+0xdc`** |
| `__TEXT.__swift5_proto` | `0x44` | `0xfc` | **`+0xb8`** |
| `__TEXT.__objc_classname` | `0x11b` | `0x1bb` | **`+0xa0`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0x120` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x150` | `0x1a8` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x70` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x768` | `0x7b8` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x78` | `0xb0` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x29e` | `0x271` | **`-0x2d`** |
| `__DATA.__objc_data` | `0x208` | `0x230` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x50` | **`+0x24`** |
| `__DATA.__common` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x38` | **`+0x20`** |
| `__DATA.__objc_ivar` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2.0.30.0.0
+2.0.32.0.0

+  - /System/Library/PrivateFrameworks/ManagedBackgroundAssetsRelay.framework/ManagedBackgroundAssetsRelay
+  - /System/Library/PrivateFrameworks/ManagedBackgroundAssetsXPC.framework/ManagedBackgroundAssetsXPC

+  - /usr/lib/swift/libswiftDistributed.dylib

-  Functions: 379
-  Symbols:   148
-  CStrings:  184
+  Functions: 736
+  Symbols:   182
+  CStrings:  253
Symbols:
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_MBAErrorLaundromat
+ _OBJC_CLASS_$_MBAProcessingPipelineFaçade
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_METACLASS_$_MBAErrorLaundromat
+ _OBJC_METACLASS_$_MBAProcessingPipelineFaçade
+ _free
+ _objc_alloc
+ _objc_autoreleaseReturnValue
+ _objc_opt_class
+ _objc_retain_x21
+ _objc_retain_x3
+ _objc_storeStrong
+ _object_setClass
+ _swift_allocBox
+ _swift_bridgeObjectRetain_n
+ _swift_conformsToProtocol2
+ _swift_coroFrameAlloc
+ _swift_cvw_allocateGenericValueMetadataWithLayoutString
+ _swift_cvw_instantiateLayoutString
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_deletedAsyncMethodErrorTu
+ _swift_distributedActor_remote_initialize
+ _swift_distributed_actor_is_remote
+ _swift_getDynamicType
+ _swift_getErrorValue
+ _swift_getGenericMetadata
+ _swift_getMetatypeMetadata
+ _swift_initStackObject
+ _swift_initStaticObject
+ _swift_makeBoxUnique
+ _swift_release_n
+ _swift_release_x10
+ _swift_release_x9
+ _swift_retain_x19
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_retain_x8
+ _swift_setDeallocating
- _objc_release_x1
- _objc_retain_x23
- _objc_retain_x24
- _objc_retain_x27
- _swift_unknownObjectUnownedDestroy
- _swift_unknownObjectUnownedInit
- _swift_unknownObjectUnownedLoadStrong
- _swift_unknownObjectWeakAssign
- _swift_unknownObjectWeakInit
- _swift_unknownObjectWeakLoadStrong
CStrings:
+ " app bundle ID: "
+ " internal version ID: "
+ "$defaultActor"
+ "<License Info | Asset-pack ID: "
+ "@\"MBADispatcher\""
+ "@24@0:8@16"
+ "A string value for the key “DownloadID” wasn’t found in the options dictionary."
+ "An existing processing pipeline couldn’t be retrieved: %{public}@"
+ "Bytes couldn’t be supplied to the stream: %{public}@"
+ "Init pipeline ID: %{public}s total bytes expected count: %llu delegate: %{public}s actor system: %{public}s"
+ "Init pipeline ID: %{public}s total bytes expected count: %llu license info: %{public}s delegate: %{public}s actor system: %{public}s"
+ "Init: %{public}s actor system: %{public}s"
+ "Invalid number of keys found, expected one."
+ "MBADispatcher"
+ "MBAErrorLaundromat"
+ "MBAProcessingPipelineFaçade"
+ "ManagedBackgroundAssetsProcessingPipeline/ProcessingPipeline.swift"
+ "Mark as active"
+ "Mark as complete at: %{public}s"
+ "Mark local pipeline as finished with ID: %{public}s"
+ "Mark local pipeline as resumed with ID: %{public}s"
+ "Mark local pipeline with ID: %{public}s as suspended at: %{public}s"
+ "Moving the extracted contents at “%{public}s” to “%{public}s”…"
+ "Moving the extracted manifest at “%{public}s” to “%{public}s”…"
+ "No download’s unique ID is available for the processing pipeline with the ID “%{public}s”."
+ "Prepare for extraction to: %{public}s"
+ "Preparing to extract to “%{public}s”…"
+ "Q"
+ "Removing the extraction directory at “%{public}s”…"
+ "Removing the resumption info for the download with the unique ID “%{public}s” via the relay…"
+ "Resumption Info.plist"
+ "Resumption info for the download with the unique ID “%{public}s” couldn’t be removed via the relay: %{public}@"
+ "Resumption info for the download with the unique ID “%{public}s” was found via the relay; reusing an existing processing pipeline…"
+ "Resumption info for the download with the unique ID “%{public}s” wasn’t found via the relay."
+ "Resumption info for the download with the unique ID “%{public}s” wasn’t found via the relay; creating a new processing pipeline with the ID “%{public}s”…"
+ "Resumption info wasn’t found at “%{public}s”; checking the relay for resumption info for the download with the unique ID “%{public}s”…"
+ "Set delegate encoded: %{public}s endpoint: %{public}s"
+ "Set progress: %f"
+ "TQ,R,N,VextractionMemoryFootprint"
+ "Terminate stream immediately with error: %{public}@"
+ "Terminate stream immediately with error: %{public}s"
+ "Terminate stream with error: %{public}s"
+ "The actor system couldn’t be retrieved: %{public}@"
+ "The actor system lacks an endpoint."
+ "The custom information is invalid."
+ "The delegate couldn’t be marked as complete: %{public}@"
+ "The destination URL is missing."
+ "The process exceeded its thread budget."
+ "The processing pipeline with the ID “%{public}s” couldn’t be canceled: %{public}@"
+ "The provided options are invalid."
+ "The resumption info at “%{public}s” couldn’t be updated: %{public}@"
+ "The resumption info for the download with the unique ID “%{public}s” couldn’t be updated via the relay: %{public}@"
+ "The resumption-info URL is missing."
+ "The stream couldn’t be prepared for extraction: %{public}@"
+ "The stream couldn’t be suspended: %{public}@"
+ "The stream couldn’t be terminated: %{public}@"
+ "Updating the resumption info at “%{public}s”…"
+ "Updating the resumption info for the download with the unique ID “%{public}s” via the relay…"
+ "_TtC41ManagedBackgroundAssetsProcessingPipeline17ExtractorDelegate"
+ "_TtC41ManagedBackgroundAssetsProcessingPipeline19ActorSystemDelegate"
+ "_state"
+ "actorSystem"
+ "code"
+ "copy"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "dataWithPropertyList:format:options:error:"
+ "destinationURL"
+ "dispatcher"
+ "domain"
+ "downloadID"
+ "id"
+ "initWithDomain:code:userInfo:"
+ "launderError:"
+ "localizedDescription"
+ "moveItemAtURL:toURL:error:"
+ "pipelineID"
+ "propertyListWithData:options:format:error:"
+ "temporaryDirectory"
+ "terminateStream(withError:)"
+ "userInfo"
+ "wrappedDelegate"
+ "” couldn’t be converted into a file path."
- "A processing pipeline couldn’t be created."
- "An options dictionary, “%{public}s”, was provided."
- "ManagedBackgroundAssetsProcessingPipeline.ProcessingPipeline"
- "Resumption info wasn’t found at “%{public}s”; creating a new processing pipeline with the ID “%{public}s”…"
- "ResumptionInfo.plist"
- "The thread budget was exceeded."
- "Tq,N,R,VextractionMemoryFootprint"
- "_TtC41ManagedBackgroundAssetsProcessingPipeline10Dispatcher"
- "delegateReference"
- "q"
- "resumptionInfoURL"
- "state"
- "terminateStreamWithError(_:)"
```
