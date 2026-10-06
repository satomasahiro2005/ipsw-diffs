## pasted

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Support/pasted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c8e0` | `0x1cd6c` | **`+0x48c`** |
| `__TEXT.__objc_methname` | `0x4fdf` | `0x5179` | **`+0x19a`** |
| `__TEXT.__objc_stubs` | `0x44a0` | `0x4560` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x1c8e` | `0x1d38` | **`+0xaa`** |
| `__TEXT.__oslogstring` | `0x21bc` | `0x2151` | **`-0x6b`** |
| `__TEXT.__gcc_except_tab` | `0x768` | `0x724` | **`-0x44`** |
| `__TEXT.__auth_stubs` | `0xd60` | `0xda0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x2e80` | `0x2eb0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1348` | `0x1378` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xd76` | `0xda6` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x13b0` | `0x13d8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x6c8` | `0x6e8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x18c0` | `0x18e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x480` | `0x4a0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x700` | `0x718` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x174` | `0x178` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-9127.0.66.0.0
+9127.0.71.0.0

-  Functions: 513
-  Symbols:   371
-  CStrings:  1353
+  Functions: 519
+  Symbols:   379
+  CStrings:  1366
Symbols:
+ _PBMetadataAppIntentsPayloadKey
+ _PBMetadataUnmatchedAppEntityPayloadsKey
+ _PBPerformCallback
+ _SBUserNotificationAlternateButtonPresentationStyleKey
+ _SBUserNotificationDefaultButtonPresentationStyleKey
+ _objc_retain_x5
+ _xpc_transaction_begin
+ _xpc_transaction_end
CStrings:
+ "PBItem _saveRepresentationsToBaseURL: requesting data load item=%@ type=%{public}@ rep=%p synchronous=%d"
+ "Synchronous save for pasteboard %@ did not complete inline; treating as a serialize failure."
+ "TB,N,GisAllowedToReadAppEntityData,V_allowedToReadAppEntityData"
+ "_allowedToReadAppEntityData"
+ "_saveRepresentationsToBaseURL:types:fileProtectionType:allowedToCopyOnPaste:synchronous:completionBlock:"
+ "allowedToReadAppEntityData"
+ "com.apple.Pasteboard.read-app-entity-data"
+ "isAllowedToReadAppEntityData"
+ "loadDataWithContext:completion:synchronous:"
+ "loadFileCopyWithContext:completion:synchronous:"
+ "loadOpenInPlaceWithContext:completion:synchronous:"
+ "loadsDataSynchronously"
+ "saveRepresentationsToStorageBaseURL:fileProtectionType:allowedToCopyOnPaste:synchronous:completionBlock:"
+ "serializeToBaseURL: starting _serializeItemRepresentations for pasteboard=%{public}@ itemCollection=%@ items=%lu synchronous=%d"
+ "serializeToBaseURL:isServerToServerCopy:allowedToCopyOnPaste:completion:"
+ "setAllowedToReadAppEntityData:"
+ "setLoadsDataSynchronously:"
+ "v32@?0@\"NSData\"8@\"PBResponseMetadata\"16@\"NSError\"24"
+ "v32@?0@\"NSURL\"8@\"PBResponseMetadata\"16@\"NSError\"24"
+ "v36@?0@\"NSURL\"8B16@\"PBResponseMetadata\"20@\"NSError\"28"
+ "v40@0:8@16B24B28@?32"
+ "v48@0:8@16@24B32B36@?40"
+ "v56@0:8@16@24@32B40B44@?48"
- "PBItem _saveRepresentationsToBaseURL: requesting data load item=%@ type=%{public}@ rep=%p"
- "_saveRepresentationsToBaseURL:types:fileProtectionType:allowedToCopyOnPaste:completionBlock:"
- "loadFileCopyWithCompletion:"
- "loadOpenInPlaceWithCompletion:"
- "saveRepresentationsToStorageBaseURL:fileProtectionType:allowedToCopyOnPaste:completionBlock:"
- "serializeToBaseURL: about to wait on semaphore for pasteboard=%{public}@ itemCollection=%@ (waiting for source data-load replies)"
- "serializeToBaseURL: semaphore signaled for pasteboard=%{public}@ itemCollection=%@ error=%{public}@"
- "serializeToBaseURL: starting _serializeItemRepresentations for pasteboard=%{public}@ itemCollection=%@ items=%lu"
- "v28@?0@\"NSURL\"8B16@\"NSError\"20"
- "v52@0:8@16@24@32B40@?44"
```
