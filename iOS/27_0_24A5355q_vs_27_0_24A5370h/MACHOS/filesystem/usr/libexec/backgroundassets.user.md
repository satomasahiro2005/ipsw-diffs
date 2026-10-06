## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59010` | `0x59a84` | **`+0xa74`** |
| `__TEXT.__oslogstring` | `0x664c` | `0x6b73` | **`+0x527`** |
| `__DATA.__objc_const` | `0x58c8` | `0x5a10` | **`+0x148`** |
| `__TEXT.__objc_stubs` | `0x7720` | `0x7820` | **`+0x100`** |
| `__DATA.__data` | `0x1230` | `0x12e8` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x9b8e` | `0x9c3e` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x1e88` | `0x1f20` | **`+0x98`** |
| `__DATA.__bss` | `0x2a10` | `0x2a90` | **`+0x80`** |
| `__TEXT.__cstring` | `0x412d` | `0x4180` | **`+0x53`** |
| `__DATA.__objc_data` | `0x11c0` | `0x1210` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x1910` | **`+0x50`** |
| `__TEXT.__const` | `0x1a88` | `0x1ad8` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2170` | `0x21b0` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x80e` | `0x84e` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x3ec` | `0x428` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x34e4` | `0x351c` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x6c4` | `0x6f4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1420` | `0x1450` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xc70` | `0xc98` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x528` | `0x550` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x2480` | `0x24a0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xe0` | `0x100` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x513` | `0x531` | **`+0x1e`** |
| `__DATA_CONST.__auth_ptr` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x148` | `0x14c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x64` | `0x68` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-268.0.0.502.1
+271.0.0.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 1927
-  Symbols:   694
-  CStrings:  2579
+  Functions: 1944
+  Symbols:   701
+  CStrings:  2604
Symbols:
+ _$s15Synchronization5MutexVMn
+ _$sytN
+ _swift_release_n
+ _swift_release_x25
+ _swift_release_x26
+ _swift_retain_x24
+ _swift_retain_x26
+ _swift_runtimeSupportsNoncopyableTypes
- _OBJC_CLASS_$_NSMutableURLRequest
CStrings:
+ "*."
+ "<Defaults Provider | Defaults: "
+ "A client object couldn’t be created for process %d."
+ "B24@?0@\"NSURLQueryItem\"8@\"NSDictionary\"16"
+ "BAInfoDictionary"
+ "BAManagedManifestURL"
+ "Client \"%{public}@\" attempted to schedule a BAManifestDownload, which is reserved for daemon use."
+ "Client \"%{public}@\" attempted to start a BAManifestDownload as foreground, which is reserved for daemon use."
+ "Init bundle ID: %{public}s app group ID: %{public}s defaults provider: %{public}s source: %{public}s managed: %{bool}d helper: %{public}s"
+ "Init bundle ID: %{public}s defaults provider: %{public}s source: %{public}s managed: %{bool}d helper: %{public}s"
+ "Initializing a fallback defaults provider…"
+ "Rejecting malformed wildcard \"%{public}@\"."
+ "Rejecting wildcard \"%{public}@\" — wildcards must have the form \"*.suffix\"."
+ "The application with the identifier “%{public}@” lacks a string team identifier in its connection request."
+ "The extension-point identifier, “%{public}@”, of the application extension with the identifier “%{public}@” doesn’t match the expected extension-point identifier, “%{public}@”."
+ "The manifest URL for the application with the identifier “%{public}@” was rewritten as “%{public}@”."
+ "The team identifier, “%{public}@”, in a connection request from the application with the identifier “%{public}@” doesn’t match the recorded team identifier, “%{public}@”, for that application."
+ "URLByAddingPlatformQueryItemToURL:applicationRecord:"
+ "_TtC21backgroundassets_user16DefaultsProvider"
+ "_addValidDomain:"
+ "_addValidWildcard:"
+ "defaults"
+ "defaultsProvider"
+ "filterUsingPredicate:"
+ "initWithExtensionIdentity:"
+ "name"
+ "platformStringForApplicationRecord:"
+ "predicateWithBlock:"
+ "queryItems"
+ "rangeOfString:options:range:"
- "Defaults"
- "ManagedBackgroundAssets"
- "appGroupID"
- "arrayWithArray:"
- "setExtensionIdentity:"
```
