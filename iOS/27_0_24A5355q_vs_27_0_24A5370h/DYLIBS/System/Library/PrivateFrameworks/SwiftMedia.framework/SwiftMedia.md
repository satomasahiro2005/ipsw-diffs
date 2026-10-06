## SwiftMedia

> `/System/Library/PrivateFrameworks/SwiftMedia.framework/SwiftMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45390` | `0x482b0` | **`+0x2f20`** |
| `__DATA.__bss` | `0x1040` | `0x16c0` | **`+0x680`** |
| `__TEXT.__const` | `0x2420` | `0x27b0` | **`+0x390`** |
| `__DATA.__data` | `0x7f8` | `0x9c8` | **`+0x1d0`** |
| `__TEXT.__swift5_reflstr` | `0xbdf` | `0xd0f` | **`+0x130`** |
| `__TEXT.__swift5_typeref` | `0x1142` | `0x1202` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x914` | `0x9c4` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x1ce3` | `0x1c43` | **`-0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x8e0` | `0x970` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x11b8` | `0x1228` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x1d30` | `0x1d98` | **`+0x68`** |
| `__TEXT.__swift5_assocty` | `0x1c8` | `0x228` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x7f8` | `0x7b8` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0xd50` | `0xd88` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x9c` | `0xd0` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x70` | `0x68` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x2e84` | `0x2e7c` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xbc` | `0xc4` | **`+0x8`** |

### Other Changes

```diff

-60.54.1.0.0
+60.59.2.0.0

-  Functions: 1421
-  Symbols:   632
-  CStrings:  129
+  Functions: 1498
+  Symbols:   646
+  CStrings:  131
Symbols:
+ ___swift_memcpy29_8
+ __swiftImmortalRefCount
+ _associated conformance 10SwiftMedia0aB5ErrorV0C4TypeOSHAASQ
+ _associated conformance 10SwiftMedia0aB5ErrorV10Foundation09LocalizedC0AAs0C0
+ _associated conformance So26FigPlaybackItemCreateFlagsVs10SetAlgebraSCSQ
+ _associated conformance So26FigPlaybackItemCreateFlagsVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So26FigPlaybackItemCreateFlagsVs9OptionSetSCSY
+ _associated conformance So26FigPlaybackItemCreateFlagsVs9OptionSetSCs0G7Algebra
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic ShySiG
+ _symbolic ShySiG______t 10SwiftMedia0aB5ErrorV0C4TypeO
+ _symbolic _____ 10SwiftMedia0aB5ErrorV
+ _symbolic _____ 10SwiftMedia0aB5ErrorV0C4TypeO
+ _symbolic _____ So26FigPlaybackItemCreateFlagsV
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____yShySiGG s23_ContiguousArrayStorageC
+ _symbolic _____yShySiG_____G s18_DictionaryStorageC 10SwiftMedia0cD5ErrorV0E4TypeO
+ _symbolic _____ySiG s11_SetStorageC
+ _symbolic _____y_____SSG s18_DictionaryStorageC 10SwiftMedia0cD5ErrorV0E4TypeO
+ _type_layout_string 10SwiftMedia0aB5ErrorV
- _NSOSStatusErrorDomain
- _OBJC_CLASS_$_NSError
- ___swift_memcpy4_4
- _objc_allocWithZone
- _objc_release_x27
- _symbolic _____ So16os_unfair_lock_sV
- _symbolic _____ySbG 15Synchronization5_CellVAARi_zrlE
- _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE So16os_unfair_lock_sV
CStrings:
+ "Calling FigPlayerCreatePlaybackItemFromAsset with flags: "
+ "Cannot find host from URL"
+ "Duplicate UnderlyingErrors for status "
+ "File does not exist"
+ "Media services were reset"
+ "Missing type for category "
+ "Not connected to internet"
+ "Server does not support byte ranges"
+ "Unable to load URL asset"
+ "Unable to parse file"
+ "UnderlyingError not found for status "
+ "Unknown description for status "
+ "Unknown error type for status "
+ "fileDoesNotExist"
+ "fileFailedToParse"
+ "init(player:asset:)"
+ "mediaServicesWereReset"
+ "notConnectedToInternet"
+ "serverDoesNotSupportByteRanges"
+ "urlLoadErrorRequestUnhandled"
- ", Removing playback item error: "
- "Failed to create FigAsset with error "
- "Failed to create FigPlaybackItem with error "
- "Failed to create FigPlayer with error "
- "Failed to insert item into play queue with error: "
- "Failed to remove item from play queue with error: "
- "SwiftMedia/FigPlayerWrapper.swift"
- "_reconfigure(for:playerValues:forceFullReset:)"
- "failed to set AllowsAirPlayVideo to "
- "failed to set AllowsNeroPlayback to "
- "failed to set audioSessionID to "
- "failed to set forwardPlaybackEnd to "
- "failed to set isMuted to "
- "failed to set outputContextID to "
- "failed to set rate with error: "
- "failed to set restrictsAutomaticMediaSelectionToAvailableOfflineOptions to "
- "failed to set reversePlaybackEnd to "
- "failed to set volume to "
```
