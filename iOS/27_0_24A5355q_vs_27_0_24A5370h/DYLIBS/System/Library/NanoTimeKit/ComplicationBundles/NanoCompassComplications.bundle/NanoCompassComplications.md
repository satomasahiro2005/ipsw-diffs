## NanoCompassComplications

> `/System/Library/NanoTimeKit/ComplicationBundles/NanoCompassComplications.bundle/NanoCompassComplications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3edf8` | `0x3df04` | **`-0xef4`** |
| `__TEXT.__cstring` | `0x3bf3` | `0x3903` | **`-0x2f0`** |
| `__TEXT.__oslogstring` | `0x40c4` | `0x3e33` | **`-0x291`** |
| `__AUTH_CONST.__objc_const` | `0x70a0` | `0x6f78` | **`-0x128`** |
| `__TEXT.__objc_methlist` | `0x3ca0` | `0x3bf0` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x3140` | `0x30a0` | **`-0xa0`** |
| `__TEXT.__gcc_except_tab` | `0xa98` | `0xa24` | **`-0x74`** |
| `__DATA_CONST.__objc_selrefs` | `0x2438` | `0x23d8` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x18c8` | `0x1878` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xdb8` | `0xd68` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x1128` | `0x10d8` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0xa40` | `0xa20` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x680` | `0x668` | **`-0x18`** |
| `__DATA.__bss` | `0x998` | `0x988` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x52c` | `0x51c` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x558` | `0x550` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2a8` | `0x2a0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1c8` | `0x1c0` | **`-0x8`** |

### Other Changes

```diff

-692.0.0.0.0
+696.0.0.0.0

-  Functions: 1625
-  Symbols:   684
-  CStrings:  839
+  Functions: 1598
+  Symbols:   674
+  CStrings:  813
Symbols:
- _CFPreferencesGetAppBooleanValue
- _NSRunLoopCommonModes
- _OBJC_CLASS_$_NCLocationUpdateNonRhythmicGNSSDelegate
- _OBJC_CLASS_$_NSRunLoop
- _OBJC_CLASS_$_NSTimer
- _OBJC_METACLASS_$_NCLocationUpdateNonRhythmicGNSSDelegate
- _hardwareSupportsAbsoluteAltimeter
- _supportAbsoluteAltimeterFeatures
- _supportsAltimeterOverride
- _supportsOrienteering
CStrings:
+ "-[NCGuidesManager _handleGuideStateChangedInClockFace:]"
+ "Skipping altimeter update. CMAltimeter is not supported. Dash will show in UI."
+ "altimeter manager is initialized. This device is authorized"
+ "v32@?0@\"NCManagerLocationToken\"8@?<v@?@\"NCLocation\">16^B24"
- "%s Location update is still running but we are out of runtime. Fire locationQueryDurationTimer now to stop location update."
- "%s Location update should end. Set the idle time to restart location update."
- "%s cancelling runtime assertion"
- "%s failed to take assertion: %@"
- "%s idle timer fired and restart location update"
- "%s invalidate location timers and assertion"
- "%s location update should not start as the app is in the background"
- "%s runtime assertion invalidated. error: %@"
- "%s runtime assertion is about to expire"
- "%s taking runtime assertion for updating location for %.0fs"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _cancelLocationAssertion]"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _idleTimerFired:]"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _invalidateLocationTimersAndAssertion]"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _startIdleTimer]"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _startLocationQueryDurationTimer]_block_invoke"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _takeLocationAssertion]"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _takeLocationAssertion]_block_invoke"
- "-[NCLocationUpdateNonRhythmicGNSSDelegate _takeLocationAssertion]_block_invoke_2"
- "Absolute altimeter support is overridden to %@"
- "AbsoluteAltitudeEnabled"
- "DeviceSupportsCompassOrienteering"
- "Periodic runtime to keep location fresh"
- "Received better altitude update."
- "absolute altimeter is not available on this device."
- "altimeter manager is initialized. This device supports the absolute altitude and is authorized"
- "com.apple.NanoCompass.location.nonRhythmicGNSSWake"
- "com.apple.locationd"
- "v16@?0@\"NSTimer\"8"
- "v16@?0@\"RBSAssertion\"8"
- "v32@?0@\"NCManagerLocationToken\"8@?<v@?@\"NCLocation\"@\"NCAltitude\">16^B24"
```
