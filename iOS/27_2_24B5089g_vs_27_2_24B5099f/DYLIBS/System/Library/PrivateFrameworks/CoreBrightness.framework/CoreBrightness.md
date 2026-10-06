## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17d528` | `0x17f5a8` | **`+0x2080`** |
| `__TEXT.__oslogstring` | `0x1aefd` | `0x1b59d` | **`+0x6a0`** |
| `__AUTH_CONST.__objc_const` | `0x392c0` | `0x394c0` | **`+0x200`** |
| `__TEXT.__gcc_except_tab` | `0x28e8` | `0x2a40` | **`+0x158`** |
| `__TEXT.__objc_methlist` | `0xde50` | `0xdf50` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0xedc0` | `0xee80` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xd345` | `0xd3d5` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d70` | `0x5de8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x5968` | `0x59c8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3220` | `0x3270` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1888` | `0x18b4` | **`+0x2c`** |
| `__TEXT.__const` | `0x1b6e0` | `0x1b6c8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x7e8` | `0x7f8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xade` | `0xace` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-2300.40.39.0.0
+2300.40.47.0.4

-  Functions: 9094
-  Symbols:   10737
-  CStrings:  4877
+  Functions: 9138
+  Symbols:   10779
+  CStrings:  4916
Symbols:
+ -[BrightnessSystemClient observerSlug:]
+ -[BrightnessSystemClient refreshKeys]
+ -[CBDisplayBrightnessClient description]
+ -[CBDisplayClient description]
+ -[CBDisplayTransitionPolicy isDeviceStableOpen]
+ -[CBDisplayTransitionPolicy isSourceSettled:target:]
+ -[CBDisplayTransitionPolicy isTopToBottomHandoffFromSource:toTarget:]
+ -[CBDisplayTransitionPolicy panelPlacementForContainer:]
+ -[CBDisplayTransitionPolicy updateAngle:]
+ -[CBIndicatorBrightnessModule registerForThermalPressureNotifications]
+ -[CBIndicatorBrightnessModule thermalPressureNotificationHandler:]
+ -[CBPreset alwaysRequestMaxHeadroom]
+ -[CBPreset maxPotentialEDRHeadroom]
+ -[CBPresetsParser alwaysRequestMaxHeadroom:]
+ -[CBPresetsParser maxPotentialEDRHeadroomForDisplay:]
+ -[CBSystemContext frameInfoProvider]
+ -[CBSystemContext setFrameInfoProvider:]
+ -[NSArray(PrimitiveDataProvider) copyFloatVector]
+ -[NSSet(PrettyDescription) prettyDescription]
+ GCC_except_table101
+ GCC_except_table111
+ GCC_except_table120
+ GCC_except_table140
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table153
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table169
+ GCC_except_table198
+ GCC_except_table42
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table84
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_IVAR_$_BLControl._transitionPolicy
+ _OBJC_IVAR_$_BrightnessSystemClient._observedKeys
+ _OBJC_IVAR_$_BrightnessSystemClient._observersCount
+ _OBJC_IVAR_$_CBAODModule._alsNodes
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._currentAngleDegrees
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._hasAngleSample
+ _OBJC_IVAR_$_CBDisplayTransitionPolicy._lastAngleBelowCriticalThresholdTime
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressure
+ _OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressureNotificationToken
+ _OBJC_IVAR_$_CBPreset._alwaysRequestMaxHeadroom
+ _OBJC_IVAR_$_CBPreset._maxPotentialEDRHeadroom
+ _OBJC_IVAR_$_CBSystemContext._frameInfoProvider
+ _OUTLINED_FUNCTION_35
+ _OUTLINED_FUNCTION_36
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSSet_$_PrettyDescription
+ __OBJC_$_CATEGORY_NSSet_$_PrettyDescription
+ __OBJC_$_PROP_LIST_NSSet_$_PrettyDescription
+ __ZN14CoreBrightness19lookupValueWithAxisIfEET_NSt3__16vectorIS1_NS2_9allocatorIS1_EEEES6_S1_
+ __ZN4AABC22BrightnessRestrictionsD2Ev
+ __ZN4AABC39BrightnessRestrictionMultiPointValues_saSERKS0_
+ ___70-[CBIndicatorBrightnessModule registerForThermalPressureNotifications]_block_invoke
+ ___block_descriptor_108_e8_32o40r_e23_v24?0"CBALSNode"8^B16ls32l8r40l8
+ ___block_descriptor_40_e8_32b_e33_v16?0r^{?=IIQQQQIBBBfffQIBQQfB}8ls32l8
+ ___block_descriptor_40_e8_32r_e8_v12?0i8lr32l8
+ ___block_descriptor_49_e8_32o40o_e15_v32?08Q16^B24ls32l8s40l8
+ _kOSThermalNotificationPressureLevelName
- -[CBDisplayTransitionPolicy isSourceSettled:]
- GCC_except_table110
- GCC_except_table119
- GCC_except_table134
- GCC_except_table139
- GCC_except_table141
- GCC_except_table142
- GCC_except_table149
- GCC_except_table154
- GCC_except_table155
- GCC_except_table194
- GCC_except_table39
- GCC_except_table62
- GCC_except_table67
- GCC_except_table70
- GCC_except_table83
- _OBJC_IVAR_$_CBAODModule._alsServiceClients
- ___block_descriptor_108_e8_32o40r_e33_v32?0"HIDServiceClient"8Q16^B24ls32l8r40l8
- ___block_descriptor_40_e8_32b_e32_v16?0r^{?=IIQQQQIBBBfffQIBQQf}8ls32l8
CStrings:
+ "%@<%@>"
+ "%@@%@ with %@"
+ "-[BrightnessSystemClient unregisterObserver:]"
+ "Display on seeded by handoff — skipping snap to own curve"
+ "DisplayPanelPlacement"
+ "EXBrightSILStateTrusted"
+ "Ignoring %{public}@: expected %zu levels, got %lu"
+ "Ignoring %{public}@: not ascending: %{public}@"
+ "IlluminanceToLuminanceAggregated_AOD: nits cap = %f, ceiling = %f, AOD L = %f >>> L %f"
+ "Initial thermal pressure level: %llu"
+ "Loaded Restriction Dictionary (Dynamic Slider Configuration) from defaults (StoreDemoMode = %d): %@"
+ "Presets(%lu): always request max headroom = %d"
+ "Presets(%lu): maxPotentialEDRHeadroom: %@"
+ "Semantic ambient lux levels: %{public}@"
+ "Thermal Pressure Critical! Snapping to target indicator brightness %f"
+ "Thermal pressure level changed: %llu -> %llu"
+ "[%@]"
+ "[Dynamic Slider] MAX - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MAX - missing thresholds or factors"
+ "[Dynamic Slider] MAX - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MAX - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MAX - thresholds or factors are not arrays"
+ "[Dynamic Slider] MAX - thresholds or factors not sorted in ascending order"
+ "[Dynamic Slider] MIN - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MIN - missing thresholds or factors"
+ "[Dynamic Slider] MIN - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MIN - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MIN - thresholds or factors are not arrays"
+ "[Dynamic Slider] MIN - thresholds or factors not sorted in ascending order"
+ "[Handoff] angle at %.0f degrees, no dip below %.0f degrees for %.1fs - not a hinge-open motion, skipping grace period, fast-ramping target instead"
+ "[Handoff] source is exiting AOD - skipping grace period, fast-ramping target instead"
+ "[Handoff] source is in fast ramp - skipping grace period, fast-ramping target instead"
+ "[Observer] Adding %@"
+ "[Observer] Not adding %@ - no observable properties"
+ "[Observer] Observed keys 🔑: %@ - %@ + %@ = %@"
+ "[Observer] Refreshing %@"
+ "[Observer] Removing %@ since the set of properties become empty."
+ "[Observer] Unregistering %@"
+ "[dcpRoleID=%d] [ReadBack] Couldn't fetch SIL state!"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d, sessionID=%u"
+ "[dcpRoleID=%d] [WillSend] SIL=%d"
+ "[dcpRoleID=%d] [WillSend] SIL=%d failed!"
+ "com.apple.demo-settings"
+ "crgb lookup: found=%d parsed=%d value=%d"
+ "notify_get_state failed with %d for token %d"
+ "notify_register_dispatch failed with %d for %s"
+ "semantic-lux-levels"
+ "v16@?0r^{?=IIQQQQIBBBfffQIBQQfB}8"
+ "v24@?0@\"CBALSNode\"8^B16"
- "/var/mobile/Library/Preferences/com.apple.demo-settings"
- "BrightnessRestrictions were loaded from CFPreferences (StoreDemoMode = %s)"
- "Failed to load BrightnessRestrictions from CFPreferences (StoreDemoMode = %s)"
- "IlluminanceToLuminanceAggregated_AOD: E(Lux) = %f | normal L(Nits) = %f | restricted normal L(Nits) = %f | AOD L(Nits) = %f >>> L %f"
- "Registered observer %@ with handle %@, properties %@. Subscribing to the following new keys: %@"
- "Removing observer %@ with handle %@. Unregistering the following keys: %@"
- "[Handoff] source exiting AOD, not settled"
- "[Handoff] source in fast ramp, not settled"
- "[Handoff] source not settled - skip grace period"
- "[dcpRoleID=%d] SIL=%d, monotonicTimeUS=%llu. Sending to EXBright: %@."
- "v16@?0r^{?=IIQQQQIBBBfffQIBQQf}8"
```
