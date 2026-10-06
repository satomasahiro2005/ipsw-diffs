## com.apple.MobileInstallationHelperService

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/XPCServices/com.apple.MobileInstallationHelperService.xpc/com.apple.MobileInstallationHelperService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14cb4` | `0x151ec` | **`+0x538`** |
| `__TEXT.__cstring` | `0x5c24` | `0x5e64` | **`+0x240`** |
| `__DATA_CONST.__cfstring` | `0x3360` | `0x3440` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x2aa5` | `0x2b59` | **`+0xb4`** |
| `__DATA.__objc_const` | `0x1010` | `0x1050` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1f20` | `0x1f60` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x277` | `0x2ac` | **`+0x35`** |
| `__TEXT.__objc_methtype` | `0x8c8` | `0x8e2` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0x960` | `0x978` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x8cc` | `0x8e4` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xc20` | `0xc30` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x15e` | `0x16e` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x620` | `0x628` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__const` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x408` | `0x410` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1663.0.0.0.1
+1673.0.0.0.0

-  Functions: 306
-  Symbols:   408
-  CStrings:  993
+  Functions: 308
+  Symbols:   409
+  CStrings:  1007
Symbols:
+ _sandbox_extension_release
Functions:
~ sub_1000019a4 : 160 -> 1160
+ sub_100001e2c
+ sub_1000160e4
CStrings:
+ "%s: Failed to release sandbox token %lld for %@ : %s"
+ "-[MIUserManagement(DaemonUtilities) daemonContainerForPersonaUniqueString:personaVolumeMount:personaVolumeUUID:extensionTokenHandle:error:]"
+ "01:11:09"
+ "@56@0:8@16@24^@32^q40^@48"
+ "DaemonUtilities"
+ "Failed to determine volume UUID for daemon container for persona %@ at %@"
+ "Failed to determine volume UUID for persona volume mount %@"
+ "Failed to get daemon container URL from %@"
+ "Failed to get daemon container for persona %@"
+ "Failed to get sandbox extension for daemon container for persona %@ at %@"
+ "Failed to release sandbox token %lld for %@ : %s"
+ "Got daemon container at %@ for data separated persona %@ that was not on persona mount %@"
+ "Jul 11 2026"
+ "daemonContainerForPersona:error:"
+ "daemonContainerForPersonaUniqueString:personaVolumeMount:personaVolumeUUID:extensionTokenHandle:error:"
+ "transferOwnershipOfSandboxExtensionToCaller"
- "01:30:57"
- "Jun 27 2026"
```
