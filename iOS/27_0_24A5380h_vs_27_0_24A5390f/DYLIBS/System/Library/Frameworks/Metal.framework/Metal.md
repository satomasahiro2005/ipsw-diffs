## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e6a3c` | `0x1e6bec` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x46ba0` | `0x46bd0` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e40` | `0x8e68` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x18` | `0x30` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1eb6c` | `0x1eb7c` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x222c` | `0x2230` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0xc39c` | `0xc3a0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-382.4.0.0.0
+382.5.0.0.0

-  Functions: 13492
-  Symbols:   22502
+  Functions: 13494
+  Symbols:   22504
Symbols:
+ -[_MTL4MachineLearningCommandEncoder agentMask]
+ _OBJC_IVAR_$__MTL4MachineLearningCommandEncoder._agentMask
+ __ZN24MTLXPCCompilerConnection12setupSandboxEhb
+ __ZN26MTLArchiveLinkResolverImpl21readFlatbufferInPlaceEjRj
+ __ZN30MTLLegacyXPCCompilerConnection12setupSandboxEhb
+ __ZZN24MTLXPCCompilerConnection12setupSandboxEhbE23fromSourceSandboxTokens
+ __ZZN24MTLXPCCompilerConnection12setupSandboxEhbE23gpuArchiverSandboxToken
+ __ZZN24MTLXPCCompilerConnection12setupSandboxEhbE9onceToken
+ __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhbE23fromSourceSandboxTokens
+ __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhbE23gpuArchiverSandboxToken
+ __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhbE9onceToken
+ ____ZN24MTLXPCCompilerConnection12setupSandboxEhb_block_invoke
+ ____ZN30MTLLegacyXPCCompilerConnection12setupSandboxEhb_block_invoke
- __ZN24MTLXPCCompilerConnection12setupSandboxEh
- __ZN26MTLArchiveLinkResolverImpl21readFlatbufferInPlaceEj
- __ZN30MTLLegacyXPCCompilerConnection12setupSandboxEh
- __ZZN24MTLXPCCompilerConnection12setupSandboxEhE23fromSourceSandboxTokens
- __ZZN24MTLXPCCompilerConnection12setupSandboxEhE23gpuArchiverSandboxToken
- __ZZN24MTLXPCCompilerConnection12setupSandboxEhE9onceToken
- __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhE23fromSourceSandboxTokens
- __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhE23gpuArchiverSandboxToken
- __ZZN30MTLLegacyXPCCompilerConnection12setupSandboxEhE9onceToken
- ____ZN24MTLXPCCompilerConnection12setupSandboxEh_block_invoke
- ____ZN30MTLLegacyXPCCompilerConnection12setupSandboxEh_block_invoke
CStrings:
+ "23:33:30"
+ "Jul 10 2026"
+ "Jul 10 2026 23:33:30"
- "01:59:26"
- "Jun 27 2026"
- "Jun 27 2026 01:59:26"
```
