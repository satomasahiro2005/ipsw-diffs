## CoreText

> `/System/Library/Frameworks/CoreText.framework/CoreText`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x51fa4` | `0x522c4` | **`+0x320`** |
| `__TEXT.__text` | `0x15fd90` | `0x15ff7c` | **`+0x1ec`** |
| `__DATA_CONST.__const` | `0xa7d8` | `0xa940` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x184a0` | `0x18600` | **`+0x160`** |
| `__TEXT.__cstring` | `0xfac6` | `0xfbc1` | **`+0xfb`** |
| `__DATA.__bss` | `0x2238` | `0x21b0` | **`-0x88`** |
| `__DATA_DIRTY.__bss` | `0xe98` | `0xf20` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x1820` | `0x1818` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x54f8` | `0x5500` | **`+0x8`** |
| `__DATA.__data` | `0x6b8` | `0x6b4` | **`-0x4`** |

### Other Changes

```diff

-906.0.0.0.0
+908.0.0.0.0

-  Functions: 5464
-  Symbols:   7715
-  CStrings:  3351
+  Functions: 5466
+  Symbols:   7717
+  CStrings:  3363
Symbols:
+ __ZL21kFontIndicGujaratiAlt
+ __ZNKSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EE7__cloneEPNS0_6__baseISB_EE
+ __ZNKSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EE7__cloneEv
+ __ZNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EE7destroyEv
+ __ZNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EED0Ev
+ __ZNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EED1Ev
+ __ZNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EEclEOS5_OhOS9_
+ __ZTVNSt3__110__function6__funcIZZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEENK3$_0clES5_S5_EUlS5_hPbE_FvS5_hS9_EEE
+ __ZZNK11COLRv1Table20RenderPaintCompositeEPKNS_5PaintERNS_11RenderStateEENK3$_0clES2_S2_
+ ____Z20MakeSpliceDescriptorPK10__CFStringmS1_S1_PK10__CFNumberS4_j23CTFontTextStylePlatformjS4_S4_22CTFontLegibilityWeightPK11__CFBooleanPKvS1__block_invoke_5
- __ZNKSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEE7__cloneEPNS0_6__baseISA_EE
- __ZNKSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEE7__cloneEv
- __ZNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEE18destroy_deallocateEv
- __ZNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEE7destroyEv
- __ZNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEED0Ev
- __ZNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEED1Ev
- __ZNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEEclEOS5_OhOS9_
- __ZTVNSt3__110__function6__funcIZNK11COLRv1Table20RenderPaintCompositeEPKNS2_5PaintERNS2_11RenderStateEE3$_0FvS5_hPbEEE
- _uscript_getScript
CStrings:
+ ".SF Gujarati Alt"
+ ".SFGujaratiAlt-Black"
+ ".SFGujaratiAlt-Bold"
+ ".SFGujaratiAlt-Heavy"
+ ".SFGujaratiAlt-Light"
+ ".SFGujaratiAlt-Medium"
+ ".SFGujaratiAlt-Regular"
+ ".SFGujaratiAlt-Semibold"
+ ".SFGujaratiAlt-Thin"
+ ".SFGujaratiAlt-Ultralight"
+ "AltGujaratiUIFont"
+ "SFGujaratiAlt.otf"
```
