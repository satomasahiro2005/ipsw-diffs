## CoreText

> `/System/Library/Frameworks/CoreText.framework/CoreText`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15c9f8` | `0x15d970` | **`+0xf78`** |
| `__TEXT.__const` | `0x51ca4` | `0x51fa4` | **`+0x300`** |
| `__DATA_DIRTY.__bss` | `0xb70` | `0xe60` | **`+0x2f0`** |
| `__DATA.__bss` | `0x2518` | `0x2238` | **`-0x2e0`** |
| `__AUTH_CONST.__cfstring` | `0x18280` | `0x18420` | **`+0x1a0`** |
| `__DATA_CONST.__const` | `0xa668` | `0xa7d8` | **`+0x170`** |
| `__TEXT.__cstring` | `0xf9a0` | `0xfab3` | **`+0x113`** |
| `__DATA_CONST.__objc_arraydata` | `0x18468` | `0x18528` | **`+0xc0`** |
| `__AUTH_CONST.__objc_dictobj` | `0x3908` | `0x3930` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x410` | `0x428` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5498` | `0x54b0` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x460` | `0x470` | **`+0x10`** |
| `__DATA.__common` | `0x4ac` | `0x4a4` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-899.0.0.0.0
+900.0.0.0.0

-  Functions: 5439
-  Symbols:   7691
-  CStrings:  3334
+  Functions: 5444
+  Symbols:   7694
+  CStrings:  3349
Symbols:
+ __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_29EE6TCFRefINT_7cf_typeEEDpOT0_
+ __ZL16RegisterFontFilePK10__CFString
+ __ZL19kFontIndicBanglaAlt
+ __ZL40kCharactersSynthesizedForMicrosoftKorean
+ __ZN12_GLOBAL__N_112PathObserver20HandleIntersectionAtEdNS0_16IntersectionTypeENS0_8LineSideEj
+ __ZN3OTL13FeatureBufferC1IPKjEET_S4_
+ __ZN5TFont25SelectOpticalStyleFromOS2EPK9TBaseFontb
+ __ZNK11TDescriptor51CreateMatchingDescriptorFromNonNormalizedDescriptorEm
+ __ZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNSt3__16vectorI6CGRectNS4_9allocatorIS6_EEEERKNS4_8functionIFvddEEE
+ __ZNK9TBaseFont16OpticalSizeValueEv
+ __ZNKSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_E7__cloneEPNS0_6__baseISE_EE
+ __ZNKSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_E7__cloneEv
+ __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_E18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_E7destroyEv
+ __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_ED0Ev
+ __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_ED1Ev
+ __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_EclEOdSK_
+ __ZNSt3__16vectorIbNS_9allocatorIbEEEC2Em
+ __ZNSt3__17__sort4B9fqn220106INS_17_ClassicAlgPolicyERNS_6__lessIvvEEPN12_GLOBAL__N_112PathObserver12IntersectionELi0EEEvT1_S9_S9_S9_T0_
+ __ZTVNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNS_6vectorI6CGRectNS_9allocatorIS8_EEEERKNS_8functionIFvddEEEE3$_0SE_EE
+ __ZZN19SyriacShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE8tagArray
+ __ZZN26JoiningScriptShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE8tagArray
+ __ZZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRNSt3__16vectorI6CGRectNS4_9allocatorIS6_EEEERKNS4_8functionIFvddEEEEN3$_18__invokeEPvPK13CGPathElement
+ __ZZNSt3__16vectorIN12_GLOBAL__N_112PathObserver12IntersectionENS_9allocatorIS3_EEE12emplace_backIJRdRNS2_16IntersectionTypeERNS2_8LineSideERjEEERS3_DpOT_ENKUlvE0_clEv
+ ____Z20MakeSpliceDescriptorPK10__CFStringmS1_S1_PK10__CFNumberS4_j23CTFontTextStylePlatformjS4_S4_22CTFontLegibilityWeightPK11__CFBooleanPKvS1__block_invoke_4
+ _kCTFontDescriptorHiddenAttribute
+ _kCTFontDescriptorNegativeAttribute
- __Z11TCFBase_NEWI16CTFontDescriptorJRPK9TBaseFont4$_28EE6TCFRefINT_7cf_typeEEDpOT0_
- __ZL14GetOpticalSizePK9TBaseFont
- __ZN12_GLOBAL__N_112PathObserver20HandleIntersectionAtEdNS0_16IntersectionTypeEj
- __ZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNSt3__18functionIFvddEEE
- __ZNK9TBaseFont20GetSynthesizedGlyphsEv
- __ZNKSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_E7__cloneEPNS0_6__baseIS8_EE
- __ZNKSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_E7__cloneEv
- __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_E18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_E7destroyEv
- __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_ED0Ev
- __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_ED1Ev
- __ZNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_EclEOdSE_
- __ZNSt3__116__if_likely_elseB9fqn220106IZNS_6vectorINS_4pairIjjEENS_9allocatorIS3_EEE12emplace_backIJRKiiEEERS3_DpOT_EUlvE_ZNS7_IJS9_iEEESA_SD_EUlvE0_EEvbT_T0_
- __ZNSt3__16vectorINS_4pairIjjEENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKiiEEEPS2_DpOT_
- __ZTVNSt3__110__function6__funcIZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNS_8functionIFvddEEEE3$_0S8_EE
- __ZZN19SyriacShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE11ltrTagArray
- __ZZN19SyriacShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE11rtlTagArray
- __ZZN26JoiningScriptShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE11ltrTagArray
- __ZZN26JoiningScriptShapingEngine11SetFeaturesERKN3OTL4GSUBERNS0_12GlyphLookupsEE11rtlTagArray
- __ZZN5TFont14SetOpticalSizeEPK18__CTFontDescriptorENK3$_0clEPK9TBaseFont
- __ZZNK14TDecorationRun27CalculateGlyphIntersectionsE17CGAffineTransformRK4TRunddRKNSt3__18functionIFvddEEEEN3$_18__invokeEPvPK13CGPathElement
- __ZZNSt3__16vectorIN12_GLOBAL__N_112PathObserver12IntersectionENS_9allocatorIS3_EEE12emplace_backIJRdRNS2_16IntersectionTypeERjEEERS3_DpOT_ENKUlvE0_clEv
- _kCTFontShapingGlyphsForFeatureSettingsAttribute
- _kCTFontVerticalShapingGlyphsForFeatureSettingsAttribute
CStrings:
+ ".SF Bangla Alt"
+ ".SFBanglaAlt"
+ ".SFBanglaAlt-Black"
+ ".SFBanglaAlt-Bold"
+ ".SFBanglaAlt-Heavy"
+ ".SFBanglaAlt-Light"
+ ".SFBanglaAlt-Medium"
+ ".SFBanglaAlt-Regular"
+ ".SFBanglaAlt-Semibold"
+ ".SFBanglaAlt-Thin"
+ ".SFBanglaAlt-Ultralight"
+ ".SFThaiLooped"
+ "AllowMixedThaiFontStyles"
+ "AltBanglaUIFont"
+ "SFBanglaAlt.otf"
+ "SFTamilAlt.otf"
+ "SFThai.ttc"
- "%@SFTamilAlt.otf"
- "%@SFThai.ttc"
```
