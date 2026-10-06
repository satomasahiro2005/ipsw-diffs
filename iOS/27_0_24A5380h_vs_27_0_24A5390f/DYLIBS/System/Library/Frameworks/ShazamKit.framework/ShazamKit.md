## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/ShazamKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1578` | `0xa172c` | **`+0x1b4`** |
| `__AUTH_CONST.__objc_const` | `0x9dd8` | `0x9f08` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x50f8` | `0x5170` | **`+0x78`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x38c0` | `0x38a0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2508` | `0x2518` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3a8b` | `0x3a9b` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1441` | `0x1431` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x34d8` | `0x34e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4dc` | `0x4e4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x860` | `0x868` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x368` | `0x370` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x250` | `0x258` | **`+0x8`** |

### Other Changes

```diff

-427.0.40.0.0
+427.0.44.0.0

-  Functions: 3643
-  Symbols:   5117
+  Functions: 3651
+  Symbols:   5136
Symbols:
+ +[SHMediaItem isAddedToLibraryForIdentifier:]
+ +[SHMediaItemDaemonConnection fetchMediaItemForIdentifier:]
+ +[SHMediaItemDaemonConnection fetchMediaItemForIdentifier:completionHandler:]
+ +[SHPreRecordingRequest supportsSecureCoding]
+ -[SHPreRecordingRequest .cxx_destruct]
+ -[SHPreRecordingRequest encodeWithCoder:]
+ -[SHPreRecordingRequest initWithCoder:]
+ -[SHPreRecordingRequest initWithRequestID:preferredInputAudioRoute:]
+ -[SHPreRecordingRequest preferredInputAudioRoute]
+ -[SHPreRecordingRequest requestID]
+ -[SHShazamKitServiceConnection mediaItemForIdentifier:completionHandler:]
+ -[SHShazamKitServiceConnection prepareMatcherForRequest:completionHandler:]
+ -[SHShazamKitServiceConnection synchronouslyFetchMediaItemForIdentifier:completionHandler:]
+ _OBJC_CLASS_$_SHPreRecordingRequest
+ _OBJC_IVAR_$_SHPreRecordingRequest._preferredInputAudioRoute
+ _OBJC_IVAR_$_SHPreRecordingRequest._requestID
+ _OBJC_METACLASS_$_SHPreRecordingRequest
+ __OBJC_$_CLASS_METHODS_SHPreRecordingRequest
+ __OBJC_$_CLASS_PROP_LIST_SHPreRecordingRequest
+ __OBJC_$_INSTANCE_METHODS_SHPreRecordingRequest
+ __OBJC_$_INSTANCE_VARIABLES_SHPreRecordingRequest
+ __OBJC_$_PROP_LIST_SHPreRecordingRequest
+ __OBJC_CLASS_PROTOCOLS_$_SHPreRecordingRequest
+ __OBJC_CLASS_RO_$_SHPreRecordingRequest
+ __OBJC_METACLASS_RO_$_SHPreRecordingRequest
+ ___59+[SHMediaItemDaemonConnection fetchMediaItemForIdentifier:]_block_invoke
+ ___73-[SHShazamKitServiceConnection mediaItemForIdentifier:completionHandler:]_block_invoke
+ ___75-[SHShazamKitServiceConnection prepareMatcherForRequest:completionHandler:]_block_invoke
+ ___91-[SHShazamKitServiceConnection synchronouslyFetchMediaItemForIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e33_v24?0"SHMediaItem"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32r_e33_v24?0"SHMediaItem"8"NSError"16lr32l8
- +[SHMediaItemDaemonConnection fetchRawSongResponseDataUsingMediaItemIdentifier:]
- +[SHMediaItemDaemonConnection fetchRawSongResponseDataUsingMediaItemIdentifier:completionHandler:]
- -[SHShazamKitServiceConnection fetchRawSongResponseDataForMediaItemIdentifier:completionHandler:]
- -[SHShazamKitServiceConnection prepareMatcherForRequestID:completionHandler:]
- -[SHShazamKitServiceConnection synchronouslyFetchRawSongResponseDataForMediaItemIdentifier:completionHandler:]
- GCC_except_table40
- ___110-[SHShazamKitServiceConnection synchronouslyFetchRawSongResponseDataForMediaItemIdentifier:completionHandler:]_block_invoke
- ___77-[SHShazamKitServiceConnection prepareMatcherForRequestID:completionHandler:]_block_invoke
- ___80+[SHMediaItemDaemonConnection fetchRawSongResponseDataUsingMediaItemIdentifier:]_block_invoke
- ___97-[SHShazamKitServiceConnection fetchRawSongResponseDataForMediaItemIdentifier:completionHandler:]_block_invoke
- ___block_descriptor_40_e8_32r_e28_v24?0"NSData"8"NSError"16lr32l8
- ___block_descriptor_48_e8_32bs40w_e28_v24?0"NSData"8"NSError"16lw40l8s32l8
CStrings:
+ "Error fetching media item: %@"
+ "[0-9]+x[0-9]+(?=[^/]*$)"
+ "v24@?0@\"SHMediaItem\"8@\"NSError\"16"
- "Error fetching raw response data: %@"
- "[0-9]+x[0-9]+"
- "v24@?0@\"NSData\"8@\"NSError\"16"
```
