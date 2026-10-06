## EntityService

> `/System/Library/PrivateFrameworks/EntityService.framework/EntityService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xccc30` | `0xd0bcc` | **`+0x3f9c`** |
| `__AUTH_CONST.__const` | `0x9420` | `0x9b88` | **`+0x768`** |
| `__DATA.__bss` | `0xf80` | `0x1280` | **`+0x300`** |
| `__TEXT.__const` | `0x3dd0` | `0x4050` | **`+0x280`** |
| `__TEXT.__swift5_capture` | `0x3600` | `0x3830` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x1c7e` | `0x1e56` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x25a7` | `0x2427` | **`-0x180`** |
| `__AUTH_CONST.__auth_got` | `0xfb8` | `0x10e0` | **`+0x128`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d0` | `0x5d8` | **`-0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x7f1` | `0x8d6` | **`+0xe5`** |
| `__TEXT.__eh_frame` | `0x63d0` | `0x62f8` | **`-0xd8`** |
| `__TEXT.__swift5_fieldmd` | `0xac4` | `0xb88` | **`+0xc4`** |
| `__DATA.__data` | `0x490` | `0x550` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x2460` | `0x23c0` | **`-0xa0`** |
| `__TEXT.__constg_swiftt` | `0xeec` | `0xe64` | **`-0x88`** |
| `__DATA_DIRTY.__data` | `0x16d0` | `0x1698` | **`-0x38`** |
| `__DATA.__common` | `0x20` | `0x50` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xa0` | `0xc8` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xdc` | `0xf4` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xd4` | `0xe4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x318` | `0x308` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3600.156.4.501.4
+3605.14.3.501.4

+  - /System/Library/Frameworks/HomeKit.framework/HomeKit

+  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 5239
-  Symbols:   351
-  CStrings:  375
+  Functions: 5263
+  Symbols:   307
+  CStrings:  378
Symbols:
+ _OBJC_CLASS_$_HMClientConnection
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
- _OBJC_CLASS_$_AssistantSiriAnalytics
- _OBJC_CLASS_$_ESSchemaESClientEvent
- _OBJC_CLASS_$_ESSchemaESClientEventMetadata
- _OBJC_CLASS_$_ESSchemaESCoerceEntityCanceled
- _OBJC_CLASS_$_ESSchemaESCoerceEntityContext
- _OBJC_CLASS_$_ESSchemaESCoerceEntityEnded
- _OBJC_CLASS_$_ESSchemaESCoerceEntityFailed
- _OBJC_CLASS_$_ESSchemaESCoerceEntityStarted
- _OBJC_CLASS_$_ESSchemaESDonateEntitiesCanceled
- _OBJC_CLASS_$_ESSchemaESDonateEntitiesContext
- _OBJC_CLASS_$_ESSchemaESDonateEntitiesEnded
- _OBJC_CLASS_$_ESSchemaESDonateEntitiesFailed
- _OBJC_CLASS_$_ESSchemaESDonateEntitiesStarted
- _OBJC_CLASS_$_ESSchemaESFullHydrationCanceled
- _OBJC_CLASS_$_ESSchemaESFullHydrationContext
- _OBJC_CLASS_$_ESSchemaESFullHydrationEnded
- _OBJC_CLASS_$_ESSchemaESFullHydrationFailed
- _OBJC_CLASS_$_ESSchemaESFullHydrationStarted
- _OBJC_CLASS_$_ESSchemaESFullyHydratedEntitiesCanceled
- _OBJC_CLASS_$_ESSchemaESFullyHydratedEntitiesContext
- _OBJC_CLASS_$_ESSchemaESFullyHydratedEntitiesEnded
- _OBJC_CLASS_$_ESSchemaESFullyHydratedEntitiesFailed
- _OBJC_CLASS_$_ESSchemaESFullyHydratedEntitiesStarted
- _OBJC_CLASS_$_ESSchemaESHydrateEntitiesCanceled
- _OBJC_CLASS_$_ESSchemaESHydrateEntitiesContext
- _OBJC_CLASS_$_ESSchemaESHydrateEntitiesEnded
- _OBJC_CLASS_$_ESSchemaESHydrateEntitiesFailed
- _OBJC_CLASS_$_ESSchemaESHydrateEntitiesStarted
- _OBJC_CLASS_$_ESSchemaESHydrateEntityPropertiesCanceled
- _OBJC_CLASS_$_ESSchemaESHydrateEntityPropertiesContext
- _OBJC_CLASS_$_ESSchemaESHydrateEntityPropertiesEnded
- _OBJC_CLASS_$_ESSchemaESHydrateEntityPropertiesFailed
- _OBJC_CLASS_$_ESSchemaESHydrateEntityPropertiesStarted
- _OBJC_CLASS_$_ESSchemaESSpotlightBatchCanceled
- _OBJC_CLASS_$_ESSchemaESSpotlightBatchContext
- _OBJC_CLASS_$_ESSchemaESSpotlightBatchEnded
- _OBJC_CLASS_$_ESSchemaESSpotlightBatchFailed
- _OBJC_CLASS_$_ESSchemaESSpotlightBatchStarted
- _OBJC_CLASS_$_ESSchemaESToolKitBatchCanceled
- _OBJC_CLASS_$_ESSchemaESToolKitBatchContext
- _OBJC_CLASS_$_ESSchemaESToolKitBatchEnded
- _OBJC_CLASS_$_ESSchemaESToolKitBatchFailed
- _OBJC_CLASS_$_ESSchemaESToolKitBatchStarted
- _OBJC_CLASS_$_SISchemaErrorInfo
- _OBJC_CLASS_$_SISchemaRequestLink
- _OBJC_CLASS_$_SISchemaRequestLinkInfo
- _OBJC_CLASS_$_SISchemaUUID
- _swift_task_localValueGet
- _swift_task_localValuePop
- _swift_task_localValuePush
CStrings:
+ "EntityService/EntityServiceTracing.swift"
+ "HomeKitHydrationAdapter.hydrateEntities"
+ "[%s.%s]: %ld entities reported as authoritative misses, not retrying via ToolKit"
+ "[%s.%s]: HomeKit hydration failed for %ld entity(ies), leaving them retryable: %{public}s [%{public}s %{public}ld]"
+ "[%s.%s]: HomeKit resolved %ld/%ld entities"
+ "[%s.%s]: HomeKit resolved %ld/%ld entities; homed is authoritative so the rest are not retried"
+ "[%s.%s]: malformed HomeKit id %{sensitive}s"
+ "cache"
+ "createService(cachePolicy:toolbox:entityChunkSize:enrichers:spotlightPreferredBundleIDs:existingSessionHolder:specProvider:appExclusionService:remoteEntityHydrator:instrumentationObserver:)"
+ "fullHydration(for:useSpotlightPreferred:propertyHydrationSpec:)"
+ "hydrateBatch(type:batch:propertyHydrationSpec:)"
+ "hydrateEntities(values:propertyHydrationSpec:)"
+ "localHydratedEntities(for:propertyHydrationSpec:)"
+ "localHydratedEntities(with:)"
+ "processBundleGroup(bundleId:indexedInputs:)"
+ "remote"
+ "spotlight"
+ "startCoerce(bundleId:)"
+ "startDonate(entityCount:)"
+ "startFullHydration(entityCount:useSpotlightPreferred:propertyHydrationSpec:)"
+ "startHydrateFull(entityCount:propertyHydrationSpec:)"
+ "startHydrateLod(entityCount:)"
+ "startHydrateProperties(bundleId:)"
+ "startSpotlightBatch(bundleId:entityCount:)"
+ "startToolKitBatch(bundleId:entityCount:propertyHydrationSpec:)"
+ "toolkit"
- "EntityService/ManagedHydratedEntityProvider.swift"
- "[ESSelf] %{public}s called without traceId via convenience overload — RequestLink correlation to EntityService will be skipped. Caller should pass traceId: UUID? directly (rdar://171208899)."
- "[ESSelf] ToolKitExecutionInterface.hydrateEntities called without parentEntityServiceId via convenience overload — ESToolKitBatch events will be standalone (entityServiceId=%{public}s). Caller should pass parentEntityServiceId: UUID directly (rdar://171208899)."
- "[ESSelf] emitted ESClientEvent entityServiceId=%{public}s which=%{public}lu"
- "[ESSelf] emitted RequestLink trace=%{public}s entityServiceId=%{public}s"
- "[ESSelf] failed to allocate ESClientEventMetadata"
- "[ESSelf] failed to allocate SISchemaRequestLink"
- "[ESSelf] failed to build ESClientEvent context"
- "coercedEntity(id:to:)"
- "coercedEntity(id:to:hydrateIfNeeded:traceId:)"
- "createService(cachePolicy:toolbox:entityChunkSize:enrichers:spotlightPreferredBundleIDs:existingSessionHolder:specProvider:appExclusionService:remoteEntityHydrator:)"
- "donateEntities(from:resolvedProperties:traceId:)"
- "fullHydration(for:useSpotlightPreferred:parentEntityServiceId:)"
- "hydrate(_:parentEntityServiceId:)"
- "hydrateBatch(type:batch:propertyHydrationSpec:parentEntityServiceId:)"
- "hydrateEntities(values:propertyHydrationSpec:parentEntityServiceId:)"
- "hydrateEntityProperties(value:resolveDeferredValues:)"
- "hydratedEntities(for:)"
- "hydratedEntities(for:propertyHydrationSpec:)"
- "hydratedEntities(with:)"
- "localHydratedEntities(for:propertyHydrationSpec:traceId:)"
- "localHydratedEntities(with:traceId:)"
- "processBundleGroup(bundleId:indexedInputs:parentEntityServiceId:)"
```
