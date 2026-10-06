## BookEPUB

> `/private/var/staged_system_apps/Books.app/Frameworks/BookEPUB.framework/BookEPUB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27f7ac` | `0x27fa18` | **`+0x26c`** |
| `__TEXT.__oslogstring` | `0xc643` | `0xc7d3` | **`+0x190`** |
| `__DATA.__objc_data` | `0x5758` | `0x5680` | **`-0xd8`** |
| `__DATA_CONST.__const` | `0x157f0` | `0x15750` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x14478` | `0x14508` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x9578` | `0x9524` | **`-0x54`** |
| `__DATA.__data` | `0xce28` | `0xcde8` | **`-0x40`** |
| `__DATA.__objc_const` | `0x10d28` | `0x10ce8` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0xa900` | `0xa940` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x4230` | `0x4260` | **`+0x30`** |
| `__TEXT.__const` | `0x1e1e0` | `0x1e1b0` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x1e0e` | `0x1dde` | **`-0x30`** |
| `__TEXT.__cstring` | `0x90a1` | `0x9081` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6aed` | `0x6acd` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x5d88` | `0x5d6c` | **`-0x1c`** |
| `__TEXT.__auth_stubs` | `0x3e20` | `0x3e30` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7020` | `0x7010` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1f28` | `0x1f30` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe00` | `0xdf8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x528` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x5898` | `0x5890` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x2388` | `0x2380` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x66c6` | `0x66c0` | **`-0x6`** |
| `__TEXT.__swift5_types` | `0x4c8` | `0x4c4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6643.0.0.0.0
+6647.0.0.0.0

-  Functions: 11375
+  Functions: 11362

-  CStrings:  5813
+  CStrings:  5818
Symbols:
+ _NSStringFromCGSize
+ _OBJC_CLASS_$_UIGlassEffect
+ _OBJC_CLASS_$_UIVisualEffectView
- _OBJC_CLASS_$_CABackdropLayer
- _kCAFilterColorSaturate
- _kCAFilterGaussianBlur
CStrings:
+ "#cover installed cover on webView %{public}s ordinal %ld"
+ "#cover move(to:) presentation state webView:%{public}s alpha:%f hasSuperview:%{bool}d hasCover:%{bool}d contentSize:%s"
+ "Loader %{public}s recovery reload finished but can't repaginate (layoutProvider:%{bool}d document:%{bool}d); applying layout only"
+ "Loader %{public}s repaginate after recovery reload failed: %{public}s"
+ "alpha"
+ "be_setContentOffset - contentSize %{public}@ does not yet contain %{public}@; deferring to next layer-tree commit for WebView:%{public}@"
+ "effectWithStyle:"
+ "grammarCheckingType"
+ "initWithEffect:"
+ "preferKeyboardInput"
+ "setGrammarCheckingType:"
+ "setPreferKeyboardInput:"
+ "topEdgeEffect"
- "T#,N,R"
- "Unable to get pageLength from layoutProvider -- applyingOffset"
- "_TtC8BookEPUB28ChromeMaterialBackgroundView"
- "contentLength is %f but a size more like %f seems more plausible. we compared %f against %f"
- "inputNormalizeEdges"
- "isInRotationTransition"
- "layerClass"
- "setScale:"
```
