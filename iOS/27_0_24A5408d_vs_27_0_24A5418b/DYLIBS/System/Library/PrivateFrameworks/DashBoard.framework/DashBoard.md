## DashBoard

> `/System/Library/PrivateFrameworks/DashBoard.framework/DashBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x306004` | `0x30556c` | **`-0xa98`** |
| `__TEXT.__cstring` | `0xde67` | `0xdbe7` | **`-0x280`** |
| `__TEXT.__eh_frame` | `0x461c` | `0x4734` | **`+0x118`** |
| `__AUTH.__objc_data` | `0xebc0` | `0xeb00` | **`-0xc0`** |
| `__TEXT.__objc_methlist` | `0x17adc` | `0x17a2c` | **`-0xb0`** |
| `__DATA_CONST.__const` | `0x3850` | `0x38f0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x52fd8` | `0x52f68` | **`-0x70`** |
| `__TEXT.__oslogstring` | `0x1911c` | `0x190ac` | **`-0x70`** |
| `__TEXT.__swift5_capture` | `0x2ffc` | `0x304c` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x8700` | `0x8740` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2f40` | `0x2f00` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1a5c` | `0x1a9c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xbbf8` | `0xbbb8` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xd130` | `0xd0f8` | **`-0x38`** |
| `__DATA.__bss` | `0x96c8` | `0x9698` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x5557` | `0x5527` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x72b0` | `0x7284` | **`-0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x36f8` | `0x3720` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xcc70` | `0xcc98` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x44b8` | `0x4490` | **`-0x28`** |
| `__DATA.__common` | `0x3d8` | `0x3b8` | **`-0x20`** |
| `__TEXT.__const` | `0xd874` | `0xd864` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x9960` | `0x9950` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x1f4` | `0x200` | **`+0xc`** |
| `__AUTH.__data` | `0x3730` | `0x3728` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb50` | `0xb48` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x660` | `0x65c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x130` | `0x134` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x114` | `0x118` | **`+0x4`** |

### Other Changes

```diff

-581.7.1.0.0
+581.7.2.0.0

+  - /usr/lib/libtailspin.dylib

