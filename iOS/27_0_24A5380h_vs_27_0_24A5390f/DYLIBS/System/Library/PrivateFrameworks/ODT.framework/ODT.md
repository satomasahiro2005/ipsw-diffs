## ODT

> `/System/Library/PrivateFrameworks/ODT.framework/ODT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ef2d0` | `0x4e988c` | **`-0x5a44`** |
| `__TEXT.__const` | `0x2db68` | `0x2c328` | **`-0x1840`** |
| `__AUTH_CONST.__const` | `0x1a408` | `0x19b50` | **`-0x8b8`** |
| `__TEXT.__gcc_except_tab` | `0x239ec` | `0x23524` | **`-0x4c8`** |
| `__TEXT.__unwind_info` | `0xd240` | `0xd050` | **`-0x1f0`** |
| `__DATA.__bss` | `0xe28` | `0xde8` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x954` | `0x98c` | **`+0x38`** |
| `__TEXT.__cstring` | `0x11cdb` | `0x11cb3` | **`-0x28`** |

### Other Changes

```diff

-25.2.0.0.0
+26.5.0.0.0

-  Functions: 10674
+  Functions: 10544

-  CStrings:  1645
+  CStrings:  1650
CStrings:
+ " OTA asset missing metadata.json"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/library/ODT/Util/include/ODT/Util/PoseFilter.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ODT/product/ODT/ODT/src/ODT3DContext.mm"
+ "ApplyModelCatalogAssets: %s missing metadata.json at %s"
+ "Detector"
+ "ResetTo not implemented for this filter"
+ "Unhandled BlendAlphaMapping"
+ "iPhone tracker"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::concurrency::ChannelOutput<cv3d::odt::api::odt3d::ModelCatalogAssetsReleaseOutput>]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::odt::api::odt3d::ModelCatalogAssetsReleaseOutput (const cv3d::odt::api::odt3d::ModelCatalogAssetsReleaseInput &)]"
- "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::odt::api::odt3d::ModelCatalogAssetsReleaseOutput]"
```
