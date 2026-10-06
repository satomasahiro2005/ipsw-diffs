## AppStoreKit

> `/System/Library/PrivateFrameworks/AppStoreKit.framework/AppStoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85e2c0` | `0x862eac` | **`+0x4bec`** |
| `__AUTH_CONST.__objc_const` | `0x47658` | `0x48f98` | **`+0x1940`** |
| `__DATA_DIRTY.__bss` | `0x1fa38` | `0x203b8` | **`+0x980`** |
| `__DATA_DIRTY.__data` | `0x2e948` | `0x2ef58` | **`+0x610`** |
| `__DATA.__bss` | `0x3a3d0` | `0x39ef0` | **`-0x4e0`** |
| `__AUTH.__data` | `0x12038` | `0x11b88` | **`-0x4b0`** |
| `__TEXT.__const` | `0x5ebc4` | `0x5ef54` | **`+0x390`** |
| `__AUTH_CONST.__const` | `0x4d460` | `0x4d7a8` | **`+0x348`** |
| `__DATA.__data` | `0xbdc8` | `0xbf08` | **`+0x140`** |
| `__TEXT.__swift5_fieldmd` | `0x1fe20` | `0x1ff38` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x1c7b8` | `0x1c8d0` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x229b0` | `0x22ab0` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x1c11c` | `0x1c214` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x2228d` | `0x2236d` | **`+0xe0`** |
| `__DATA_DIRTY.__objc_data` | `0x9600` | `0x96c8` | **`+0xc8`** |
| `__TEXT.__constg_swiftt` | `0x21864` | `0x2191c` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x45e0` | `0x4530` | **`-0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x5550` | `0x55c0` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x3d90` | `0x3df0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x2b78` | `0x2ba0` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x35d0` | `0x35f4` | **`+0x24`** |
| `__TEXT.__swift5_types` | `0x1d58` | `0x1d6c` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x4ba8` | `0x4bb8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c00` | `0x4c10` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x1f3c0` | `0x1f3d0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6190` | `0x6180` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0xc868` | `0xc874` | **`+0xc`** |
| `__DATA.__common` | `0xba8` | `0xba0` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x2448` | `0x2450` | **`+0x8`** |

### Other Changes

```diff

