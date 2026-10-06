## pasted

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Support/pasted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c838` | `0x1d1ac` | **`+0x974`** |
| `__TEXT.__objc_methname` | `0x515a` | `0x5331` | **`+0x1d7`** |
| `__TEXT.__objc_stubs` | `0x4520` | `0x4640` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x21a4` | `0x2267` | **`+0xc3`** |
| `__TEXT.__cstring` | `0x1d94` | `0x1e09` | **`+0x75`** |
| `__TEXT.__gcc_except_tab` | `0x714` | `0x778` | **`+0x64`** |
| `__DATA_CONST.__cfstring` | `0x18e0` | `0x1940` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2eb0` | `0x2f00` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1368` | `0x13b0` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0xda6` | `0xdd7` | **`+0x31`** |
| `__TEXT.__objc_methlist` | `0x13d8` | `0x1408` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1400` | `0x1420` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x708` | `0x720` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x178` | `0x180` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0xf0` | `0xf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-9127.0.78.0.0
+9127.0.84.1.102

-  Functions: 510
-  Symbols:   379
-  CStrings:  1367
+  Functions: 514
+  Symbols:   383
+  CStrings:  1387
Symbols:
+ _OBJC_CLASS_$_BKSHIDEventDeferringNamespacePredicate
+ _OBJC_CLASS_$_FBSDisplayMonitor
+ _objc_sync_enter
+ _objc_sync_exit
CStrings:
+ "@\"FBSDisplayMonitor\""
+ "@60@0:8@16B24@28^Q36^q44^@52"
+ "Bundle ID %@ from team %@ is saving pasteboard named %@ attributed to bundle ID %@ from team %@"
+ "Bundle ID %@ saved pasteboard named %@ carrying %lu item(s) stored on behalf of %@. Dropping them."
+ "EmbeddedDisplayDuringMirroring"
+ "NotEmbeddedDisplayDuringMirroring"
+ "TB,N,GisAllowedToSpecifyOriginator,V_allowedToSpecifyOriginator"
+ "_allowedToSpecifyOriginator"
+ "_displayMonitor"
+ "allowedToSpecifyOriginator"
+ "anyContinuityDisplay"
+ "arrayWithCapacity:"
+ "authenticationMessage:matchesDeferringNamespacePredicate:"
+ "com.apple.Pasteboard.specify-originator"
+ "connectedIdentities"
+ "displayMonitor"
+ "initWithNotificationState:changeCount:sharingToken:removedItemUUIDs:"
+ "isAllowedToSpecifyOriginator"
+ "isPasteFromEmbeddedDisplayDuringMirroringForAuthenticationMessage:"
+ "savePasteboard:deviceIslocked:clientInfo:completionBlock:"
+ "setAllowedToSpecifyOriginator:"
+ "setWithCapacity:"
+ "v40@?0Q8q16@\"NSArray\"24@\"NSError\"32"
+ "v44@0:8@16B24@28@?36"
+ "workQueue_savePasteboard:isServerToServerCopy:clientInfo:outNotificationState:outChangeCount:outRemovedItemUUIDs:"
- "@44@0:8@16B24^Q28^q36"
- "initWithNotificationState:changeCount:sharingToken:"
- "savePasteboard:deviceIslocked:completionBlock:"
- "v32@?0Q8q16@\"NSError\"24"
- "workQueue_savePasteboard:isServerToServerCopy:outNotificationState:outChangeCount:"
```
