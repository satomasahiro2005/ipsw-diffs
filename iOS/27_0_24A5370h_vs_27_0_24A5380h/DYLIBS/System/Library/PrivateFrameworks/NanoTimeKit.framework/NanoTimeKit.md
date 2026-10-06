## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xe5f8` | `0xa1f0` | **`-0x4408`** |
| `__DATA_DIRTY.__objc_data` | `0x2f10` | `0x7318` | **`+0x4408`** |
| `__DATA_DIRTY.__bss` | `0x1e90` | `0x4b60` | **`+0x2cd0`** |
| `__DATA.__bss` | `0x87b0` | `0x5b50` | **`-0x2c60`** |
| `__DATA_DIRTY.__data` | `0x3b0` | `0x1368` | **`+0xfb8`** |
| `__DATA.__data` | `0x5808` | `0x5050` | **`-0x7b8`** |
| `__AUTH.__data` | `0xae0` | `0x340` | **`-0x7a0`** |
| `__TEXT.__text` | `0x2f9be0` | `0x2fa24c` | **`+0x66c`** |
| `__TEXT.__oslogstring` | `0x1527e` | `0x1530e` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x5cb8` | `0x5d08` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x5904` | `0x5954` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x20b20` | `0x20b60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1dbce` | `0x1dc0e` | **`+0x40`** |
| `__DATA.__common` | `0xa8` | `0x70` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x50` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x1c68` | `0x1c38` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0xd420` | `0xd400` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x53868` | `0x53880` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xbe08` | `0xbe18` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2ff08` | `0x2fef8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x574` | `0x584` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2060` | `0x2068` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3260` | `0x3258` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x1556` | `0x154e` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x399c` | `0x39a0` | **`+0x4`** |
| `__TEXT.__swift5_reflstr` | `0x808` | `0x805` | **`-0x3`** |

### Other Changes

```diff

-2483.493.1.0.0
+2483.503.0.0.0

-  Functions: 20264
-  Symbols:   33986
-  CStrings:  6384
+  Functions: 20270
+  Symbols:   33989
+  CStrings:  6388
Symbols:
+ -[NTKFaceView(Siri) siriDidDismiss]
+ -[NTKFaceView(Siri) siriDidPresent]
+ GCC_except_table67
+ _NTKDebugRegisterForSiriPresentationDarwinNotifications
+ _NTKSiriDidDismissNotification
+ _NTKSiriDidPresentNotification
+ _OBJC_IVAR_$_NTKSiderealDataSource._dayChangedObserver
+ _OBJC_IVAR_$_NTKSiderealDataSource._significantTimeChangeObserver
+ _OBJC_IVAR_$_NTKSiderealDataSource._timeZoneObserver
+ __OBJC_$_CLASS_METHODS_NTKFaceBundle(Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|FaceGeneration|DynamicCollectionAdditions)
+ __OBJC_$_INSTANCE_METHODS_NTKFaceBundle(Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|FaceGeneration|DynamicCollectionAdditions)
+ __OBJC_$_INSTANCE_METHODS_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|Siri|ComplicationColor|NTKSColorPaletteAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|Siri|ComplicationColor|NTKSColorPaletteAdditions)
+ __UIUnitClamp
+ ___36-[NTKSiderealDataSource initWithXR:]_block_invoke_2
+ ___36-[NTKSiderealDataSource initWithXR:]_block_invoke_3
+ _swift_release_x27
+ _symbolic _____ s13OpaquePointerV
+ _symbolic _____ySo11NSHashTableCy______pGG 15Synchronization5MutexVAARi_zrlE 11NanoTimeKit40WidgetComplicationDeviceProviderObserverP
- -[NTKFaceViewController faceViewWantsStatusBarHiddenForLPR:]
- -[NTKFaceViewController statusBarDidChange]
- GCC_except_table174
- _OBJC_IVAR_$_NTKFaceViewController._isApplyingStatusBarHiddenForLPR
- _OBJC_IVAR_$_NTKFaceViewController._statusBarHiddenForLPR
- __OBJC_$_CLASS_METHODS_NTKFaceBundle(FaceGeneration|Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|DynamicCollectionAdditions)
- __OBJC_$_INSTANCE_METHODS_NTKFaceBundle(FaceGeneration|Internal|FaceSupport|Support|Markdown|ShareSheetCreation|DebugMenu|DynamicCollectionAdditions)
- __OBJC_$_INSTANCE_METHODS_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NTKFaceView(NTKSMetadataProviding|GalleryComplicationFactoryAdditions|ComplicationColor|NTKSColorPaletteAdditions)
- _get_type_metadata 15Synchronization5MutexVySSSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScTyyts5NeverOGSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo11NSHashTableCy11NanoTimeKit40WidgetComplicationDeviceProviderObserver_pGG noncopyable
- _get_type_metadata 15Synchronization5MutexVyyyYbcG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
- _symbolic _____ySo11NSHashTableCG 15Synchronization5MutexVAARi_zrlE
CStrings:
+ "NTKSiriDidDismissNotification"
+ "NTKSiriDidPresentNotification"
+ "Skipping selected-face snapshot: face is nil or restricted for its device"
+ "[NTKSiderealDataSource] _updateForSignificantTimeChange: handling %@"
+ "description=NanoTimeKit-2483.503"
+ "\xf0\xf0B"
- "description=NanoTimeKit-2483.493.1"
- "\xf0\xf0R"
```
