## EntityService

> `/System/Library/PrivateFrameworks/EntityService.framework/EntityService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0238` | `0xcad50` | **`+0x1ab18`** |
| `__AUTH_CONST.__const` | `0x80b8` | `0x94e8` | **`+0x1430`** |
| `__TEXT.__eh_frame` | `0x50d0` | `0x61b8` | **`+0x10e8`** |
| `__TEXT.__swift5_capture` | `0x2f54` | `0x3638` | **`+0x6e4`** |
| `__TEXT.__cstring` | `0x1ba4` | `0x2244` | **`+0x6a0`** |
| `__TEXT.__unwind_info` | `0x1f20` | `0x23d8` | **`+0x4b8`** |
| `__TEXT.__const` | `0x3900` | `0x3d10` | **`+0x410`** |
| `__TEXT.__oslogstring` | `0x2227` | `0x25a7` | **`+0x380`** |
| `__TEXT.__swift5_typeref` | `0x1814` | `0x1b94` | **`+0x380`** |
| `__DATA.__data` | `0x2d8` | `0x448` | **`+0x170`** |
| `__TEXT.__swift_as_cont` | `0x388` | `0x484` | **`+0xfc`** |
| `__AUTH_CONST.__auth_got` | `0xec0` | `0xfb8` | **`+0xf8`** |
| `__DATA.__bss` | `0xe90` | `0xf80` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x9e0` | `0xac4` | **`+0xe4`** |
| `__TEXT.__constg_swiftt` | `0xe38` | `0xeec` | **`+0xb4`** |
| `__TEXT.__swift_as_ret` | `0x270` | `0x300` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x771` | `0x7f1` | **`+0x80`** |
| `__TEXT.__swift_as_entry` | `0x220` | `0x290` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a0` | `0x6c8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xd98` | `0xdb8` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xd4` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0xcc` | `0xdc` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x16c8` | `0x16d0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-3600.147.12.501.3
+3600.151.4.501.6

+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch
+  - /System/Library/PrivateFrameworks/HybridSearchAdapter.framework/HybridSearchAdapter

-  Functions: 4740
-  Symbols:   343
-  CStrings:  310
+  Functions: 5166
+  Symbols:   351
+  CStrings:  372
Symbols:
+ _CNContactEmailAddressesKey
+ _OBJC_CLASS_$_INPersonHandle
+ _objc_release_x9
+ _objc_retain_x26
+ _objc_retain_x9
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_asyncLet_get_throwing
- _MDItemPhotosLocationKeywords
CStrings:
+ "\" && FieldMatch("
+ "GLPMailHydrationAdapter.glp"
+ "PreExtractedEvent"
+ "PreExtractedEventLookup.fetch"
+ "PreExtractedEventLookup.fetchEvents"
+ "[%s.%s]: Failed to donate %ld remote entities to cache: %{sensitive}@"
+ "[%s.%s]: GLP fetch failed, falling back to Spotlight for %ld entities"
+ "[%s.%s]: GLP hydration failed for %{sensitive}s: %{public}s"
+ "[%s.%s]: GLP resolved %ld/%ld mail entities"
+ "[%s.%s]: GLP returned 0 items for %ld requested"
+ "[%s.%s]: GLP search failed: %{public}s [%{public}s %{public}ld]"
+ "[%s.%s]: No GLP match for %{sensitive}s"
+ "[%s.%s]: Remote batch hydration failed for %ld identifiers: %{sensitive}@"
+ "[%s.%s]: Remote hydration cache hit for %s"
+ "[PreExtractedEventLookup] Enriching %{public}ld eligible entities"
+ "[PreExtractedEventLookup] Found events for %{public}ld/%{public}ld entities"
+ "[PreExtractedEventLookup] No events found for %{public}ld external IDs"
+ "[PreExtractedEventLookup] Spotlight query failed: %{public}s [%{public}s %{public}ld]"
+ "_kMDItemBundleID == \""
+ "cachedRemoteEntities(for:)"
+ "createService(cachePolicy:toolbox:entityChunkSize:enrichers:spotlightPreferredBundleIDs:existingSessionHolder:specProvider:appExclusionService:remoteEntityHydrator:)"
+ "donateRemoteEntities(_:)"
+ "eventCustomerNames"
+ "eventEndDateTimeZone"
+ "eventEndLocationAddress"
+ "eventEndLocationName"
+ "eventFlightArrivalAirportCode"
+ "eventFlightCarrierCode"
+ "eventFlightConfirmationNumber"
+ "eventFlightDepartureAirportCode"
+ "eventFlightDesignator"
+ "eventFlightNumber"
+ "eventReservationId"
+ "eventSourceBundleIdentifier"
+ "eventStartDateTimeZone"
+ "eventStartLocationAddress"
+ "eventStartLocationName"
+ "eventTrackingNumber"
+ "fetchEvents(forExternalIds:)"
+ "hydrateRemoteEntities(_:)"
+ "kMDItemEndDateTimeZone"
+ "kMDItemEventCustomerNames"
+ "kMDItemEventEndLocationAddress"
+ "kMDItemEventEndLocationName"
+ "kMDItemEventFlightArrivalAirportCode"
+ "kMDItemEventFlightCarrierCode"
+ "kMDItemEventFlightConfirmationNumber"
+ "kMDItemEventFlightDepartureAirportCode"
+ "kMDItemEventFlightDesignator"
+ "kMDItemEventFlightNumber"
+ "kMDItemEventName"
+ "kMDItemEventProvider"
+ "kMDItemEventReservationID"
+ "kMDItemEventSourceBundleIdentifier"
+ "kMDItemEventStartLocationAddress"
+ "kMDItemEventStartLocationName"
+ "kMDItemEventSubType"
+ "kMDItemEventTrackingNumber"
+ "kMDItemEventType"
+ "kMDItemRelatedUniqueIdentifier"
+ "kMDItemStartDate"
+ "kMDItemStartDateTimeZone"
+ "localHydratedEntities(for:propertyHydrationSpec:traceId:)"
+ "localHydratedEntities(with:traceId:)"
+ "preExtractedEvents"
- "createService(cachePolicy:toolbox:entityChunkSize:enrichers:spotlightPreferredBundleIDs:existingSessionHolder:specProvider:appExclusionService:)"
- "hydratedEntities(for:propertyHydrationSpec:traceId:)"
- "hydratedEntities(with:traceId:)"
```
