## SoftwareUpdateCoreConnect

> `/System/Library/PrivateFrameworks/SoftwareUpdateCoreConnect.framework/SoftwareUpdateCoreConnect`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa778` | `0xb0dc` | **`+0x964`** |
| `__AUTH_CONST.__objc_const` | `0x1238` | `0x1450` | **`+0x218`** |
| `__TEXT.__objc_methlist` | `0x9c8` | `0xb20` | **`+0x158`** |
| `__TEXT.__cstring` | `0xb0a` | `0xc03` | **`+0xf9`** |
| `__AUTH_CONST.__cfstring` | `0x920` | `0x9e0` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x678` | `0x710` | **`+0x98`** |
| `__DATA.__data` | `0x360` | `0x3c0` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0xb4` | `0xdc` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x358` | `0x370` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x50` | **`+0x8`** |

### Other Changes

```diff

-2718.0.18.0.0
+2718.40.13.0.0

-  Functions: 257
-  Symbols:   516
-  CStrings:  152
+  Functions: 286
+  Symbols:   561
+  CStrings:  159
Symbols:
+ -[SUCoreConnectClientPolicy conciseLoggingMessages]
+ -[SUCoreConnectClientPolicy debugLoggingMessages]
+ -[SUCoreConnectClientPolicy setConciseLoggingMessages:]
+ -[SUCoreConnectClientPolicy setDebugLoggingMessages:]
+ -[SUCoreConnectClientPolicy setUsesConciseMessageLogging:]
+ -[SUCoreConnectClientPolicy setUsesDebugMessageLogging:]
+ -[SUCoreConnectClientPolicy usesConciseLoggingForMessageName:]
+ -[SUCoreConnectClientPolicy usesConciseMessageLogging]
+ -[SUCoreConnectClientPolicy usesDebugLoggingForMessageName:]
+ -[SUCoreConnectClientPolicy usesDebugMessageLogging]
+ -[SUCoreConnectMessage loggableDescriptionForPolicy:]
+ -[SUCoreConnectMessage loggableLogTypeForPolicy:]
+ -[SUCoreConnectMessage setUsesConciseLogging:]
+ -[SUCoreConnectMessage setUsesDebugLogging:]
+ -[SUCoreConnectMessage usesConciseLogging]
+ -[SUCoreConnectMessage usesDebugLogging]
+ -[SUCoreConnectServerPolicy conciseLoggingMessages]
+ -[SUCoreConnectServerPolicy debugLoggingMessages]
+ -[SUCoreConnectServerPolicy setConciseLoggingMessages:]
+ -[SUCoreConnectServerPolicy setDebugLoggingMessages:]
+ -[SUCoreConnectServerPolicy setUsesConciseMessageLogging:]
+ -[SUCoreConnectServerPolicy setUsesDebugMessageLogging:]
+ -[SUCoreConnectServerPolicy usesConciseLoggingForMessageName:]
+ -[SUCoreConnectServerPolicy usesConciseMessageLogging]
+ -[SUCoreConnectServerPolicy usesDebugLoggingForMessageName:]
+ -[SUCoreConnectServerPolicy usesDebugMessageLogging]
+ _OBJC_IVAR_$_SUCoreConnectClientPolicy._conciseLoggingMessages
+ _OBJC_IVAR_$_SUCoreConnectClientPolicy._debugLoggingMessages
+ _OBJC_IVAR_$_SUCoreConnectClientPolicy._usesConciseMessageLogging
+ _OBJC_IVAR_$_SUCoreConnectClientPolicy._usesDebugMessageLogging
+ _OBJC_IVAR_$_SUCoreConnectMessage._usesConciseLogging
+ _OBJC_IVAR_$_SUCoreConnectMessage._usesDebugLogging
+ _OBJC_IVAR_$_SUCoreConnectServerPolicy._conciseLoggingMessages
+ _OBJC_IVAR_$_SUCoreConnectServerPolicy._debugLoggingMessages
+ _OBJC_IVAR_$_SUCoreConnectServerPolicy._usesConciseMessageLogging
+ _OBJC_IVAR_$_SUCoreConnectServerPolicy._usesDebugMessageLogging
+ _SUCoreConnectMessageAppendValue
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SUCoreConnectMessageLoggingPolicy
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SUCoreConnectMessageLoggingPolicy
+ __OBJC_$_PROTOCOL_REFS_SUCoreConnectMessageLoggingPolicy
+ __OBJC_LABEL_PROTOCOL_$_SUCoreConnectMessageLoggingPolicy
+ __OBJC_PROTOCOL_$_SUCoreConnectMessageLoggingPolicy
+ __os_log_debug_impl
+ _objc_retain_x27
+ _objc_setProperty_atomic_copy
CStrings:
+ ""
+ "%@"
+ "%@%@="
+ "(none)"
+ "(null)"
+ ","
+ "1"
+ "SUCoreConnectClientPolicy(serviceName:%@|clientID:%@|usesConciseMessageLogging:%@|conciseLoggingMessages:%@|usesDebugMessageLogging:%@|debugLoggingMessages:%@)"
+ "SUCoreConnectServerPolicy(serviceName:%@|usesConciseMessageLogging:%@|conciseLoggingMessages:%@|usesDebugMessageLogging:%@|debugLoggingMessages:%@)"
+ "UsesConciseLogging"
+ "UsesDebugLogging"
+ "["
+ "[depth-limit]"
+ "]"
+ "{"
+ "{depth-limit}"
+ "|"
+ "}"
- "\t\t%@\n"
- "\t\t%@: %@\n"
- "\t%@: %@\t]\n"
- "\t%@: %@\n"
- "\t%@: %@\n\t}\n"
- "<<<]"
- "SUCoreConnectClientPolicy(serviceName:%@|clientID:%@)"
- "SUCoreConnectServerPolicy(serviceName:%@)"
- "[\n"
- "[>>>\n"
- "{\n"
```
