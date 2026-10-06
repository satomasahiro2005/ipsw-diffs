## HomeKitNFCBackgroundTagReadingExtension

> `/System/Library/ExtensionKit/Extensions/HomeKitNFCBackgroundTagReadingExtension.appex/HomeKitNFCBackgroundTagReadingExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4490` | `0x3684` | **`-0xe0c`** |
| `__TEXT.__auth_stubs` | `0x7a0` | `0x5d0` | **`-0x1d0`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x140` | **`-0x140`** |
| `__DATA_CONST.__auth_got` | `0x3d8` | `0x2f0` | **`-0xe8`** |
| `__TEXT.__oslogstring` | `0x1e1` | `0x111` | **`-0xd0`** |
| `__TEXT.__objc_methname` | `0x39b` | `0x2dc` | **`-0xbf`** |
| `__DATA_CONST.__const` | `0x1a8` | `0x130` | **`-0x78`** |
| `__DATA.__data` | `0x180` | `0x110` | **`-0x70`** |
| `__DATA.__objc_selrefs` | `0x1c8` | `0x178` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0x167` | `0x11f` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0xdb` | `0x9b` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x90` | `0x58` | **`-0x38`** |
| `__DATA.__objc_const` | `0x268` | `0x248` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x22c` | `0x214` | **`-0x18`** |
| `__TEXT.__objc_classname` | `0x2b` | `0x16` | **`-0x15`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x20` | **`-0x10`** |
| `__TEXT.__const` | `0x11a` | `0x10a` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x118` | `0x108` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x10` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1484.2.0.0.0
+1490.2.0.1.1

-  Functions: 56
-  Symbols:   97
-  CStrings:  103
+  Functions: 45
+  Symbols:   73
+  CStrings:  85
Symbols:
+ _objc_release_x27
- _HMDNFCTagXPCMachServiceName
- _NSCocoaErrorDomain
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_CLASS_$_NSXPCInterface
- __Block_copy
- __Block_release
- __NSConcreteStackBlock
- _dispatch_semaphore_create
- _objc_opt_self
- _objc_release
- _objc_release_x23
- _objc_release_x25
- _objc_release_x8
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x25
- _swift_deallocObject
- _swift_dynamicCast
- _swift_errorRelease
- _swift_errorRetain
- _swift_getErrorValue
- _swift_getObjCClassMetadata
- _swift_release_x25
- _swift_retain_x2
- _swift_retain_x20
CStrings:
- "Failed to obtain XPC remote proxy"
- "HMDNFCTagXPCProtocol"
- "XPC error forwarding NFC tag: %{public}s"
- "XPC to homed rejected (NSCocoaErrorDomain 4099 — entitlement mismatch)."
- "code"
- "domain"
- "homed reply error: %{public}s"
- "initWithMachServiceName:options:"
- "interfaceWithProtocol:"
- "invalidate"
- "localizedDescription"
- "processTagInfos:reply:"
- "remoteObjectProxyWithErrorHandler:"
- "resume"
- "setRemoteObjectInterface:"
- "v16@?0@\"NSError\"8"
- "v32@0:8@\"NSArray\"16@?<v@?@\"NSError\">24"
- "v32@0:8@16@?24"
```