-27.1.16.0.0
+27.1.20.0.0

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  Functions: 45838
-  Symbols:   12895
-  CStrings:  3848
+  Functions: 45936
+  Symbols:   12930
+  CStrings:  3854
Symbols:
+ _CGContextSetInterpolationQuality
+ _CGDataProviderCopyData
+ _CGImageGetBitsPerComponent
+ _CGImageGetBitsPerPixel
+ _CGImageGetBytesPerRow
+ _CGImageGetColorSpace
+ _CGImageGetDataProvider
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CGImageSourceCreateImageAtIndex
+ _CGImageSourceCreateWithURL
+ _MTKTextureLoaderOptionGenerateMipmaps
+ _MTLRegionMake2D
+ _OBJC_CLASS_$_MTLFunctionConstantValues
+ _OBJC_CLASS_$__TtC11AppStoreKit13ChicletUIView
+ _OBJC_CLASS_$__TtC11AppStoreKit15ChicletRenderer
+ _OBJC_METACLASS_$__TtC11AppStoreKit13ChicletUIView
+ _OBJC_METACLASS_$__TtC11AppStoreKit15ChicletRenderer
+ __DATA__TtC11AppStoreKit13ChicletUIView
+ __DATA__TtC11AppStoreKit14MetalResources
+ __DATA__TtC11AppStoreKit15ChicletRenderer
+ __INSTANCE_METHODS__TtC11AppStoreKit13ChicletUIView
+ __INSTANCE_METHODS__TtC11AppStoreKit15ChicletRenderer
+ __IVARS__TtC11AppStoreKit13ChicletUIView
+ __IVARS__TtC11AppStoreKit14MetalResources
+ __IVARS__TtC11AppStoreKit15ChicletRenderer
+ __METACLASS_DATA__TtC11AppStoreKit13ChicletUIView
+ __METACLASS_DATA__TtC11AppStoreKit14MetalResources
+ __METACLASS_DATA__TtC11AppStoreKit15ChicletRenderer
+ __PROTOCOLS__TtC11AppStoreKit15ChicletRenderer
+ ___swift_closure_destructor.59Tm
+ _associated conformance 11AppStoreKit11ChicletViewV7SwiftUI0E0AA4BodyAdEP_AdE
+ _associated conformance 11AppStoreKit11ChicletViewV7SwiftUI19UIViewRepresentableAaD0E0
+ _associated conformance 11AppStoreKit13ChicletLayoutOSHAASQ
+ _associated conformance 11AppStoreKit13ChicletLayoutOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 11AppStoreKit13ChicletLayoutOs12IdentifiableAA2IDsADP_SH
+ _associated conformance 11AppStoreKit19PrefersWideGamutKeyV7SwiftUI025UITraitBridgedEnvironmentG0AaD0lG0
+ _associated conformance 11AppStoreKit7ArtworkC13DisplayTraitsVSHAASQ
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACy11AppStoreKit11ChicletViewVAA30_SafeAreaRegionsIgnoringLayoutVGAA25_AllowsHitTestingModifierVGAA01_d5ShapeR0VyAA9RectangleVGGAA017_AppearanceActionR0VGAA0I0HPAraVHPAlaVHPAiaVHPAfaVHPyHC_AhA0iR0HPyHCHC_AkaWHPyHCHC_AqaWHPyHCHC_AtaWHPyHCHC
+ _symbolic SDy__________SgG 11AppStoreKit13ChicletLayoutO AA0E9ResourcesV
+ _symbolic SaySo7UIImageCSgG
+ _symbolic Say_____6source_______p7texturetSgG So10CGImageRefa So10MTLTextureP
+ _symbolic Say_____G 11AppStoreKit13ChicletLayoutO
+ _symbolic _____ 11AppStoreKit11ChicletViewV
+ _symbolic _____ 11AppStoreKit13ChicletLayoutO
+ _symbolic _____ 11AppStoreKit13ChicletUIViewC
+ _symbolic _____ 11AppStoreKit14MetalResourcesC
+ _symbolic _____ 11AppStoreKit15ChicletRendererC
+ _symbolic _____ 11AppStoreKit15LayoutResourcesV
+ _symbolic _____ 11AppStoreKit19PrefersWideGamutKeyV
+ _symbolic _____ 11AppStoreKit7ArtworkC13DisplayTraitsV
+ _symbolic _____6source_______p7texturetSg So10CGImageRefa So10MTLTextureP
+ _symbolic _____Sg 11AppStoreKit14MetalResourcesC
+ _symbolic _____Sg 11AppStoreKit15LayoutResourcesV
+ _symbolic _____yAAyAAyAAy__________G_____G_____y_____GG_____G 7SwiftUI15ModifiedContentV 11AppStoreKit11ChicletViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV AA01_d5ShapeR0V AA9RectangleV AA017_AppearanceActionR0V
+ _symbolic _____yAAyAAy__________G_____G_____y_____GG 7SwiftUI15ModifiedContentV 11AppStoreKit11ChicletViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV AA01_d5ShapeR0V AA9RectangleV
+ _symbolic _____yAAy__________G_____G 7SwiftUI15ModifiedContentV 11AppStoreKit11ChicletViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV
+ _symbolic _____ySo7UIImageCSgG s23_ContiguousArrayStorageC
+ _symbolic _____y_____6source_______p7texturetSgG s23_ContiguousArrayStorageC So10CGImageRefa So10MTLTextureP
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV 11AppStoreKit7ArtworkC13DisplayTraitsV
+ _symbolic _____y_____G 7SwiftUI26UIViewRepresentableContextV 11AppStoreKit11ChicletViewV
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV 11AppStoreKit11ChicletViewV AA30_SafeAreaRegionsIgnoringLayoutV
+ _symbolic _____y__________SgG s18_DictionaryStorageC 11AppStoreKit13ChicletLayoutO AC0G9ResourcesV
+ _type_layout_string 11AppStoreKit11ChicletViewV
+ _type_layout_string 11AppStoreKit15LayoutResourcesV
+ _type_layout_string 11AppStoreKit7ArtworkC13DisplayTraitsV
- _OBJC_CLASS_$__TtC11AppStoreKit15BakedIconUIView
- _OBJC_CLASS_$__TtC11AppStoreKit17BakedIconRenderer
- _OBJC_METACLASS_$__TtC11AppStoreKit15BakedIconUIView
- _OBJC_METACLASS_$__TtC11AppStoreKit17BakedIconRenderer
- __DATA__TtC11AppStoreKit15BakedIconUIView
- __DATA__TtC11AppStoreKit17BakedIconRenderer
- __DATA__TtC11AppStoreKit18BakedIconResources
- __INSTANCE_METHODS__TtC11AppStoreKit15BakedIconUIView
- __INSTANCE_METHODS__TtC11AppStoreKit17BakedIconRenderer
- __IVARS__TtC11AppStoreKit15BakedIconUIView
- __IVARS__TtC11AppStoreKit17BakedIconRenderer
- __IVARS__TtC11AppStoreKit18BakedIconResources
- __METACLASS_DATA__TtC11AppStoreKit15BakedIconUIView
- __METACLASS_DATA__TtC11AppStoreKit17BakedIconRenderer
- __METACLASS_DATA__TtC11AppStoreKit18BakedIconResources
- __PROTOCOLS__TtC11AppStoreKit17BakedIconRenderer
- _associated conformance 11AppStoreKit13BakedIconViewV7SwiftUI0F0AA4BodyAdEP_AdE
- _associated conformance 11AppStoreKit13BakedIconViewV7SwiftUI19UIViewRepresentableAaD0F0
- _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACy11AppStoreKit13BakedIconViewVAA30_SafeAreaRegionsIgnoringLayoutVGAA25_AllowsHitTestingModifierVGAA01_d5ShapeS0VyAA9RectangleVGGAA017_AppearanceActionS0VGAA0J0HPAraVHPAlaVHPAiaVHPAfaVHPyHC_AhA0jS0HPyHCHC_AkaWHPyHCHC_AqaWHPyHCHC_AtaWHPyHCHC
- _symbolic So10NSMapTableCySo7UIImageC______pG So10MTLTextureP
- _symbolic _____ 11AppStoreKit13BakedIconViewV
- _symbolic _____ 11AppStoreKit15BakedIconUIViewC
- _symbolic _____ 11AppStoreKit17BakedIconRendererC
- _symbolic _____ 11AppStoreKit18BakedIconResourcesC
- _symbolic _____Sg 11AppStoreKit18BakedIconResourcesC
- _symbolic _____yAAyAAyAAy__________G_____G_____y_____GG_____G 7SwiftUI15ModifiedContentV 11AppStoreKit13BakedIconViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV AA01_d5ShapeS0V AA9RectangleV AA017_AppearanceActionS0V
- _symbolic _____yAAyAAy__________G_____G_____y_____GG 7SwiftUI15ModifiedContentV 11AppStoreKit13BakedIconViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV AA01_d5ShapeS0V AA9RectangleV
- _symbolic _____yAAy__________G_____G 7SwiftUI15ModifiedContentV 11AppStoreKit13BakedIconViewV AA30_SafeAreaRegionsIgnoringLayoutV AA25_AllowsHitTestingModifierV
- _symbolic _____y_____G 7SwiftUI26UIViewRepresentableContextV 11AppStoreKit13BakedIconViewV
- _symbolic _____y__________G 7SwiftUI15ModifiedContentV 11AppStoreKit13BakedIconViewV AA30_SafeAreaRegionsIgnoringLayoutV
- _type_layout_string 11AppStoreKit13BakedIconViewV
CStrings:
+ "53F05C5C-C237-4BEF-B3E5-36119AEE84EC"
+ "AppStoreKit.ChicletUIView"
+ "AppStoreKit/ChicletUIView.swift"
+ "Could not allocate the empty-slot albedo texture"
+ "Could not specialize chicletFragment (isMulti="
+ "DC4F1CC6-208D-48F5-9B2F-778C83FDEED8"
+ "MetalResources: baked icon pipeline build failed: "
+ "MetalResources: could not create a Metal command queue"
+ "MetalResources: could not load baked icon Metal functions"
+ "MetalResources: missing colour attachment on baked icon pipeline descriptor"
+ "MetalResources: no Metal device; skipping pre-baked icon header"
+ "fetchArtwork(_:handlerKey:with:compatibleWith:)"
+ "init(id:kind:titleBackingGradient:isOfTheDay:impressionMetrics:)"
+ "library-shelf-initial-batch-size"
+ "metal_shader_icons_category_brick"
+ "single"
+ "twoUp"
- "AppStoreKit.BakedIconUIView"
- "AppStoreKit/BakedIconUIView.swift"
- "BakedIconResources: baked icon pipeline build failed: "
- "BakedIconResources: could not create a Metal command queue"
- "BakedIconResources: could not load baked icon Metal functions"
- "BakedIconResources: missing colour attachment on baked icon pipeline descriptor"
- "BakedIconResources: no Metal device; skipping pre-baked icon header"
- "bakedIconFragment"
- "chiclet_lighting"
- "fetchArtwork(_:handlerKey:with:)"
- "init(id:kind:titleBackingGradient:otdTextStyle:impressionMetrics:)"
```
