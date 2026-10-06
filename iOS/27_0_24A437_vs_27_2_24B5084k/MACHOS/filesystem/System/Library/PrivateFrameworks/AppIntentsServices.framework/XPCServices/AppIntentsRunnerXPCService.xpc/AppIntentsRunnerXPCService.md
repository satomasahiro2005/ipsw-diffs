## AppIntentsRunnerXPCService

> `/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cf14` | `0x3ef4c` | **`+0x2038`** |
| `__TEXT.__eh_frame` | `0x3f68` | `0x42f0` | **`+0x388`** |
| `__TEXT.__const` | `0x20d8` | `0x21f8` | **`+0x120`** |
| `__TEXT.__objc_methtype` | `0xa9c` | `0xb6c` | **`+0xd0`** |
| `__TEXT.__objc_methname` | `0x135f` | `0x141d` | **`+0xbe`** |
| `__TEXT.__objc_stubs` | `0x860` | `0x900` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1580` | `0x1600` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x850` | `0x8a0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x9a1` | `0x9f1` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2120` | `0x2160` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x438` | `0x470` | **`+0x38`** |
| `__DATA.__data` | `0xb00` | `0xb30` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x15c0` | `0x15f0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xdf4` | `0xe24` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x324` | `0x354` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x5f0` | `0x618` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x274` | `0x294` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xbe5` | `0xc01` | **`+0x1c`** |
| `__DATA.__common` | `0x1d8` | `0x1f0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x3fc` | `0x414` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1fc` | `0x214` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA.__objc_const` | `0x620` | `0x630` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x68c` | `0x69c` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-41.0.50.0.0
+41.1.9.0.0

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 1397
-  Symbols:   216
-  CStrings:  354
+  Functions: 1449
+  Symbols:   221
+  CStrings:  365
Symbols:
+ _LNMetadataProviderErrorDomain
+ _OBJC_CLASS_$_LNAutoShortcut
+ _OBJC_CLASS_$_LNStaticDeferredLocalizedString
+ _OBJC_CLASS_$_NSError
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
CStrings:
+ "Failed to tear down ephemeral services: %@"
+ "RunnerServiceDispatcher.updateAppShortcutParameters"
+ "autoShortcuts(forBundleIdentifier:localeIdentifier:)"
+ "autoShortcutsForBundleIdentifier:localeIdentifier:completion:"
+ "basePhraseTemplate"
+ "basePhraseTemplates"
+ "code"
+ "domain"
+ "key"
+ "openApplicationAndFetchListenerEndpointWithLaunchApplicationRequest:reply:"
+ "openApplicationWithLaunchApplicationRequest:reply:"
+ "v24@?0@\"NSArray\"8@\"NSError\"16"
+ "v32@0:8@\"LNDaemonLaunchApplicationRequest\"16@?<v@?@\"LNConnectionListenerEndpoint\"@\"NSError\">24"
+ "v32@0:8@\"LNDaemonLaunchApplicationRequest\"16@?<v@?@\"NSError\">24"
+ "v40@0:8@\"LNAppEntityContext\"16@\"NSString\"24@?<v@?@\"NSError\">32"
+ "v48@0:8@\"NSArray\"16@\"LNAppEntityContext\"24@\"NSString\"32@?<v@?@\"NSError\">40"
- "autoShortcuts(forLocaleIdentifier:)"
- "autoShortcutsForLocaleIdentifier:completion:"
- "v24@?0@\"NSDictionary\"8@\"NSError\"16"
- "v40@0:8@\"NSData\"16@\"NSString\"24@?<v@?@\"NSError\">32"
- "v48@0:8@\"NSData\"16@\"NSData\"24@\"NSString\"32@?<v@?@\"NSError\">40"
```
