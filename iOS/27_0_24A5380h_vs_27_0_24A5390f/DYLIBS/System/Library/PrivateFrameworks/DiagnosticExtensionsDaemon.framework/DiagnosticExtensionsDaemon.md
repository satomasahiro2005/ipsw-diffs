## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75ab0` | `0x759a8` | **`-0x108`** |
| `__TEXT.__cstring` | `0x5730` | `0x56f0` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x13a40` | `0x13a70` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2178` | `0x2150` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x6fa4` | `0x6fcc` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5040` | `0x5020` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1ae0` | `0x1ac0` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x9828` | `0x9808` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x6f8` | `0x6e8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b70` | `0x3b80` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1cc8` | `0x1cc0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5e0` | `0x5e4` | **`+0x4`** |

### Other Changes

```diff

-220.0.0.0.0
+221.0.0.0.0

+  - /System/Library/PrivateFrameworks/DiagnosticExtensionsKit.framework/DiagnosticExtensionsKit

-  Functions: 2920
+  Functions: 2921

-  CStrings:  1790
+  CStrings:  1787
Symbols:
+ -[DEDDiagnosticCollector cachedExtensionManager]
+ -[DEDDiagnosticCollector deExtensionForIdentifier:]
+ -[DEDDiagnosticCollector setCachedExtensionManager:]
+ _OBJC_CLASS_$_DEKExtensionManager
+ _OBJC_IVAR_$_DEDDiagnosticCollector._cachedExtensionManager
- _NSExtensionPointName
- _OBJC_CLASS_$_DEExtensionManager
- _OBJC_CLASS_$_NSExtension
- ___56-[DEDDiagnosticCollector isDiagnosticExtensionAvailable]_block_invoke
- ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16ls32l8r48l8s40l8
CStrings:
- "Error finding diagnostic extension [%@]"
- "com.apple.diagnosticextensions-service"
- "v24@?0@\"NSArray\"8@\"NSError\"16"
```
