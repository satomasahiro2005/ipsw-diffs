## HybridQueryProcessing

> `/System/Library/PrivateFrameworks/HybridQueryProcessing.framework/HybridQueryProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6a24` | `0xde748` | **`+0x7d24`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0xa00` | **`+0x900`** |
| `__DATA_DIRTY.__data` | `0x8e0` | `0x1028` | **`+0x748`** |
| `__TEXT.__const` | `0x353c` | `0x39dc` | **`+0x4a0`** |
| `__TEXT.__oslogstring` | `0x3c82` | `0x40a2` | **`+0x420`** |
| `__AUTH.__data` | `0x570` | `0x208` | **`-0x368`** |
| `__AUTH_CONST.__const` | `0x6628` | `0x6970` | **`+0x348`** |
| `__DATA.__data` | `0xeb0` | `0xc20` | **`-0x290`** |
| `__DATA.__bss` | `0x2930` | `0x27c0` | **`-0x170`** |
| `__TEXT.__eh_frame` | `0x2418` | `0x2584` | **`+0x16c`** |
| `__TEXT.__unwind_info` | `0x1678` | `0x1790` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0xd2c` | `0xe28` | **`+0xfc`** |
| `__TEXT.__swift5_fieldmd` | `0x1120` | `0x1208` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x2053` | `0x2113` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xf50` | `0xfe0` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x1754` | `0x17d4` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xc5b` | `0xcab` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x16c` | `0x1a8` | **`+0x3c`** |
| `__DATA_DIRTY.__common` | `0x40` | `0x70` | **`+0x30`** |
| `__DATA.__common` | `0x88` | `0x59` | **`-0x2f`** |
| `__AUTH_CONST.__auth_got` | `0x1118` | `0x1138` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x120` | `0x13c` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x60` | **`+0x8`** |

### Other Changes

```diff

-57.0.1.0.0
+59.0.1.0.0

+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch

-  Functions: 3584
-  Symbols:   181
-  CStrings:  514
+  Functions: 3698
+  Symbols:   183
+  CStrings:  532
Symbols:
+ _os_variant_has_internal_diagnostics
+ _swift_deallocPartialClassInstance
CStrings:
+ "DATE"
+ "Duplicate values for key: '"
+ "Failed to load time_sensitive_tokens.json: %{public}s"
+ "Fatal error"
+ "HQP Planner Event: location search \"%s\" → customerAddresses"
+ "HQP Planner Event: person search \"%s\" → customerNames, contactPersonNames"
+ "HQP Planner Flight: person search \"%s\" → passengerNames"
+ "HQP Planner HotelReservation: location search \"%s\" → hotelCity, hotelRegion, hotelCountry, hotelAddress, hotelStreet, hotelAddressSynonyms"
+ "HQP Planner HotelReservation: person search \"%s\" → underName"
+ "HQP Planner IdentificationDocument: person search \"%s\" → subjectName, underName"
+ "HQP Planner MailCategory: \"transactions\" category detected but filtering is a no-op; skipping predicate"
+ "HQP Planner MailCategory: \"updates\" category detected but filtering is a no-op; skipping predicate"
+ "HQP Planner RestaurantReservation: location search \"%s\" → restaurantCity, restaurantRegion, restaurantCountry, restaurantAddress, restaurantStreet, restaurantAddressSynonyms"
+ "HQP Planner RestaurantReservation: person search \"%s\" → underName"
+ "Swift/NativeDictionary.swift"
+ "isQueryTimeSensitive"
+ "isU2OnlyFallback"
+ "time_sensitive_tokens"
```
