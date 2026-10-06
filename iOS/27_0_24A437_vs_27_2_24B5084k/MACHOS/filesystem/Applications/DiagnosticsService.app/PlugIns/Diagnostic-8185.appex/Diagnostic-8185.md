## Diagnostic-8185

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8185.appex/Diagnostic-8185`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2508` | `0x18b8` | **`-0xc50`** |
| `__TEXT.__objc_stubs` | `0x920` | `0x460` | **`-0x4c0`** |
| `__TEXT.__objc_methname` | `0xadc` | `0x8d2` | **`-0x20a`** |
| `__DATA_CONST.__cfstring` | `0xa80` | `0x920` | **`-0x160`** |
| `__TEXT.__objc_methtype` | `0x27c` | `0x15f` | **`-0x11d`** |
| `__TEXT.__cstring` | `0x5dc` | `0x4ff` | **`-0xdd`** |
| `__DATA.__data` | `0x180` | `0xc0` | **`-0xc0`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x2a0` | **`-0xc0`** |
| `__TEXT.__auth_stubs` | `0x230` | `0x1a0` | **`-0x90`** |
| `__DATA_CONST.__objc_dictobj` | `0xa0` | `0x28` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x344` | `0x2d4` | **`-0x70`** |
| `__DATA.__objc_const` | `0x7c8` | `0x770` | **`-0x58`** |
| `__DATA_CONST.__auth_got` | `0x120` | `0xd8` | **`-0x48`** |
| `__DATA_CONST.__objc_intobj` | `0x138` | `0xf0` | **`-0x48`** |
| `__DATA_CONST.__got` | `0x98` | `0x60` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x201` | `0x1ca` | **`-0x37`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0xf0` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x69` | `0x3a` | **`-0x2f`** |
| `__DATA_CONST.__const` | `0x28` | `—` | **`-0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x10` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__const` | `0x68` | `0x60` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 38
-  Symbols:   72
-  CStrings:  277
+  Functions: 36
+  Symbols:   56
+  CStrings:  230
Symbols:
- _MGGetBoolAnswer
- _OBJC_CLASS_$_NSBundle
- _OBJC_CLASS_$_NSData
- _OBJC_CLASS_$_NSMutableDictionary
- _OBJC_CLASS_$_NSNumber
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_CLASS_$_NSXPCInterface
- __NSConcreteStackBlock
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _dispatch_time
- _objc_alloc_init
- _objc_release_x28
- _objc_retain_x1
- _objc_retain_x21
CStrings:
+ "fdrErrorCode"
- "CFBundleShortVersionString"
- "CRAttestationProtocol"
- "CoreRepairHelperProtocol"
- "DisplayMaxDuration"
- "InDiagnosticsMode"
- "InternalBuild"
- "Missing required SPC code"
- "Not in diagnostics mode"
- "Operation timed out"
- "Result %@"
- "UseSOCKSHost"
- "UseSOCKSPort"
- "addEntriesFromDictionary:"
- "challengeComponentsWith:withReply:"
- "com.apple.corerepair"
- "daemonControl:withReply:"
- "data"
- "decompressPearlFramesWithReply:"
- "ensurePrebootPathIsWritable:"
- "getStrongComponentsWithReply:"
- "initWithBase64EncodedString:options:"
- "initWithMachServiceName:options:"
- "intValue"
- "interfaceWithProtocol:"
- "intersectSet:"
- "invalidate"
- "mainBundle"
- "mutableCopy"
- "numberWithBool:"
- "objectForInfoDictionaryKey:"
- "remoteObjectProxy"
- "resume"
- "seal:withReply:"
- "selected PartSPCs:%@"
- "setObject:forKeyedSubscript:"
- "setRemoteObjectInterface:"
- "statusCode"
- "updateDATFirmware:withReply:"
- "v16@?0@\"NSDictionary\"8"
- "v24@0:8@?16"
- "v24@0:8@?<v@?@\"NSError\">16"
- "v24@0:8@?<v@?B@\"NSArray\"@\"NSError\">16"
- "v32@0:8@\"NSArray\"16@?<v@?B@\"NSArray\"@\"NSError\">24"
- "v32@0:8@\"NSDictionary\"16@?<v@?@\"NSDictionary\">24"
- "v32@0:8@\"NSDictionary\"16@?<v@?@\"NSError\">24"
- "v32@0:8@\"NSDictionary\"16@?<v@?B@\"NSDictionary\">24"
- "v32@0:8@16@?24"
- "verifyPSD3WithReply:"
```
