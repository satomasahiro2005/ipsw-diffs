## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1092f0` | `0x10a748` | **`+0x1458`** |
| `__TEXT.__oslogstring` | `0xb` | `0x53a` | **`+0x52f`** |
| `__TEXT.__const` | `0x78c` | `0x8bc` | **`+0x130`** |
| `__TEXT.__ustring` | `0x2b4` | `0x3c8` | **`+0x114`** |
| `__AUTH_CONST.__objc_const` | `0x12b20` | `0x12bd8` | **`+0xb8`** |
| `__AUTH_CONST.__cfstring` | `0xcae0` | `0xcb60` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x3540` | `0x35b4` | **`+0x74`** |
| `__TEXT.__cstring` | `0x102c3` | `0x10269` | **`-0x5a`** |
| `__AUTH.__objc_data` | `0x12c0` | `0x1310` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x12d8` | `0x1318` | **`+0x40`** |
| `__DATA.__bss` | `0x820` | `0x860` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x9240` | `0x9268` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x12e8` | `0x1308` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xbb9c` | `0xbbbc` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3fe0` | `0x4000` | **`+0x20`** |
| `__AUTH.__thread_vars` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x68f0` | `0x6900` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x480` | `0x488` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x420` | `0x428` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x131c` | `0x1320` | **`+0x4`** |
| `__AUTH.__thread_bss` | `—` | `0x1` | **`+0x1`** |
| `__DATA.__common` | `—` | `0x1` | **`+0x1`** |

### Other Changes

```diff

-1056.0.0.0.0
+1057.1.0.0.0

-  Functions: 5352
-  Symbols:   9342
-  CStrings:  3220
+  Functions: 5367
+  Symbols:   9375
+  CStrings:  3248
Symbols:
+ -[UIFoundationInstrumentationEventObservation _initWithToken:]
+ -[UIFoundationInstrumentationEventObservation dealloc]
+ _OBJC_CLASS_$_UIFoundationInstrumentationEventObservation
+ _OBJC_IVAR_$_UIFoundationInstrumentationEventObservation._token
+ _OBJC_METACLASS_$_UIFoundationInstrumentationEventObservation
+ __OBJC_$_INSTANCE_METHODS_UIFoundationInstrumentationEventObservation
+ __OBJC_$_INSTANCE_VARIABLES_UIFoundationInstrumentationEventObservation
+ __OBJC_CLASS_RO_$_UIFoundationInstrumentationEventObservation
+ __OBJC_METACLASS_RO_$_UIFoundationInstrumentationEventObservation
+ ___UIFoundationCreateAllLogObjects.once
+ ___UIFoundationDynamicLogCache
+ ___UIFoundationDynamicLogCacheLock
+ ___UIFoundationInstrumentationEventAnySinkActiveFlag
+ ___UIFoundationInstrumentationEventEmit
+ ___UIFoundationInstrumentationEventEmit.inEmit
+ ___UIFoundationInstrumentationEventEmit.inEmit$tlv$init
+ ___UIFoundationInstrumentationEventEnsureInit
+ ___UIFoundationInstrumentationEventEnsureInit.once
+ ___UIFoundationInstrumentationEventObservers
+ ___UIFoundationInstrumentationEventRemoveObserver
+ ___UIFoundationInstrumentationEventSequence
+ ___UIFoundationLogGeneral
+ ___UIFoundationLogScrolling
+ ___UIFoundationLogStringDrawing
+ ___UIFoundationSignpostSinkEnabled
+ ___UIFoundationWriteLogDynamic
+ _____UIFoundationCreateAllLogObjects_block_invoke
+ _____UIFoundationInstrumentationEventEnsureInit_block_invoke
+ ___block_descriptor_66_e8_32r40r_e50_v32?0"NSTextLayoutFragment"8"NSTextRange"16^B24lr32l8r40l8
+ ___block_descriptor_73_e8_32o40r48r56r64r_e30_B16?0"NSTextLayoutFragment"8lr40l8s32l8r48l8r56l8r64l8
+ __os_signpost_emit_with_name_impl
+ __tlv_bootstrap
+ _log_General
+ _log_Scrolling
+ _log_StringDrawing
+ _mach_absolute_time
+ _os_signpost_enabled
+ _os_signpost_id_make_with_pointer
- ___UIFoundationWriteLog
- ___UIFoundationWriteLog.onceToken
- ___UIFoundationWriteLog.uifoundationLog
- _____UIFoundationWriteLog_block_invoke
- ___block_descriptor_57_e8_32r_e50_v32?0"NSTextLayoutFragment"8"NSTextRange"16^B24lr32l8
CStrings:
+ "ContentHeightEstimate"
+ "EnableScrollingSignposts"
+ "FragmentCreate"
+ "FragmentEstimate"
+ "FragmentHeightResolved"
+ "FragmentInvalidate"
+ "FragmentLayout"
+ "PositionMapping"
+ "ScrollAnchor"
+ "Scrolling"
+ "UIFoundationInstrumentationEvent observer re-entered the emit funnel — observers must not trigger layout/emit; marshal to your own queue."
+ "UIFoundationLogging.m"
+ "ViewportLayout"
+ "ViewportOffsetDelta"
+ "ViewportRestore"
+ "bounds={%{public}f,%{public}f,%{public}f,%{public}f} offset={%{public}f,%{public}f}"
+ "entryState=%{public}u viewportController=%{public}#llx"
+ "estimatedHeight=%{public}f actualHeight=%{public}f heightDelta=%{public}f"
+ "estimatedHeight=%{public}f frameY=%{public}f"
+ "estimatedHeight=%{public}f realHeight=%{public}f elementCount=%{public}llu lastFragmentEstimated=%{public}u"
+ "frameY=%{public}f frameHeight=%{public}f viewportController=%{public}#llx"
+ "path=%{public}u anchorLayoutY=%{public}f anchorLocationOffset=%{public}lld"
+ "positionY=%{public}f skippedStateNoneCount=%{public}llu resolvedFrameY=%{public}f resolvedState=%{public}u"
+ "priorState=%{public}u discardedHeight=%{public}f"
+ "reason=%{public}u preOriginY=%{public}f postOriginY=%{public}f verticalDelta=%{public}f"
+ "viewportController=%{public}#llx"
+ "viewportOrigin={%{public}f,%{public}f} layoutRectOrigin={%{public}f,%{public}f} delta={%{public}f,%{public}f}"
+ "void __UIFoundationInstrumentationEventEmit(const UIFoundationInstrumentationEvent *)"
```
