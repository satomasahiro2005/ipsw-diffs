## gamesaved

> `/usr/libexec/gamesaved`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30a4c` | `0x31c5c` | **`+0x1210`** |
| `__DATA_CONST.__const` | `0xe40` | `0xfa8` | **`+0x168`** |
| `__TEXT.__objc_methtype` | `0x66b` | `0x53b` | **`-0x130`** |
| `__DATA.__objc_data` | `0x430` | `0x4e0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x716` | `0x7b8` | **`+0xa2`** |
| `__TEXT.__eh_frame` | `0x2130` | `0x21c8` | **`+0x98`** |
| `__DATA.__data` | `0x1018` | `0x10a8` | **`+0x90`** |
| `__DATA.__objc_const` | `0x1548` | `0x14d0` | **`-0x78`** |
| `__TEXT.__swift5_capture` | `0x340` | `0x394` | **`+0x54`** |
| `__TEXT.__objc_methname` | `0xf5d` | `0xfad` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xb08` | `0xb58` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xedd` | `0xf1d` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x830` | `0x864` | **`+0x34`** |
| `__TEXT.__objc_classname` | `0x2ba` | `0x2ea` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x360` | `0x390` | **`+0x30`** |
| `__TEXT.__const` | `0xfd8` | `0xff8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x57a` | `0x59a` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xbe0` | `0xc00` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x46c` | `0x47c` | **`+0x10`** |
| `__DATA.__common` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x248` | `0x24c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xa4` | `0xa8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xe0` | `0xe4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-102.0.4.0.0
+102.1.2.0.0

-  Functions: 680
-  Symbols:   467
-  CStrings:  351
+  Functions: 712
+  Symbols:   470
+  CStrings:  354
Symbols:
+ _$s10ObjectiveC8SelectorVMn
+ _OBJC_CLASS_$_FPXPCAutomaticErrorProxy
+ _OBJC_METACLASS_$_FPXPCAutomaticErrorProxy
CStrings:
+ "@\"NSProgress\"24@0:8@?<v@?@\"NSError\">16"
+ "@24@0:8@?16"
+ "@24@0:8^{_NSZone=}16"
+ "@52@0:8@16@24@32@40i48"
+ "@60@0:8@16@24@32@40i48@?52"
+ "@68@0:8@16@24@32@40i48@?52@?60"
+ "@?<v@?@\"FPXPCAutomaticErrorProxy\"@\"<NSCopying>\">32@?0@\"FPXPCAutomaticErrorProxy\"8:16@\"<NSCopying>\"24"
+ "Error connecting to the iWork collaboration service"
+ "Error creating the iWork collaboration proxy"
+ "GSFileProvideriWorkCollaboration"
+ "NSCopying"
+ "_TtC9gamesaved19AutomaticErrorProxy"
+ "com.apple.iWorkCollaboration"
+ "copyWithZone:"
+ "fetchLatestRevision(over:)"
+ "fetchLatestRevisionWithCompletionHandler:"
+ "iWork Collaboration Proxy"
+ "initWithConnection:protocol:orError:name:requestPid:"
+ "initWithConnection:protocol:orError:name:requestPid:requestWillBegin:"
+ "initWithConnection:protocol:orError:name:requestPid:requestWillBegin:requestDidBegin:"
+ "sanitizeErrors"
+ "v24@?0@\"FPXPCAutomaticErrorProxy\"8@\"<NSCopying>\"16"
+ "v40@?0@\"FPXPCAutomaticErrorProxy\"8:16@\"<NSCopying>\"24@\"NSProgress\"32"
- "@\"NSProgress\"40@0:8@\"NSSecurityScopedURLWrapper\"16@\"NSFileProviderItemVersion\"24@?<v@?@\"NSFileProviderItemVersion\"@\"NSError\">32"
- "@\"NSProgress\"48@0:8@\"NSSecurityScopedURLWrapper\"16@\"NSFileProviderItemVersion\"24Q32@?<v@?@\"NSFileProviderItemVersion\"@\"NSError\">40"
- "@40@0:8@16@24@?32"
- "@48@0:8@16@24Q32@?40"
- "Error connecting to DocServerlessInterface"
- "ICDFileProviderClientSideCollaborationProtocol"
- "calculateCollaborationVersionForContents:reply:"
- "com.apple.CloudDocs.private.ClientSideCollaboration"
- "extractEtagsFromBaseVersion:withReply:"
- "fetchLatestRevisionIntoURL:reply:"
- "fetchLatestRevisionWithReply:"
- "uploadContents:baseVersion:options:reply:"
- "uploadContents:baseVersion:reply:"
- "v24@0:8@?16"
- "v24@0:8@?<v@?@\"ICDCollaborationVersion\"@\"NSFileProviderItemVersion\"@\"NSError\">16"
- "v32@0:8@\"NSFileProviderItemVersion\"16@?<v@?@\"NSString\"@\"NSString\"@\"NSError\">24"
- "v32@0:8@\"NSSecurityScopedURLWrapper\"16@?<v@?@\"ICDCollaborationVersion\"@\"NSError\">24"
- "v32@0:8@\"NSSecurityScopedURLWrapper\"16@?<v@?@\"NSURL\"@\"NSFileProviderItemVersion\"@\"NSError\">24"
- "v32@0:8@16@?24"
- "v32@?0@\"ICDCollaborationVersion\"8@\"NSFileProviderItemVersion\"16@\"NSError\"24"
```
