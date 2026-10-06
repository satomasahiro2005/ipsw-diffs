## libANGLE-shared.dylib

> `/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libANGLE-shared.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x259160` | `0x258d10` | **`-0x450`** |
| `__TEXT.__cstring` | `0x43cce` | `0x43d25` | **`+0x57`** |
| `__TEXT.__const` | `0x83f40` | `0x83f00` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x15df0` | `0x15db8` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x92f8` | `0x92d8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x12fd8` | `0x12fc8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2b58` | `0x2b5c` | **`+0x4`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Functions: 9089
-  Symbols:   13252
-  CStrings:  6974
+  Functions: 9088
+  Symbols:   13250
+  CStrings:  6977
Symbols:
+ __ZN2gl27ValidateNoActivePLSConflictEPKNS_7ContextEN5angle10EntryPointENS_14RenderbufferIDE
+ __ZN2gl27ValidateNoActivePLSConflictEPKNS_7ContextEN5angle10EntryPointENS_9TextureIDE
+ __ZN2rx10TextureMtl23deallocateNativeStorageEb
+ __ZN2rx3mtl26CopyPixelsFromBufferParamsD1Ev
+ __ZN2sh12_GLOBAL__N_114FindLValueBaseEPNS_12TIntermTypedE
+ __ZN2sh12_GLOBAL__N_119PruneNoOpsTraverser11visitBinaryENS_5VisitEPNS_13TIntermBinaryE
+ __ZN2sh12_GLOBAL__N_119PruneNoOpsTraverser25pruneNoOpCommaExpressionsEPNS_12TIntermTypedENS0_15CommaExpressionE
+ __ZN2sh12_GLOBAL__N_119PruneNoOpsTraverser29pruneCommaThrowAwayExpressionEPNS_12TIntermTypedE
+ __ZN2sh12_GLOBAL__N_119PruneNoOpsTraverser31mergePrunedNoOpCommaExpressionsEPNS_12TIntermTypedES3_
+ __ZN2sh12_GLOBAL__N_129GLFragColorBroadcastTraverser31visitGlobalQualifierDeclarationENS_5VisitEPNS_33TIntermGlobalQualifierDeclarationE
+ __ZN2sh13TParseContext18checkShaderVersionERKNS_10TSourceLocE
+ __ZN2sh13TParseContext23onShaderVersionDeclaredERKNS_10TSourceLocEi
+ __ZN2sh26GetMaxShaderVersionForSpecE12ShShaderSpec
+ __ZN2shL12kNoSourceLocE
+ __ZNK2rx14FramebufferMtl33needsRG16UnormMSAAClearWorkaroundEPKNS_10ContextMtlEN5angle7BitSetTILm8EhmEE
+ __ZNSt3__13mapIN2gl10ImageIndexEN5angle13PackedEnumMapINS1_25RenderToTextureImageIndexEN2rx15RenderTargetMtlELm5EEENS_4lessIS2_EENS_9allocatorINS_4pairIKS2_S8_EEEEEixERSD_
+ __ZThn544_N2gl11VertexArrayD0Ev
+ __ZThn544_N2gl11VertexArrayD1Ev
- GCC_except_table58
- GCC_except_table59
- _GL_InvalidateTextureANGLE
- _GL_TexImage2DExternalANGLE
- __ZN2gl30ValidateInvalidateTextureANGLEEPKNS_7ContextEN5angle10EntryPointENS_11TextureTypeE
- __ZN2gl31ValidateTexImage2DExternalANGLEEPKNS_7ContextEN5angle10EntryPointENS_13TextureTargetEiiiiijj
- __ZN2gl33ValidateES2TexImageParametersBaseEPKNS_7ContextEN5angle10EntryPointENS_13TextureTargetEijbbiiiiijjPKvPj
- __ZN2gl7Texture16setImageExternalEPNS_7ContextENS_13TextureTargetEijRKN5angle7ExtentsIiEEjj
- __ZN2rx10TextureMtl15copySubImageCPUEPKN2gl7ContextERKNS1_10ImageIndexERKN5angle6OffsetIiEERKNS1_13RectangleImplIiEERKNS1_14InternalFormatEPKNS_14FramebufferMtlEPKNS_15RenderTargetMtlE
- __ZN2rx10TextureMtl18ensureImageCreatedEPKN2gl7ContextERKNS1_10ImageIndexE
- __ZN2rx10TextureMtl20copySubImageWithDrawEPKN2gl7ContextERKNS1_10ImageIndexERKN5angle6OffsetIiEERKNS1_13RectangleImplIiEERKNS1_14InternalFormatEPKNS_14FramebufferMtlEPKNS_15RenderTargetMtlE
- __ZN2rx10TextureMtl23deallocateNativeStorageEbb
- __ZN2rx11ContextImpl17invalidateTextureEN2gl11TextureTypeE
- __ZN2rx11TextureImpl16setImageExternalEPKN2gl7ContextERKNS1_10ImageIndexEjRKN5angle7ExtentsIiEEjj
- __ZN2rx3mtl26CopyPixelsFromBufferParamsD2Ev
- __ZN2sh12_GLOBAL__N_119PruneNoOpsTraverser25pruneNoOpCommaExpressionsEPNS_12TIntermTypedE
- __ZNK2rx11TextureImpl11getNativeIDEv
- __ZNSt3__16vectorIN2sh16TIntermTraverser28NodeReplaceWithMultipleEntryENS_9allocatorIS3_EEE12emplace_backIJRPNS1_18TIntermDeclarationERPNS1_13TIntermSymbolENS1_7TVectorIPNS1_11TIntermNodeEEEEEERS3_DpOT_
- __ZThn552_N2gl11VertexArrayD0Ev
- __ZThn552_N2gl11VertexArrayD1Ev
CStrings:
+ "1.5 (ANGLE 2.1.27980 git hash: 1359a25fcf26)"
+ "2.1.27980 git hash: 1359a25fcf26"
+ "b3596e5feb49a4fc9fa9f506a95bc91f"
+ "clearMsaaRg16UnormWithDrawWorkaround"
+ "copySubImageImpl"
+ "copySubTextureImpl"
+ "copySubTextureWithDraw"
+ "initializeContents"
+ "modifying structures containing samplers is not currently supported"
+ "unsupported shader version "
- "1.5 (ANGLE 2.1.27944 git hash: 7f06a944d91a)"
- "2.1.27944 git hash: 7f06a944d91a"
- "GL_ANGLE_texture_external_update"
- "d29efb93a06d55ec6caa3ad79f59e154"
- "glInvalidateTextureANGLE"
- "glTexImage2DExternalANGLE"
- "unsupported shader version"
```
