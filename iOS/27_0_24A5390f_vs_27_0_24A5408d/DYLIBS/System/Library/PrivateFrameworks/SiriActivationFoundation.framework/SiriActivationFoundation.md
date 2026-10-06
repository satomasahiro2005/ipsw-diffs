## SiriActivationFoundation

> `/System/Library/PrivateFrameworks/SiriActivationFoundation.framework/SiriActivationFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ad5c` | `0x3aec4` | **`+0x168`** |
| `__TEXT.__cstring` | `0x445b` | `0x450b` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x3b40` | `0x3bc0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1188` | `0x11f0` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x5a10` | `0x5a70` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2804` | `0x2834` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x10e0` | `0x1100` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x358` | `0x360` | **`+0x8`** |

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 1904
-  Symbols:   2084
-  CStrings:  602
+  Functions: 1908
+  Symbols:   2090
+  CStrings:  606
Symbols:
+ -[SAFRequestOptions isInitiatedByPresentedAssistantInterface]
+ -[SAFRequestOptions referenceIdentifier]
+ -[SAFRequestOptions setIsInitiatedByPresentedAssistantInterface:]
+ -[SAFRequestOptions setReferenceIdentifier:]
+ _OBJC_IVAR_$_SAFRequestOptions._isInitiatedByPresentedAssistantInterface
+ _OBJC_IVAR_$_SAFRequestOptions._referenceIdentifier
CStrings:
+ ";isInitiatedByPresentedAssistantInterface=%i"
+ ";referenceIdentifier=%@"
+ "SAFRequestOptionsInitiatedByPresentedAssistantInterfaceCodingKey"
+ "SAFRequestOptionsReferenceIdentifierCodingKey"
```
