## FMFCore

> `/System/Library/PrivateFrameworks/FMFCore.framework/FMFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e5e4` | `0x12eb14` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0x5bce` | `0x5c9e` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x8b11` | `0x8b89` | **`+0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x828` | `0x870` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x4450` | `0x4490` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x3890` | `0x3860` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x1174` | `0x11a4` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xcc00` | `0xcc20` | **`+0x20`** |
| `__DATA.__data` | `0x1780` | `0x17a0` | **`+0x20`** |
| `__TEXT.__const` | `0x9e08` | `0x9e18` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x35fd` | `0x360d` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3974` | `0x3980` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1678` | `0x1670` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1060` | `0x1068` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x24ef` | `0x24f1` | **`+0x2`** |

### Other Changes

```diff

-467.30.5.16.4
+469.30.6.7.4

-  Functions: 4943
+  Functions: 4953
Symbols:
+ _OBJC_CLASS_$_NSThread
- _objc_retain_x11
CStrings:
+ "*** FMFServerInteractionController: received response"
+ "FMFInitRefreshClientResponse: initialized with coder"
+ "FMFMyLocationResponse: initialized with coder"
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
- "*** FMFServerInteractionController: received response?: %s"
- "FMFInitRefreshClientResponse: initialized with coder %s"
- "FMFMyLocationResponse: initialized with coder %s"
- "FMReverseGeocodingCache: Geocoding error: %s for request: %s"
- "FMReverseGeocodingCache: Using cached request for %s due to location distance throttling - distance: %f, limit: %f -> %s."
```
