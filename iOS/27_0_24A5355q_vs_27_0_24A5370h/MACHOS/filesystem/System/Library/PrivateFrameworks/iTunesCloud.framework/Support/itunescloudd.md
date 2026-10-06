## itunescloudd

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x148a28` | `0x1491fc` | **`+0x7d4`** |
| `__TEXT.__objc_methname` | `0x22952` | `0x22a5e` | **`+0x10c`** |
| `__TEXT.__oslogstring` | `0x2b0b2` | `0x2b1bd` | **`+0x10b`** |
| `__TEXT.__cstring` | `0x117e0` | `0x11867` | **`+0x87`** |
| `__TEXT.__objc_stubs` | `0x15ba0` | `0x15c00` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0xc860` | `0xc8a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x6798` | `0x67b8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb954` | `0xb974` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1100` | `0x1110` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1950` | `0x1960` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3c90` | `0x3ca0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xcb8` | `0xcc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.100.55.0.0
+4026.100.69.0.0

-  Functions: 5312
-  Symbols:   1010
-  CStrings:  9457
+  Functions: 5316
+  Symbols:   1013
+  CStrings:  9471
Symbols:
+ _ICCloudAvailabilityControllerHasProperNetworkConditionsToShowCloudMediaDidChangeNotification
+ __xpc_type_data
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
- _objc_release_x2
CStrings:
+ "Affected bundleIDs:%{public}@, registration:%{BOOL}u"
+ "ApplicationRegistered"
+ "ApplicationUnregistered"
+ "Failed to deserialize trusted UserInfo for %{public}@: %{public}@"
+ "LaunchServices"
+ "Received notification with invalid event name"
+ "Received trusted distributed notification: %{public}@"
+ "UserInfo is not of type correct type OR is NULL"
+ "_didReceiveTrustedDistributedNotification:withStreamEvent:"
+ "_handleTrustedApplicationRegistration:notificationName:streamEvent:"
+ "_hasProperNetworkConditionsToShowCloudMediaDidChangeNotification:"
+ "com.apple.distnoted.matching.trusted"
+ "dataWithBytesNoCopy:length:freeWhenDone:"
+ "importOriginalArtworkFromFileURL:withArtworkToken:artworkType:sourceType:mediaType:variantType:shouldPerformColorAnalysis:qualityOfService:completion:"
+ "importOriginalArtworkFromImageData:withArtworkToken:artworkType:sourceType:mediaType:variantType:shouldPerformColorAnalysis:qualityOfService:completion:"
+ "restricted_distributed_notifications"
- "importOriginalArtworkFromFileURL:withArtworkToken:artworkType:sourceType:mediaType:variantType:shouldPerformColorAnalysis:completion:"
- "importOriginalArtworkFromImageData:withArtworkToken:artworkType:sourceType:mediaType:variantType:shouldPerformColorAnalysis:completion:"
```
