## Matter

> `/System/Library/Frameworks/Matter.framework/Matter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7fa4ac` | `0x80e9c8` | **`+0x1451c`** |
| `__TEXT.__gcc_except_tab` | `0xb95c8` | `0xbb6d4` | **`+0x210c`** |
| `__AUTH_CONST.__objc_const` | `0x6e110` | `0x6f880` | **`+0x1770`** |
| `__TEXT.__objc_methlist` | `0x587bc` | `0x59994` | **`+0x11d8`** |
| `__TEXT.__cstring` | `0x2e645` | `0x2ec96` | **`+0x651`** |
| `__AUTH.__objc_data` | `0x1c660` | `0x1cc00` | **`+0x5a0`** |
| `__TEXT.__unwind_info` | `0x4e4d8` | `0x4e9f8` | **`+0x520`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b3f0` | `0x1b7d0` | **`+0x3e0`** |
| `__AUTH_CONST.__cfstring` | `0x16c60` | `0x16fa0` | **`+0x340`** |
| `__AUTH_CONST.__objc_intobj` | `0x6690` | `0x67c8` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x1afa8` | `0x1b0de` | **`+0x136`** |
| `__DATA.__objc_ivar` | `0x3b54` | `0x3c48` | **`+0xf4`** |
| `__DATA_CONST.__objc_classlist` | `0x2d70` | `0x2e00` | **`+0x90`** |
| `__DATA_CONST.__objc_superrefs` | `0x1fd8` | `0x2038` | **`+0x60`** |
| `__DATA_DIRTY.__common` | `0x708` | `0x6b0` | **`-0x58`** |
| `__DATA_CONST.__got` | `0x2148` | `0x2188` | **`+0x40`** |
| `__TEXT.__const` | `0x63149` | `0x63179` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1c410` | `0x1c3e8` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x128a8` | `0x128c8` | **`+0x20`** |
| `__DATA.__bss` | `0x8f58` | `0x8f68` | **`+0x10`** |

### Other Changes

