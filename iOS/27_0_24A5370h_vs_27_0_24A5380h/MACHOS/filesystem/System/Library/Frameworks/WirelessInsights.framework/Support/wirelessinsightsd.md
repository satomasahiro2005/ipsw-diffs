## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33e4d8` | `0x344dfc` | **`+0x6924`** |
| `__TEXT.__objc_stubs` | `0xf580` | `0xf860` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0x2e622` | `0x2e8d2` | **`+0x2b0`** |
| `__TEXT.__objc_methname` | `0x1817c` | `0x183ac` | **`+0x230`** |
| `__DATA_CONST.__got` | `0x12b0` | `0x13e0` | **`+0x130`** |
| `__TEXT.__cstring` | `0x1592b` | `0x15a4b` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x17140` | `0x17258` | **`+0x118`** |
| `__DATA.__objc_selrefs` | `0x43c8` | `0x4478` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x5ce3` | `0x5d63` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x40f0` | `0x416c` | **`+0x7c`** |
| `__TEXT.__const` | `0x17e03` | `0x17e73` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x10350` | `0x103b8` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x2602` | `0x2662` | **`+0x60`** |
| `__DATA.__objc_data` | `0x5528` | `0x5558` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x69e0` | `0x6a10` | **`+0x30`** |
| `__DATA.__data` | `0x6798` | `0x6778` | **`-0x20`** |
| `__DATA.__objc_const` | `0x143f0` | `0x14410` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x45ba` | `0x45da` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x4030` | `0x404c` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0x854` | `0x838` | **`-0x1c`** |
| `__TEXT.__auth_stubs` | `0x4f60` | `0x4f70` | **`+0x10`** |
| `__DATA.__common` | `0x608` | `0x610` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x27c8` | `0x27d0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x29ecc` | `0x29ed0` | **`+0x4`** |
| `__TEXT.__swift5_capture` | `0x1ca4` | `0x1ca8` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x528` | `0x52c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x2d8` | `0x2dc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-341.0.0.0.0
+344.0.0.0.0

+  - /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight

-  Functions: 14348
-  Symbols:   2026
-  CStrings:  10247
+  Functions: 14376
+  Symbols:   2048
+  CStrings:  10291
Symbols:
+ _$sScC6resume8throwingyq_n_tF
+ _CSEventTypeFlight
+ _MDItemBundleID
+ _MDItemEndDate
+ _MDItemEventEndLocationAddressLatitude
+ _MDItemEventEndLocationAddressLongitude
+ _MDItemEventFlightArrivalAirportCode
+ _MDItemEventFlightArrivalAirportLatitude
+ _MDItemEventFlightArrivalAirportLongitude
+ _MDItemEventFlightArrivalDateTime
+ _MDItemEventFlightDepartureAirportCode
+ _MDItemEventFlightDepartureAirportLatitude
+ _MDItemEventFlightDepartureAirportLongitude
+ _MDItemEventFlightDepartureDateTime
+ _MDItemEventSourceBundleIdentifier
+ _MDItemEventStartLocationAddressLatitude
+ _MDItemEventStartLocationAddressLongitude
+ _MDItemEventType
+ _MDItemStartDate
+ _OBJC_CLASS_$_CSSearchQuery
+ _OBJC_CLASS_$_CSSearchQueryContext
+ _OBJC_CLASS_$_CSSearchableItem
CStrings:
+ ", registrationState: "
+ "344"
+ "344~46"
+ "CommCenter flight item is missing required field, skipping"
+ "CommCenter list of flight predictions is nil, aborting"
+ "Converting CommCenter flight item: %{private}@"
+ "Converting flight item: %{private}s"
+ "Failed to fetch flight predictions: %@"
+ "Flight item filtered due to timing (departure time: %s, arrival time: %s, now %s), skipping"
+ "Flight item is missing a required field"
+ "Flight prediction: %s"
+ "Flight query cancelled"
+ "Flight query completed with %ld results: %{private}s"
+ "Flight query error: %@"
+ "Flight search received %ld results"
+ "Received %ld new upcoming flight predictions"
+ "Simulated flight travel end time is in the past, removing"
+ "WirelessInsightsMapsSuggestions"
+ "attributeSet"
+ "com.apple.MobileSMS"
+ "com.apple.Passbook"
+ "com.apple.email.SearchIndexer"
+ "com.apple.mobilemail"
+ "com.microsoft.Office.Outlook"
+ "eventEndLocationAddressLatitude"
+ "eventEndLocationAddressLongitude"
+ "eventSourceBundleIdentifier"
+ "eventStartLocationAddressLatitude"
+ "eventStartLocationAddressLongitude"
+ "flightArrivalAirportCode"
+ "flightArrivalAirportLatitude"
+ "flightArrivalAirportLongitude"
+ "flightArrivalDateTime"
+ "flightDepartureAirportCode"
+ "flightDepartureAirportLatitude"
+ "flightDepartureAirportLongitude"
+ "flightDepartureDateTime"
+ "initWithQueryString:queryContext:"
+ "isCancelled"
+ "setCompletionHandler:"
+ "setFetchAttributes:"
+ "setFoundItemsHandler:"
+ "setMaxAge:"
+ "setMaxCount:"
+ "spUnknown"
+ "spotlightFlightTravelPredictions(atTime:)"
+ "v16@?0@\"NSArray\"8"
- "341"
- "341~13"
- "Simulated flight travel start time is in the past, removing"
```