-  Functions: 15622
-  Symbols:   14486
-  CStrings:  3702
+  Functions: 15599
+  Symbols:   14481
+  CStrings:  3688
Symbols:
+ -[DBDashboard _collectTailspinForTapToRadarWithCompletion:]
+ GCC_except_table113
+ GCC_except_table117
+ GCC_except_table124
+ GCC_except_table135
+ GCC_except_table218
+ GCC_except_table231
+ GCC_except_table275
+ GCC_except_table277
+ GCC_except_table282
+ GCC_except_table283
+ _NSTemporaryDirectory
+ _OBJC_CLASS_$_NSFileHandle
+ _TSPDumpOptions_CollectOsLogs
+ _TSPDumpOptions_CollectOsSignposts
+ _TSPDumpOptions_ReasonString
+ _TSPDumpOptions_Symbolicate
+ ___37-[DBDashboard _handleTapToRadarEvent]_block_invoke_7
+ ___59-[DBDashboard _collectTailspinForTapToRadarWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e15_v16?0"NSURL"8lr40l8s32l8
+ ___block_descriptor_56_e8_32s40s48r_e22_v16?0"NSDictionary"8ls32l8s40l8r48l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e15_v16?0"NSURL"8ls32l8s40l8r72l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e5_v8?0ls32l8s40l8r72l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e5_v8?0ls32l8s40l8s48l8r72l8s56l8s64l8
+ ___swift_closure_destructor.29Tm
+ _symbolic ScTyyt_____GSgz_Xx s5NeverO
+ _tailspin_config_create_with_current_state
+ _tailspin_config_free
+ _tailspin_dump_output_with_options_sync
+ _tailspin_enabled_get
- GCC_except_table108
- GCC_except_table112
- GCC_except_table116
- GCC_except_table132
- GCC_except_table215
- GCC_except_table228
- GCC_except_table272
- GCC_except_table274
- GCC_except_table279
- GCC_except_table280
- _OBJC_CLASS_$_UIApplication
- _OBJC_CLASS_$_UIScene
- _OBJC_CLASS_$__TtC9DashBoard24DBC2AnimationDiagnostics
- _OBJC_METACLASS_$__TtC9DashBoard24DBC2AnimationDiagnostics
- _UIApplicationDidBecomeActiveNotification
- _UIApplicationDidEnterBackgroundNotification
- _UIApplicationWillEnterForegroundNotification
- _UIApplicationWillResignActiveNotification
- _UISceneDidActivateNotification
- _UISceneDidDisconnectNotification
- _UISceneDidEnterBackgroundNotification
- _UISceneWillConnectNotification
- _UISceneWillDeactivateNotification
- _UISceneWillEnterForegroundNotification
- __CLASS_METHODS__TtC9DashBoard24DBC2AnimationDiagnostics
- __DATA__TtC9DashBoard24DBC2AnimationDiagnostics
- __INSTANCE_METHODS__TtC9DashBoard24DBC2AnimationDiagnostics
- __IVARS__TtC9DashBoard24DBC2AnimationDiagnostics
- __METACLASS_DATA__TtC9DashBoard24DBC2AnimationDiagnostics
- ___block_descriptor_64_e8_32s40s48s56s_e15_v16?0"NSURL"8ls32l8s40l8s48l8s56l8
- ___swift_closure_destructor.33Tm
- _symbolic SS_So6UIViewCSgt
- _symbolic So11NSHashTableCySo13UIWindowSceneCG
- _symbolic _____ 9DashBoard24DBC2AnimationDiagnosticsC
- _symbolic _____ySS_So6UIViewCSgtG s23_ContiguousArrayStorageC
CStrings:
+ "CarPlay Tap-to-Radar"
+ "CarPlay.tailspin"
+ "Collected tailspin for Tap-to-Radar at %{public}@."
+ "Collecting tailspin for Tap-to-Radar."
+ "Could not reach tailspind; skipping tailspin capture for Tap-to-Radar."
+ "Error creating temporary directory for CarPlay tailspin: %@"
+ "Failed to open output file for CarPlay tailspin %{public}@: %@"
+ "Failed to save CarPlay tailspin to %{public}@."
+ "Tailspin is not enabled; skipping capture for Tap-to-Radar."
+ "TapToRadarTailspin"
+ "Zoom %s animation did not complete within %fs, force completing it."
- ", windowScene=nil"
- "C2 animations WOULD BE SUSPENDED after %s: app is suspended and no observed screen-based scene is foreground. New C2 animations will not start or complete until this clears."
- "DBSwitcherGenieEffectView committed a genie animation while its container was detached so window/screen is nil. Its animatable properties resolved to the UIScreen._main"
- "DBSwitcherZoomAnimator isActive=%{bool}d view=%s %s"
- "Started C2 animation lifecycle diagnostics"
- "[%s] scene=%s appSuspended=%{bool}d observedScreenBasedScenes=%ld {%s} anyForeground=%{bool}d wouldSuspendAnimations=%{bool}d"
- "_UIScreenBasedWindowSceneDidAttachWindowNotification"
- "app.didBecomeActive"
- "app.didEnterBackground"
- "app.willEnterForeground"
- "app.willResignActive"
- "appContentContainer"
- "appTransitionContainerView"
- "detached (no window)"
- "foregroundActive"
- "foregroundInactive"
- "iconOverlayAccessoryView"
- "rootContainerView"
- "scene.didActivate"
- "scene.didDisconnect"
- "scene.didEnterBackground"
- "scene.willConnect"
- "scene.willDeactivate"
- "scene.willEnterForeground"
- "screenBasedWindowScene.didAttachWindow"
```
