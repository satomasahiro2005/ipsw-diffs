## EntityService

> `/System/Library/PrivateFrameworks/EntityService.framework/EntityService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6ef4` | `0xad3e0` | **`+0x64ec`** |
| `__AUTH_CONST.__const` | `0x7688` | `0x7be0` | **`+0x558`** |
| `__TEXT.__cstring` | `0x1898` | `0x1b24` | **`+0x28c`** |
| `__TEXT.__swift5_capture` | `0x2b48` | `0x2d64` | **`+0x21c`** |
| `__TEXT.__oslogstring` | `0x20a7` | `0x2227` | **`+0x180`** |
| `__AUTH_CONST.__auth_got` | `0xde0` | `0xeb0` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x1e90` | `0x1ef8` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x179e` | `0x17d6` | **`+0x38`** |
| `__DATA.__data` | `0x650` | `0x680` | **`+0x30`** |
| `__DATA.__common` | `0x80` | `0xa0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x698` | `0x6a0` | **`+0x8`** |
| `__TEXT.__const` | `0x38d8` | `0x38d0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x25c` | `0x260` | **`+0x4`** |

### Other Changes

```diff

-3600.138.6.501.17
+3600.144.5.501.3

-  Functions: 4504
-  Symbols:   341
-  CStrings:  287
+  Functions: 4680
+  Symbols:   342
+  CStrings:  307
Symbols:
+ _MDItemExternalID
+ _MDMailMessageID
- _MDItemIsAllDay
CStrings:
+ "Audio Visual Mode"
+ "Chat Unique Identifier"
+ "EntityService.autoSpecDeferredResolutionTimeoutMilliseconds"
+ "External Identifier"
+ "Mail Message Identifier"
+ "Organization Name"
+ "[%s.%s]: Binary schema not registered for %s; using synthetic definition"
+ "[%s.%s]: Deferred property resolution timed out after %s for %s"
+ "[%s.%s]: Resolving deferred property %s with timeout=%s"
+ "[%s.%s]: ToolKit hydration failed and no donation cache entry found — entity dropped: %s"
+ "[%s.%s]: ToolKit hydration failed, using donation cache fallback at resolvedProperties %s for %s"
+ "[%s] [Search-LoD] donation key audit: csItem=%{sensitive}s entityToIdentifier=%{sensitive}s hint=%{sensitive}s"
+ "_kMDItemMessageService"
+ "chatUniqueIdentifier"
+ "com.apple.contactsd"
+ "com_apple_mobilephone_callType"
+ "com_apple_mobilephone_provider"
+ "com_apple_mobilesms_chatUniqueIdentifier"
+ "fetchHydratedEntities(type:batch:propertyHydrationSpec:)"
+ "hydrate(value:propertyHydrationSpec:deferredResolutionTimeout:session:context:)"
+ "hydrateBatch(type:batch:propertyHydrationSpec:parentEntityServiceId:)"
+ "hydrateEntityProperties(entity:propertyHydrationSpec:deferredResolutionTimeout:session:context:)"
+ "kMDItemContainerDisplayName"
+ "kMDItemPhotosBusinessNames"
+ "kMDItemPhotosPeopleNamesAlternatives"
+ "kMDItemPhotosSceneClassificationLabels"
+ "organizationName"
+ "resolveEntityProperties(batch:hydratedLookup:propertyHydrationSpec:deferredResolutionTimeout:session:)"
- "[%s.%s]: Deferred property resolution timed out after %fs for %s"
- "[%s.%s]: Resolving deferred property %s with timeout=%fs"
- "__PARTIAL_ENTITY__"
- "fetchHydratedEntities(type:batch:session:displayRepresentationConfiguration:)"
- "hydrate(value:propertyHydrationSpec:session:context:)"
- "hydrateBatch(type:batch:session:propertyHydrationSpec:parentEntityServiceId:)"
- "hydrateEntityProperties(entity:propertyHydrationSpec:session:context:)"
- "resolveEntityProperties(batch:hydratedLookup:propertyHydrationSpec:session:)"
```
