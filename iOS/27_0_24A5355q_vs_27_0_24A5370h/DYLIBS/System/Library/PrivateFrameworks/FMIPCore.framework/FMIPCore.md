## FMIPCore

> `/System/Library/PrivateFrameworks/FMIPCore.framework/FMIPCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6ec4` | `0x1c71e4` | **`+0x320`** |
| `__DATA.__bss` | `0x15680` | `0x15800` | **`+0x180`** |
| `__TEXT.__const` | `0x13aec` | `0x13c6c` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0xa8f0` | `0xa9f0` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x12be9` | `0x12c91` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0x54d1` | `0x5551` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x6000` | `0x607c` | **`+0x7c`** |
| `__TEXT.__constg_swiftt` | `0x68f0` | `0x690c` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0xd38` | `0xd50` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x42b3` | `0x42c1` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0xea4` | `0xeb0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1408` | `0x1410` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x15d0` | `0x15d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4e38` | `0x4e30` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x5f0` | `0x5f4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-467.30.5.16.4
+469.30.6.7.4

-  Functions: 8821
+  Functions: 8830

-  CStrings:  1414
+  CStrings:  1415
CStrings:
+ "FMIPBeaconRefreshingController: auto refreshing set to %{bool}d"
+ "FMReverseGeocodingCache: Already loading address for same geohash as %s, ignoring."
+ "FMReverseGeocodingCache: Attaching to existing operation for %s"
+ "FMReverseGeocodingCache: Cached request for %s is older than the 30s."
+ "FMReverseGeocodingCache: Current throughput: %f requests per second."
+ "FMReverseGeocodingCache: Existing operation completed, notifying duplicate %s isNil=%{bool}d"
+ "FMReverseGeocodingCache: Geocoding error for %s: %s"
+ "FMReverseGeocodingCache: Loading declined, already processed similar location for %s"
+ "FMReverseGeocodingCache: Loading declined, already processing similar location for %s"
+ "FMReverseGeocodingCache: Loading new address for %s"
+ "FMReverseGeocodingCache: No cached request for %s."
+ "FMReverseGeocodingCache: No map items received for %s"
+ "FMReverseGeocodingCache: Total operations processed: %ld."
+ "FMReverseGeocodingCache: Using cached request %s based on geoHash %s"
+ "FMReverseGeocodingCache: Using cached request for %s due to location distance throttling - distance: %f, limit: %f"
+ "FMReverseGeocodingCache: address received for %s"
+ "video"
- "%s: Already loading address for same geohash as %s, ignoring."
- "%s: Attaching to an existing operation: %s, source: %s"
- "%s: Cached request for %s is older than the 30s."
- "%s: Current throughput: %f requests per second."
- "%s: Existing operation completed, notifying the duplicate: %s - %s"
- "%s: Loading declined, we are already processing similar location: %s"
- "%s: Loading declined, we have already processed similar location: %s"
- "%s: Loading new address for %s"
- "%s: No cached request for %s."
- "%s: No map items received for request: %s"
- "%s: Total operations processed: %ld."
- "%s: Using cached request %s based on geoHash %s -> %s."
- "%s: address received for request: %s - %s"
- "FMIPBeaconRefreshingController: auto refreshing set to: %s"
- "FMReverseGeocodingCache: Geocoding error: %s for request: %s"
- "FMReverseGeocodingCache: Using cached request for %s due to location distance throttling - distance: %f, limit: %f -> %s."
```
