## RenderBox

> `/System/Library/PrivateFrameworks/RenderBox.framework/RenderBox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16f88c` | `0x16fa9c` | **`+0x210`** |
| `__TEXT.__cstring` | `0x6888` | `0x68c7` | **`+0x3f`** |
| `__TEXT.__gcc_except_tab` | `0x80bc` | `0x80f0` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0x3320` | `0x3300` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1500` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f40` | `0x1f48` | **`+0x8`** |

### Other Changes

```diff

-8.0.84.0.0
+8.1.5.0.0

-  Functions: 7705
+  Functions: 7704

-  CStrings:  1778
+  CStrings:  1781
Symbols:
+ GCC_except_table81
+ GCC_except_table85
+ __ZN2RB16SharedSubsurface11mark_commitEP9CAContext
+ __ZN2RB16SharedSubsurface5resetEP9CAContext
+ __ZN2RB18SharedSurfaceGroup17remove_subsurfaceERNS_16SharedSubsurfaceEP9CAContext
+ __ZN2RB21coverage_pixel_formatENS_14CoverageFormatE
+ __ZN2RB4Fill12MeshGradient10clear_dataEv
+ __ZNK2RB6Symbol5Model20variable_draw_paramsEfRKNS0_5Glyph5LayerEb
+ _objc_retain_x25
- GCC_except_table112
- GCC_except_table82
- __ZN2RB16SharedSubsurface11mark_commitEv
- __ZN2RB16SharedSubsurface5resetEv
- __ZN2RB16SharedSubsurface6attachEP9CAContext
- __ZN2RB18SharedSurfaceGroup17remove_subsurfaceERNS_16SharedSubsurfaceEb
- __ZN2RB7details14realloc_vectorIjLm48EEEPvS2_S2_T_RS3_S3_y
- __ZN2RB7details14realloc_vectorImLm56EEEPvS2_S2_T_RS3_S3_y
- __ZNK2RB6Symbol5Model20variable_draw_paramsEfRKNS0_5Glyph5LayerE
CStrings:
+ "8.1.5"
+ "hit-test:ignore"
+ "hit-test:opaque"
+ "hit-test:report"
+ "invalid coverage format: %u\n"
- "8.0.84"
- "has_coverage"
```
