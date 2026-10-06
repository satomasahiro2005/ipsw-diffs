## shazamd

> `/System/Library/Frameworks/ShazamKit.framework/shazamd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f59c` | `0x4f7cc` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0xd160` | `0xd1a0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x303d` | `0x306a` | **`+0x2d`** |
| `__DATA.__objc_selrefs` | `0x3b20` | `0x3b38` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xbc8` | `0xbe0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14d0` | `0x14e0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x4d63` | `0x4d55` | **`-0xe`** |
| `__DATA_CONST.__const` | `0x1980` | `0x1978` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x910` | `0x918` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x615c` | `0x6164` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x10d4d` | `0x10d4e` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-427.0.40.0.0
+427.0.44.0.0

-  Functions: 1883
-  Symbols:   445
-  CStrings:  3918
+  Functions: 1885
+  Symbols:   446
+  CStrings:  3921
Symbols:
+ _OBJC_CLASS_$_UNNotificationIcon
CStrings:
+ "@\"SHPreRecordingRequest\""
+ "Fetching media item from data store for mediaItem ID: %@"
+ "No data store to retrieve media item."
+ "T@\"SHPreRecordingRequest\",R,N,V_request"
+ "fetchMediaItemForLibraryTrackIdentifier:"
+ "iconForApplicationIdentifier:"
+ "initWithRequest:audioTapProvider:"
+ "mediaItemForIdentifier:"
+ "mediaItemForIdentifier:completionHandler:"
+ "mediaItemValue"
+ "notificationIcon"
+ "prepareMatcherForRequest:completionHandler:"
+ "setIcon:"
+ "v32@0:8@\"NSUUID\"16@?<v@?@\"SHMediaItem\"@\"NSError\">24"
+ "v32@0:8@\"SHPreRecordingRequest\"16@?<v@?>24"
- "Fetching raw song response from data store for mediaItem ID: %@"
- "No data store to retrieve raw song response."
- "T@\"NSUUID\",R,N,V_requestID"
- "_requestID"
- "fetchRawSongResponseDataForLibraryTrackIdentifier:"
- "fetchRawSongResponseDataForMediaItemIdentifier:completionHandler:"
- "initWithRequestID:audioTapProvider:"
- "prepareMatcherForRequestID:completionHandler:"
- "rawSongResponseDataForMediaItemIdentifier:"
- "setResultType:"
- "v32@0:8@\"NSUUID\"16@?<v@?>24"
- "v32@0:8@\"NSUUID\"16@?<v@?@\"NSData\"@\"NSError\">24"
```
