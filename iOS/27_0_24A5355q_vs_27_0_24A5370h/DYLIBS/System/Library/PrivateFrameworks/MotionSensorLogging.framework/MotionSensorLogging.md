## MotionSensorLogging

> `/System/Library/PrivateFrameworks/MotionSensorLogging.framework/MotionSensorLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x266194` | `0x266e84` | **`+0xcf0`** |
| `__TEXT.__cstring` | `0x1273a` | `0x127b9` | **`+0x7f`** |
| `__AUTH_CONST.__const` | `0xb370` | `0xb3c0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x486` | `0x450` | **`-0x36`** |
| `__TEXT.__unwind_info` | `0x6860` | `0x6880` | **`+0x20`** |
| `__TEXT.__const` | `0x490a` | `0x491a` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3c98` | `0x3c94` | **`-0x4`** |

### Other Changes

```diff

-3164.0.0.0.0
+3169.4.0.0.0

-  Functions: 10456
-  Symbols:   11892
-  CStrings:  3843
+  Functions: 10474
+  Symbols:   11913
+  CStrings:  3849
Symbols:
+ __ZN5CMMsl17CompanionAltitude8readFromERN2PB6ReaderE
+ __ZN5CMMsl17CompanionAltitudeC1EOS0_
+ __ZN5CMMsl17CompanionAltitudeC1ERKS0_
+ __ZN5CMMsl17CompanionAltitudeC1Ev
+ __ZN5CMMsl17CompanionAltitudeC2EOS0_
+ __ZN5CMMsl17CompanionAltitudeC2ERKS0_
+ __ZN5CMMsl17CompanionAltitudeC2Ev
+ __ZN5CMMsl17CompanionAltitudeD0Ev
+ __ZN5CMMsl17CompanionAltitudeD1Ev
+ __ZN5CMMsl17CompanionAltitudeD2Ev
+ __ZN5CMMsl17CompanionAltitudeaSEOS0_
+ __ZN5CMMsl17CompanionAltitudeaSERKS0_
+ __ZN5CMMsl4Item21makeCompanionAltitudeEv
+ __ZN5CMMsl4swapERNS_17CompanionAltitudeES1_
+ __ZNK5CMMsl17CompanionAltitude10formatTextERN2PB13TextFormatterEPKc
+ __ZNK5CMMsl17CompanionAltitude10hash_valueEv
+ __ZNK5CMMsl17CompanionAltitude7writeToERN2PB6WriterE
+ __ZNK5CMMsl17CompanionAltitudeeqERKS0_
+ __ZTIN5CMMsl17CompanionAltitudeE
+ __ZTSN5CMMsl17CompanionAltitudeE
+ __ZTVN5CMMsl17CompanionAltitudeE
CStrings:
+ "altitudeInMeters"
+ "companionAltitude"
+ "l2NormGMMError"
+ "magneticInclinationError"
+ "magneticMagnitudeError"
+ "progress"
+ "uncertaintyInMeters"
- "MSLWriter - pruning rotated session file: %{private}s"
```
