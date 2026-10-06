## CoreRE

> `/System/Library/PrivateFrameworks/CoreRE.framework/CoreRE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1683630` | `0x1683760` | **`+0x130`** |
| `__TEXT.__cstring` | `0xb4ab8` | `0xb4ad8` | **`+0x20`** |

### Other Changes

```diff

-453.40.4.0.0
+453.40.5.0.0

-  CStrings:  23224
+  CStrings:  23226
Functions:
~ __ZN2re34createMaterialSystemShaderMetadataEbbb : 2652 -> 2860
~ __ZN2re24fillArgBufferForSemanticINS_3mtl20RenderCommandEncoderEEEvPNS_20VertexArgumentBufferERKNS_14AttributeTableERKNS_5SliceINS_19AttributeResolutionEEEN2NS9SharedPtrIN3MTL6BufferEEERKT_j : 704 -> 752
~ __ZN2re24fillArgBufferForSemanticINS_3mtl21ComputeCommandEncoderEEEvPNS_20VertexArgumentBufferERKNS_14AttributeTableERKNS_5SliceINS_19AttributeResolutionEEEN2NS9SharedPtrIN3MTL6BufferEEERKT_j : 692 -> 740
CStrings:
+ "fsDepthOnlyClipping"
+ "vsDepthOnly"
```
