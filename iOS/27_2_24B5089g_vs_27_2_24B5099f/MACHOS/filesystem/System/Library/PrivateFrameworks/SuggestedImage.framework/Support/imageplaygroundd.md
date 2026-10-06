## imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13bb4` | `0x15924` | **`+0x1d70`** |
| `__DATA.__data` | `0xb30` | `0xd60` | **`+0x230`** |
| `__DATA.__objc_const` | `0x5d0` | `0x780` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x9ce` | `0xb5e` | **`+0x190`** |
| `__TEXT.__objc_methname` | `0x4f9` | `0x660` | **`+0x167`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x3c0` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x570` | `0x648` | **`+0xd8`** |
| `__TEXT.__auth_stubs` | `0x1050` | `0x1100` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x3ac` | `0x45c` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x428` | `0x4d4` | **`+0xac`** |
| `__TEXT.__objc_methtype` | `0xfd` | `0x1a6` | **`+0xa9`** |
| `__TEXT.__const` | `0xb00` | `0xba0` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xeb0` | `0xf20` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x150` | `0x1a8` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x830` | `0x888` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x278` | `0x2d0` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x1e7` | `0x23a` | **`+0x53`** |
| `__TEXT.__objc_classname` | `0x1cb` | `0x21b` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x104` | `0x154` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0xb0` | `0xe8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x580` | `0x5b8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x248` | `0x268` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x433` | `0x44d` | **`+0x1a`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0xac` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa4` | `0x98` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x84` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x5c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-198.2.7.100.0
+198.2.11.0.0

+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary
+  - /System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams

-  Functions: 315
-  Symbols:   414
-  CStrings:  147
+  Functions: 335
+  Symbols:   429
+  CStrings:  184
Symbols:
+ _$s14SuggestedImage22PhotosDeleteWakePolicyO14allowsPruneNow3now8defaultsSb10Foundation4DateV_So14NSUserDefaultsCtFZ
+ _$s14SuggestedImage22PhotosDeleteWakePolicyO20recordPruneCompleted3now8defaultsy10Foundation4DateV_So14NSUserDefaultsCtFZ
+ _$s14SuggestedImage30DefaultPersonalizationProducerC24pruneDeletedSourceAssets3forySayAA7UseCaseOG_tYaFTjTu
+ _$s14SuggestedImage7UseCaseO19sourceAssetPrunableSayACGvgZ
+ _$sSS10describingSSx_tclufC
+ _$sScP10backgroundScPvgZ
+ _$sSo14NSUserDefaultsC14SuggestedImageE06daemonB0ABvgZ
+ _BiomeLibrary
+ _OBJC_CLASS_$_BMBiomeScheduler
+ _OBJC_CLASS_$_BMPhotosDelete
+ _OBJC_CLASS_$_NSUserDefaults
+ _os_transaction_create
+ _swift_dynamicCastObjCClass
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_getMetatypeMetadata
+ _swift_makeBoxUnique
+ _swift_release_x25
+ _swift_retain_x23
- _swift_asyncLet_begin
- _swift_asyncLet_finish
- _swift_asyncLet_get
CStrings:
+ "@\"<BMStoreData>\"16@0:8"
+ "@\"BMStoreBookmark\"16@0:8"
+ "BMStoreEvent"
+ "BPSCancellable"
+ "Booted %ld of %ld registered dependency services."
+ "C16@0:8"
+ "DSLPublisher"
+ "Delete"
+ "Finished pruning deleted source assets (%{public}s) for %{public}ld use cases."
+ "Photos"
+ "Photos.Delete prune (%{public}s) arrived during an in-flight pass; coalescing."
+ "Photos.Delete subscription already established; ignoring duplicate start."
+ "Photos.Delete subscription completed or was cancelled."
+ "Photos.Delete subscription failed: %{public}@"
+ "Received an unexpected payload type on the Photos.Delete stream; ignoring."
+ "Service %s failed to start: %@"
+ "Subscribed to Photos.Delete via Biome Context (%{public}s)."
+ "T@\"<BMStoreData>\",R,N"
+ "TC,R,N"
+ "Td,R,N"
+ "_TtC16imageplaygroundd23PhotosDeleteWakeService"
+ "_isPruning"
+ "_needsRerun"
+ "_photosDeleteQueue"
+ "_subscription"
+ "bookmark"
+ "cancel"
+ "com.apple.imageplaygroundd.PhotosDelete.reader"
+ "com.apple.imageplaygroundd.photosDeleteWake.prune"
+ "com.apple.imageplaygroundd.photosDeleteWakeQueue"
+ "d16@0:8"
+ "error"
+ "eventBody"
+ "initWithIdentifier:targetQueue:waking:"
+ "sinkWithCompletion:receiveInput:"
+ "subscribeOn:"
+ "timestamp"
+ "v16@0:8"
+ "v16@?0@\"BPSCompletion\"8"
+ "v16@?0@8"
- "Attempted to boot up stubbed dependency service successfully."
- "Cannot continue boot-up phase; exiting with failure status code."
- "Dependency boot-up phase failed with error: %@"
```