```diff

-311.0.0.0.0
+315.0.0.0.0

-  Functions: 50925
-  Symbols:   3264
-  CStrings:  8719
+  Functions: 50883
+  Symbols:   3292
+  CStrings:  8749
Symbols:
+ _OBJC_CLASS_$_MTRBaseClusterDynamicLighting
+ _OBJC_CLASS_$_MTRBaseClusterElectricalDistribution
+ _OBJC_CLASS_$_MTRBaseClusterElectricalProtectionAlarm
+ _OBJC_CLASS_$_MTRBaseClusterSmokeConcentrationMeasurement
+ _OBJC_CLASS_$_MTRClusterDynamicLighting
+ _OBJC_CLASS_$_MTRClusterElectricalDistribution
+ _OBJC_CLASS_$_MTRClusterElectricalProtectionAlarm
+ _OBJC_CLASS_$_MTRClusterSmokeConcentrationMeasurement
+ _OBJC_CLASS_$_MTRDynamicLightingClusterEffectColorStruct
+ _OBJC_CLASS_$_MTRDynamicLightingClusterEffectStruct
+ _OBJC_CLASS_$_MTRDynamicLightingClusterStartEffectParams
+ _OBJC_CLASS_$_MTRDynamicLightingClusterStopEffectParams
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterArcFaultRatingsStruct
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterModifyEnabledAlarmsParams
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterNotifyEvent
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterOverLoadRatingsStruct
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterOverVoltageRatingsStruct
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterResidualCurrentFaultRatingsStruct
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterShortCircuitRatingsStruct
+ _OBJC_CLASS_$_MTRElectricalProtectionAlarmClusterSurgeProtectionRatingsStruct
+ _OBJC_METACLASS_$_MTRBaseClusterDynamicLighting
+ _OBJC_METACLASS_$_MTRBaseClusterElectricalDistribution
+ _OBJC_METACLASS_$_MTRBaseClusterElectricalProtectionAlarm
+ _OBJC_METACLASS_$_MTRBaseClusterSmokeConcentrationMeasurement
+ _OBJC_METACLASS_$_MTRClusterDynamicLighting
+ _OBJC_METACLASS_$_MTRClusterElectricalDistribution
+ _OBJC_METACLASS_$_MTRClusterElectricalProtectionAlarm
+ _OBJC_METACLASS_$_MTRClusterSmokeConcentrationMeasurement
+ _OBJC_METACLASS_$_MTRDynamicLightingClusterEffectColorStruct
+ _OBJC_METACLASS_$_MTRDynamicLightingClusterEffectStruct
+ _OBJC_METACLASS_$_MTRDynamicLightingClusterStartEffectParams
+ _OBJC_METACLASS_$_MTRDynamicLightingClusterStopEffectParams
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterArcFaultRatingsStruct
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterModifyEnabledAlarmsParams
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterNotifyEvent
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterOverLoadRatingsStruct
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterOverVoltageRatingsStruct
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterResidualCurrentFaultRatingsStruct
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterShortCircuitRatingsStruct
+ _OBJC_METACLASS_$_MTRElectricalProtectionAlarmClusterSurgeProtectionRatingsStruct
- _OBJC_CLASS_$_MTRBaseClusterTimer
- _OBJC_CLASS_$_MTRClusterTimer
- _OBJC_CLASS_$_MTRTimerClusterAddTimeParams
- _OBJC_CLASS_$_MTRTimerClusterReduceTimeParams
- _OBJC_CLASS_$_MTRTimerClusterResetTimerParams
- _OBJC_CLASS_$_MTRTimerClusterSetTimerParams
- _OBJC_METACLASS_$_MTRBaseClusterTimer
- _OBJC_METACLASS_$_MTRClusterTimer
- _OBJC_METACLASS_$_MTRTimerClusterAddTimeParams
- _OBJC_METACLASS_$_MTRTimerClusterReduceTimeParams
- _OBJC_METACLASS_$_MTRTimerClusterResetTimerParams
- _OBJC_METACLASS_$_MTRTimerClusterSetTimerParams
CStrings:
+ "<%@: currentSensitivity:%@; tripMechanism:%@; voltageDependent:%@; groundFaultClass:%@; waveform:%@; trippingCharacteristic:%@; ultimateMaxCurrent:%@; serviceMaxCurrent:%@; >"
+ "<%@: effectID:%@; source:%@; label:%@; maxSpeed:%@; defaultSpeed:%@; supportsColorPalette:%@; >"
+ "<%@: effectID:%@; speed:%@; colorMode:%@; colorPalette:%@; >"
+ "<%@: groupKeySetID:%@; groupKeySecurityPolicy:%@; epochKey0:%@; epochStartTime0:%@; epochKey1:%@; epochStartTime1:%@; epochKey2:%@; epochStartTime2:%@; >"
+ "<%@: level:%@; x:%@; y:%@; hue:%@; enhancedHue:%@; saturation:%@; >"
+ "<%@: seriesArcCurrentSensitivity:%@; parallelArcCurrentSensitivity:%@; supportedArcCauses:%@; >"
+ "<%@: tripCurrent:%@; tripCurve:%@; tripMechanism:%@; ultimateMaxCurrent:%@; serviceMaxCurrent:%@; >"
+ "<%@: tripCurrent:%@; tripMechanism:%@; tripCurve:%@; ultimateMaxCurrent:%@; serviceMaxCurrent:%@; maxCurrent:%@; >"
+ "<%@: tripMechanism:%@; protectionClass:%@; protectionType:%@; maxContinuousOperatingVoltage:%@; maxVoltageProtection:%@; maxTemporaryVoltage:%@; nominalDischargeCurrent:%@; maximumDishargeCurrent:%@; ratedShortCircuitCurrent:%@; ratedShortTimeWithstandCurrent:%@; energyAbsorptionCapability:%@; responseTime:%@; >"
+ "<%@: tripMechanism:%@; tripVoltage:%@; maxContinuousOperatingVoltage:%@; responseTime:%@; >"
+ "AppleResetAll"
+ "AppleStabilityResetCountBootRelativeTime"
+ "ArcCause"
+ "ArcFaultRating"
+ "AvailableEffects"
+ "CodegenDataModelProvider::Shutdown() complete"
+ "CurrentEffectID"
+ "CurrentSpeed"
+ "Destroy() called on already-destroyed cluster — this should not happen"
+ "DynamicLighting"
+ "Electrical Distribution Enclosure"
+ "ElectricalDistribution"
+ "ElectricalProtectionAlarm"
+ "EndOfLife"
+ "Humidifier/Dehumidifier"
+ "ImageRotationDiscreteAngles"
+ "MaxContinuousCurrent"
+ "MaxVoltage"
+ "NumberOfPoles"
+ "OverLoadRating"
+ "OverVoltageRating"
+ "Re-mapping security policy from CacheAndSync to TrustFirst for keyset %u (fabric index %u)"
+ "Re-starting data model provider %p (server restart cycle)"
+ "Received zero-length TCP message, closing connection."
+ "ResetAll"
+ "ResidualCurrentRating"
+ "ServiceEntranceRated"
+ "ShortCircuitRating"
+ "Shutting down data model provider %p"
+ "SmokeConcentrationMeasurement"
+ "StartEffect"
+ "StopEffect"
+ "SurgeProtectionRating"
+ "Unsupported group key security policy: %d"
+ "device-name"
- "<%@: additionalTime:%@; >"
- "<%@: newTime:%@; >"
- "<%@: timeReduction:%@; >"
- "AddTime"
- "Event encode failure: no fabric index for fabric scoped event"
- "Failed to generate event: %s"
- "IsConstructed()"
- "ReduceTime"
- "ResetTimer"
- "SetTime"
- "SetTimer"
- "Test Kitchen"
- "TimeRemaining"
- "Timer"
- "TimerState"
```
