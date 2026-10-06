## ClassroomKit

> `/System/Library/PrivateFrameworks/ClassroomKit.framework/ClassroomKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4cdc` | `0xb5830` | **`+0xb54`** |
| `__AUTH_CONST.__objc_const` | `0x26fd8` | `0x271f0` | **`+0x218`** |
| `__TEXT.__objc_methlist` | `0x130f4` | `0x131bc` | **`+0xc8`** |
| `__AUTH.__objc_data` | `0x7170` | `0x7210` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x4ab1` | `0x4b4a` | **`+0x99`** |
| `__TEXT.__cstring` | `0x8c09` | `0x8c95` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x9040` | `0x90c0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x720` | `0x768` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x7038` | `0x7068` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x18e0` | `0x1900` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3b20` | `0x3b38` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1270` | `0x1284` | **`+0x14`** |
| `__DATA.__bss` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xf28` | `0xf38` | **`+0x10`** |
| `__TEXT.__const` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x12f0` | `0x12f8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc10` | `0xc18` | **`+0x8`** |

### Other Changes

```diff

-143.2.1.0.0
-  - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
+148.40.4.0.0

-  Functions: 6470
-  Symbols:   12431
-  CStrings:  1669
+  Functions: 6489
+  Symbols:   12474
+  CStrings:  1676
Symbols:
+ +[CRKReImportEDUIdentityRequest allowlistedClassForResultObject]
+ +[CRKReImportEDUIdentityRequest supportsSecureCoding]
+ +[CRKReImportEDUIdentityResultObject supportsSecureCoding]
+ -[CRKClassSessionBrowser _debugFireBeaconCallbacks]
+ -[CRKClassSessionBrowser _debugStartBeaconSimulationIfNeeded]
+ -[CRKClassSessionBrowser _debugStopBeaconSimulation]
+ -[CRKReImportEDUIdentityResultObject .cxx_destruct]
+ -[CRKReImportEDUIdentityResultObject dictionaryValue]
+ -[CRKReImportEDUIdentityResultObject encodeWithCoder:]
+ -[CRKReImportEDUIdentityResultObject initWithCoder:]
+ -[CRKReImportEDUIdentityResultObject reason]
+ -[CRKReImportEDUIdentityResultObject setReason:]
+ -[CRKReImportEDUIdentityResultObject setWasIdentityReImported:]
+ -[CRKReImportEDUIdentityResultObject wasIdentityReImported]
+ -[CRKSession crk_debugKickOutOfBackoff]
+ _CRKDebugDirectConnectAllowed.allowed
+ _CRKDebugDirectConnectAllowed.once
+ _OBJC_CLASS_$_CRKReImportEDUIdentityRequest
+ _OBJC_CLASS_$_CRKReImportEDUIdentityResultObject
+ _OBJC_IVAR_$_CRKClassSessionBrowser.mDebugBeaconTimer
+ _OBJC_IVAR_$_CRKClassSessionBrowser.mDebugLeaderIP
+ _OBJC_IVAR_$_CRKClassSessionBrowser.mDebugLeaderIPString
+ _OBJC_IVAR_$_CRKReImportEDUIdentityResultObject._reason
+ _OBJC_IVAR_$_CRKReImportEDUIdentityResultObject._wasIdentityReImported
+ _OBJC_METACLASS_$_CRKReImportEDUIdentityRequest
+ _OBJC_METACLASS_$_CRKReImportEDUIdentityResultObject
+ __OBJC_$_CLASS_METHODS_CRKReImportEDUIdentityRequest
+ __OBJC_$_CLASS_METHODS_CRKReImportEDUIdentityResultObject
+ __OBJC_$_INSTANCE_METHODS_CRKReImportEDUIdentityResultObject
+ __OBJC_$_INSTANCE_VARIABLES_CRKReImportEDUIdentityResultObject
+ __OBJC_$_PROP_LIST_CRKReImportEDUIdentityResultObject
+ __OBJC_CLASS_PROTOCOLS_$_CRKReImportEDUIdentityResultObject
+ __OBJC_CLASS_RO_$_CRKReImportEDUIdentityRequest
+ __OBJC_CLASS_RO_$_CRKReImportEDUIdentityResultObject
+ __OBJC_METACLASS_RO_$_CRKReImportEDUIdentityRequest
+ __OBJC_METACLASS_RO_$_CRKReImportEDUIdentityResultObject
+ ___61-[CRKClassSessionBrowser _debugStartBeaconSimulationIfNeeded]_block_invoke
+ ___CRKDebugDirectConnectAllowed_block_invoke
+ _freeaddrinfo
+ _gai_strerror
+ _getaddrinfo
+ _inet_ntop
+ _os_variant_has_internal_diagnostics
CStrings:
+ "\t2"
+ "App lock encountered an error and was canceled."
+ "CRKDebugDirectConnectHostname"
+ "CRKDebugDirectConnectSimulateBeaconLoss"
+ "Debug direct connect: failed to resolve hostname %{private}@: %{private}s"
+ "Debug direct connect: starting beacon simulation for %{private}@ (%{private}@)"
+ "wasIdentityReImported"
+ "\xa2"
- "\x82"
```
