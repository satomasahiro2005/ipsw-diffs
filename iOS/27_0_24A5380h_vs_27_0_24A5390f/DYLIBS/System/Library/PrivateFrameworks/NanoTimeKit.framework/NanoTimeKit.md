## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fa24c` | `0x2fd464` | **`+0x3218`** |
| `__AUTH_CONST.__objc_const` | `0x53880` | `0x53a00` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x1c38` | `0x1d70` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x1530e` | `0x1542e` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x2fef8` | `0x2fff8` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x5d08` | `0x5da8` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1dc0e` | `0x1dc9e` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xd400` | `0xd488` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x14ca0` | `0x14d10` | **`+0x70`** |
| `__TEXT.__const` | `0x5dc4` | `0x5e34` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x584` | `0x5e4` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x805` | `0x865` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x2068` | `0x20c0` | **`+0x58`** |
| `__AUTH.__objc_data` | `0xa1f0` | `0xa240` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x5954` | `0x59a0` | **`+0x4c`** |
| `__AUTH_CONST.__cfstring` | `0x20b60` | `0x20ba0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x154e` | `0x158e` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x3258` | `0x3290` | **`+0x38`** |
| `__DATA.__data` | `0x5050` | `0x5080` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xd2c` | `0xd50` | **`+0x24`** |
| `__DATA_DIRTY.__data` | `0x1368` | `0x1348` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0xe4` | `0x100` | **`+0x1c`** |
| `__DATA.__common` | `0x70` | `0x88` | **`+0x18`** |
| `__AUTH.__data` | `0x340` | `0x350` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x94` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x39a0` | `0x39a8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1b50` | `0x1b58` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x7318` | `0x7320` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-2483.503.0.0.0
+2483.512.0.0.0

-  Functions: 20270
-  Symbols:   33989
-  CStrings:  6388
+  Functions: 20308
+  Symbols:   34018
+  CStrings:  6396
Symbols:
+ +[NTKComplication(Defines) sleepScoreComplication]
+ -[NTKComplicationController _notifyTouchObserverTouchCancelled:]
+ -[NTKComplicationStyleTransitionContext .cxx_destruct]
+ -[NTKComplicationStyleTransitionContext animationCompletion]
+ -[NTKComplicationStyleTransitionContext animationSettings]
+ -[NTKComplicationStyleTransitionContext setAnimationCompletion:]
+ -[NTKComplicationStyleTransitionContext setAnimationSettings:]
+ -[NTKComplicationViewController _applyStyleIfPossibleWithTransitionContext:]
+ -[NTKComplicationViewController _applyStyleToDisplay:withTransitionContext:]
+ -[NTKComplicationViewController _batchingUpdatesToDisplay:withTransitionContext:updates:]
+ -[NTKComplicationViewController setStyle:withTransitionContext:]
+ -[NTKFace curatedGalleryBackgroundColorStops]
+ -[NTKFaceView _complicationTouchObserverForSlot:]
+ -[NTKWidgetComplicationManager widgetComplicationDeviceProvider:activeDeviceChanged:]
+ -[NTKWidgetComplicationManager widgetComplicationDeviceProviderPairedDevicesChanged:]
+ GCC_except_table289
+ GCC_except_table297
+ GCC_except_table303
+ GCC_except_table305
+ GCC_except_table310
+ GCC_except_table332
+ GCC_except_table337
+ GCC_except_table377
+ GCC_except_table384
+ GCC_except_table392
+ _OBJC_CLASS_$_NTKComplicationStyleTransitionContext
+ _OBJC_IVAR_$_NTKComplicationStyleTransitionContext._animationCompletion
+ _OBJC_IVAR_$_NTKComplicationStyleTransitionContext._animationSettings
+ _OBJC_METACLASS_$_NTKComplicationStyleTransitionContext
+ __OBJC_$_INSTANCE_METHODS_NTKComplicationStyleTransitionContext
+ __OBJC_$_INSTANCE_VARIABLES_NTKComplicationStyleTransitionContext
+ __OBJC_$_PROP_LIST_NTKComplicationStyleTransitionContext
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NTKComplicationControllerTouchObserver
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NTKWidgetComplicationDeviceProviderObserver
+ __OBJC_CLASS_RO_$_NTKComplicationStyleTransitionContext
+ __OBJC_METACLASS_RO_$_NTKComplicationStyleTransitionContext
+ __PROTOCOL_INSTANCE_METHODS_OPT_NTKWidgetComplicationDeviceProviderObserver
+ ___76-[NTKComplicationViewController _applyStyleToDisplay:withTransitionContext:]_block_invoke
+ ___89-[NTKComplicationViewController _batchingUpdatesToDisplay:withTransitionContext:updates:]_block_invoke
+ ___block_descriptor_56_e8_32s40bs48bs_e32_v16?0"CHUISTransitionContext"8ls40l8s32l8s48l8
+ ___block_descriptor_56_e8_32s40s48r_e32_v24?0"CHSWidgetExtension"8^B16ls32l8s40l8r48l8
+ ___block_descriptor_56_e8_32s40s48s_e32_v24?0"CHSWidgetExtension"8^B16ls32l8s40l8s48l8
+ ___swift_closure_destructor.132Tm
+ ___swift_closure_destructor.168Tm
+ _symbolic SDy_____AAG 10Foundation4UUIDV
+ _symbolic _____ s8DurationV
+ _symbolic ______AAt 10Foundation4UUIDV
+ _symbolic _____ySDy_____ABGG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____y_____ABG s18_DictionaryStorageC 10Foundation4UUIDV
- -[NTKComplicationViewController _applyStyleIfPossible:]
- -[NTKComplicationViewController _applyStyleToDisplay:animationCompletion:]
- -[NTKComplicationViewController _batchingUpdatesToDisplay:animationCompletion:updates:]
- GCC_except_table288
- GCC_except_table296
- GCC_except_table302
- GCC_except_table304
- GCC_except_table309
- GCC_except_table331
- GCC_except_table336
- GCC_except_table373
- GCC_except_table383
- GCC_except_table391
- ___74-[NTKComplicationViewController _applyStyleToDisplay:animationCompletion:]_block_invoke
- ___87-[NTKComplicationViewController _batchingUpdatesToDisplay:animationCompletion:updates:]_block_invoke
- ___block_descriptor_40_e8_32s_e32_v24?0"CHSWidgetExtension"8^B16ls32l8
- ___block_descriptor_48_e8_32bs40bs_e32_v16?0"CHUISTransitionContext"8ls32l8s40l8
- ___block_descriptor_48_e8_32s40r_e32_v24?0"CHSWidgetExtension"8^B16ls32l8r40l8
- ___swift_closure_destructor.133Tm
- ___swift_closure_destructor.146Tm
CStrings:
+ "Paired devices changed"
+ "Reconnect already in flight - ignoring duplicate request…"
+ "Scheduling reconnect (attempt %ld) in %s…"
+ "WidgetComplicationDeviceProvider"
+ "com.apple.NanoSleep.watchkitapp.NanoSleepWidgetExtension"
+ "com.apple.health.SleepScoreWidget"
+ "description=NanoTimeKit-2483.512"
+ "performBatchUpdateWithContext (animationCompletion=%@, animationSettings=%@)"
+ "relationshipID(forPairingID:) called with nil pairingID; returning nil"
- "description=NanoTimeKit-2483.503"
```
