## DiagnosticsCheckup

> `/System/Library/PrivateFrameworks/DiagnosticsCheckup.framework/DiagnosticsCheckup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e58` | `0x49a0` | **`+0x1b48`** |
| `__AUTH_CONST.__objc_const` | `0x268` | `0x728` | **`+0x4c0`** |
| `__AUTH_CONST.__const` | `0x230` | `0x340` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x1dc` | `0x2dc` | **`+0x100`** |
| `__TEXT.__cstring` | `0x196` | `0x238` | **`+0xa2`** |
| `__DATA_CONST.__objc_selrefs` | `0x158` | `0x1f0` | **`+0x98`** |
| `__DATA.__data` | `0x120` | `0x1b0` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x8c` | `0x100` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0xc0` | `0x132` | **`+0x72`** |
| `__TEXT.__unwind_info` | `0x128` | `0x180` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x70` | `0xc0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x190` | `0x1d8` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__const` | `0x62` | `0x82` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 72
-  Symbols:   98
-  CStrings:  7
+  Functions: 111
+  Symbols:   128
+  CStrings:  11
Symbols:
+ +[DiagnosticsCheckupLauncherClient exportedInterface]
+ -[DiagnosticsCheckupLauncherClient .cxx_destruct]
+ -[DiagnosticsCheckupLauncherClient diagnosticsExitingForReason:]
+ -[DiagnosticsCheckupLauncherClient initWithExitHandler:]
+ _OBJC_CLASS_$_DiagnosticsCheckupLauncherClient
+ _OBJC_IVAR_$_DiagnosticsCheckupLauncherClient._exitHandler
+ _OBJC_METACLASS_$_DiagnosticsCheckupLauncherClient
+ __OBJC_$_CLASS_METHODS_DiagnosticsCheckupLauncherClient
+ __OBJC_$_INSTANCE_METHODS_DiagnosticsCheckupLauncherClient
+ __OBJC_$_INSTANCE_VARIABLES_DiagnosticsCheckupLauncherClient
+ __OBJC_$_PROP_LIST_DiagnosticsCheckupLauncherClient
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_DADiagnosticsLauncherClientProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_DADiagnosticsLauncherClientProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_DADiagnosticsLauncherClientProtocol
+ __OBJC_$_PROTOCOL_REFS_DADiagnosticsLauncherClientProtocol
+ __OBJC_CLASS_PROTOCOLS_$_DiagnosticsCheckupLauncherClient
+ __OBJC_CLASS_RO_$_DiagnosticsCheckupLauncherClient
+ __OBJC_LABEL_PROTOCOL_$_DADiagnosticsLauncherClientProtocol
+ __OBJC_METACLASS_RO_$_DiagnosticsCheckupLauncherClient
+ __OBJC_PROTOCOL_$_DADiagnosticsLauncherClientProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_DADiagnosticsLauncherClientProtocol
+ _objc_release_x19
+ _objc_release_x8
+ _objc_retain_x2
+ _objc_storeStrong
+ _swift_getForeignTypeMetadata
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic So15NSXPCConnectionCSgXw
+ _symbolic So15NSXPCConnectionCSgXwz_Xx
+ _symbolic So25DiagnosticsCheckupServiceCSgXw
+ _symbolic So25DiagnosticsCheckupServiceCSgXwz_Xx
+ _symbolic _____ So23DADiagnosticsExitReasonV
+ _symbolic _____IeyBy_ So23DADiagnosticsExitReasonV
- _symbolic Ieg_
- _symbolic IeyB_
- _symbolic Sb
- _symbolic Sbz_Xx
- _symbolic So6NSLockC
CStrings:
+ "DiagnosticsCheckupLauncherClient callback called"
+ "calling self.reportExit"
+ "invoking exit handler"
+ "reporting exit"
```
