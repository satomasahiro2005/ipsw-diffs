## ModelCatalogRuntime

> `/System/Library/PrivateFrameworks/ModelCatalogRuntime.framework/ModelCatalogRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x89ecc` | `0x98934` | **`+0xea68`** |
| `__TEXT.__eh_frame` | `0x45b4` | `0x4f5c` | **`+0x9a8`** |
| `__AUTH_CONST.__const` | `0x4cf0` | `0x5400` | **`+0x710`** |
| `__TEXT.__const` | `0x3458` | `0x3988` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0x458a` | `0x4a9a` | **`+0x510`** |
| `__DATA.__bss` | `0x1f90` | `0x2410` | **`+0x480`** |
| `__DATA.__data` | `0x830` | `0xc28` | **`+0x3f8`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x21e8` | **`+0x360`** |
| `__TEXT.__swift5_typeref` | `0x1bb6` | `0x1f0c` | **`+0x356`** |
| `__TEXT.__swift5_capture` | `0x15c4` | `0x17b0` | **`+0x1ec`** |
| `__AUTH_CONST.__auth_got` | `0x14e8` | `0x16c8` | **`+0x1e0`** |
| `__TEXT.__constg_swiftt` | `0x1300` | `0x14d0` | **`+0x1d0`** |
| `__AUTH_CONST.__objc_const` | `0x1698` | `0x1858` | **`+0x1c0`** |
| `__TEXT.__swift5_fieldmd` | `0xcc8` | `0xe64` | **`+0x19c`** |
| `__AUTH.__data` | `0x488` | `0x610` | **`+0x188`** |
| `__TEXT.__swift5_reflstr` | `0xad3` | `0xc03` | **`+0x130`** |
| `__TEXT.__cstring` | `0x191b` | `0x19fe` | **`+0xe3`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a0` | `0x560` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x604` | `0x664` | **`+0x60`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0xa0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x1f0` | `0x220` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x1ac` | `0x1d8` | **`+0x2c`** |
| `__TEXT.__swift5_types` | `0x124` | `0x144` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x58` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x310` | `0x328` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x3d8` | `0x3e8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1608` | `0x1618` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x164` | `0x170` | **`+0xc`** |
| `__DATA_CONST.__const` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x178` | `0x180` | **`+0x8`** |

### Other Changes

```diff

-302.6.0.3.0
+308.7.0.1.0

+  - /System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 3342
-  Symbols:   253
-  CStrings:  372
+  Functions: 3595
+  Symbols:   273
+  CStrings:  397
Symbols:
+ _CCModelCatalogRequestedUseCaseContentArgumentIdentifierFromString
+ _OBJC_CLASS_$_CCItemInstance
+ _OBJC_CLASS_$_CCModelCatalogRequestedUseCaseContent
+ _OBJC_CLASS_$_CCModelCatalogRequestedUseCaseContentArgument
+ _OBJC_CLASS_$_CCModelCatalogRequestedUseCaseMetaContent
+ _OBJC_CLASS_$_CCSet
+ _OBJC_CLASS_$_CCSetChangeXPCListener
+ _OBJC_CLASS_$_CCSetDonation
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$__PASDeviceState
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _objc_autorelease
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_dynamicCastObjCClass
+ _swift_getEnumCaseMultiPayload
+ _swift_getTupleTypeMetadata2
+ _swift_storeEnumTagMultiPayload
CStrings:
+ "CascadeSetChangeTrigger."
+ "CascadeSetProvider skipping an item it could not decode"
+ "Monitor received a %{public}s set change"
+ "Rejecting a use case request for unknown identifier: %{public}s"
+ "RequestedUseCase cannot decode %{public}s because an argument records no name or value"
+ "RequestedUseCase cannot decode an item of type %{public}s"
+ "RequestedUseCase cannot decode an item that records no use case identifier"
+ "RequestedUseCaseStore found %{public}s already requested"
+ "RequestedUseCaseStore found nothing to release for %{public}s"
+ "RequestedUseCaseStore recording request for %{public}s with resolved arguments: %{public}s"
+ "RequestedUseCaseStore releasing %{public}ld request(s) for %{public}s"
+ "RequestedUseCases"
+ "SubscriptionEvaluationManager skipping evaluation as the AppleIntelligence.Availability stream is empty"
+ "SubscriptionEvaluationManager skipping evaluation because the device is class C locked"
+ "SubscriptionEvaluator isIFPEnabled: %{bool}d"
+ "SubscriptionEvaluator received error: %{public}@ while executing download condition: %s"
+ "SubscriptionEvaluator received error: %{public}@ while reading rows of download condition: %s"
+ "Unable to resolve a supported language from system language: "
+ "Unknown use case identifier: "
+ "bm_isIFPEnabled()"
+ "bm_requestedUseCaseVariants"
+ "bm_requestedUseCaseVariants was called without a use case identifier"
+ "bm_requestedUseCaseVariants(%{public}s) -> %{public}s"
+ "bm_requestedUseCaseVariants(%{public}s) could not read the requested use cases: %{public}@"
+ "bm_requestedUseCaseVariants(%{public}s) is not a known use case"
+ "com.apple.modelcatalog.agent.catalogservice"
+ "com.apple.modelcatalog.requestedusecasesetchangelistener"
+ "previous  "
+ "sourceItem instance "
- "Could not initialize Library.Streams.ModelCatalog.Subscriptions.Decisions source"
- "ModelCatalogRuntime/SubscriptionStreamWriter.swift"
- "SubscriptionEvaluationManager skipping evaluation as stream is empty"
- "SubscriptionEvaluator received error: %{public}@ while evaluating download condition: %s"
```
