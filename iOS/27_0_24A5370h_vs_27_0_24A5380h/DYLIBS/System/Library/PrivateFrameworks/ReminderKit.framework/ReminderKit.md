## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/ReminderKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3c50` | `0x4830` | **`+0xbe0`** |
| `__DATA_DIRTY.__objc_data` | `0x3ca0` | `0x3160` | **`-0xb40`** |
| `__AUTH_CONST.__objc_const` | `0x246c0` | `0x24808` | **`+0x148`** |
| `__TEXT.__text` | `0x13bbf8` | `0x13bd04` | **`+0x10c`** |
| `__TEXT.__objc_methlist` | `0x15b40` | `0x15bc8` | **`+0x88`** |
| `__DATA.__bss` | `0x504` | `0x574` | **`+0x70`** |
| `__DATA.__data` | `0x1a44` | `0x1aa4` | **`+0x60`** |
| `__DATA_DIRTY.__bss` | `0x270` | `0x210` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b60` | `0x7b88` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xe600` | `0xe620` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2cc0` | `0x2ce0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf68` | `0xf88` | **`+0x20`** |
| `__TEXT.__cstring` | `0xe4ee` | `0xe500` | **`+0x12`** |
| `__DATA_CONST.__objc_classlist` | `0xc18` | `0xc28` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6ac8` | `0x6ad0` | **`+0x8`** |

### Other Changes

```diff

-4037.1.0.0.0
+4040.0.0.0.0

-  Functions: 8794
-  Symbols:   14277
-  CStrings:  2969
+  Functions: 8800
+  Symbols:   14297
+  CStrings:  2970
Symbols:
+ +[REMXPCSignificantChangePerformerInterface interface]
+ -[REMXPCDaemonController asyncSignificantChangePerformerWithReason:loadHandler:errorHandler:]
+ -[REMXPCDaemonControllerPerformerResolver_significantChange name]
+ -[REMXPCDaemonControllerPerformerResolver_significantChange resolveWithDaemon:reason:completion:]
+ _OBJC_CLASS_$_REMXPCDaemonControllerPerformerResolver_significantChange
+ _OBJC_CLASS_$_REMXPCSignificantChangePerformerInterface
+ _OBJC_METACLASS_$_REMXPCDaemonControllerPerformerResolver_significantChange
+ _OBJC_METACLASS_$_REMXPCSignificantChangePerformerInterface
+ __OBJC_$_CLASS_METHODS_REMXPCSignificantChangePerformerInterface
+ __OBJC_$_INSTANCE_METHODS_REMXPCDaemonControllerPerformerResolver_significantChange
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_REMXPCSignificantChangePerformer
+ __OBJC_$_PROTOCOL_METHOD_TYPES_REMXPCSignificantChangePerformer
+ __OBJC_CLASS_RO_$_REMXPCDaemonControllerPerformerResolver_significantChange
+ __OBJC_CLASS_RO_$_REMXPCSignificantChangePerformerInterface
+ __OBJC_LABEL_PROTOCOL_$_REMXPCSignificantChangePerformer
+ __OBJC_METACLASS_RO_$_REMXPCDaemonControllerPerformerResolver_significantChange
+ __OBJC_METACLASS_RO_$_REMXPCSignificantChangePerformerInterface
+ __OBJC_PROTOCOL_$_REMXPCSignificantChangePerformer
+ __OBJC_PROTOCOL_REFERENCE_$_REMXPCSignificantChangePerformer
+ ___54+[REMXPCSignificantChangePerformerInterface interface]_block_invoke
CStrings:
+ "significantChange"
```
