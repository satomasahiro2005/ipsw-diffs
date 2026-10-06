## CoreNavigation

> `/System/Library/PrivateFrameworks/CoreNavigation.framework/CoreNavigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x361e5c` | `0x361b44` | **`-0x318`** |
| `__TEXT.__gcc_except_tab` | `0x16990` | `0x1676c` | **`-0x224`** |
| `__TEXT.__eh_frame` | `0x48` | `—` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xec48` | `0xec70` | **`+0x28`** |
| `__TEXT.__const` | `0x51f91` | `0x51fa1` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3833c` | `0x3834c` | **`+0x10`** |

### Other Changes

```diff

-417.0.0.0.0
+421.0.0.0.0

-  Functions: 15513
-  Symbols:   13497
-  CStrings:  3913
+  Functions: 15512
+  Symbols:   13504
+  CStrings:  3914
Symbols:
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData18WirelessClientInfo25kCourseDegreesFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData18WirelessClientInfo32kSpeedMetersPerSecondFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData18WirelessClientInfo33kCourseAccuracyDegreesFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData18WirelessClientInfo40kSpeedAccuracyMetersPerSecondFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry5Raven20MeasurementTypeCount19MT_GnssPhaseDopplerE
+ __ZN5raven14RavenEstimator26UpdateMeasurementTypeCountERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERKNS1_6vectorINS1_4pairIjS7_EENS5_ISC_EEEERNS1_5arrayIjLm35EEESJ_
+ __ZN5raven24RavenIonosphereEstimator26UpdateMeasurementTypeCountERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERKNS1_6vectorINS1_4pairIjS7_EENS5_ISC_EEEERNS1_5arrayIjLm35EEESJ_
+ __ZNK5raven17RavenPlatformInfo26IsRavenSupportedFire9PhoneEv
+ __ZNK5raven17RavenPlatformInfo39IsRavenSupportedIndusFall26orLaterPhoneEv
- __ZN5raven14RavenEstimator26UpdateMeasurementTypeCountERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERKNS1_6vectorINS1_4pairIjS7_EENS5_ISC_EEEERNS1_5arrayIjLm34EEESJ_
- __ZN5raven24RavenIonosphereEstimator26UpdateMeasurementTypeCountERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERKNS1_6vectorINS1_4pairIjS7_EENS5_ISC_EEEERNS1_5arrayIjLm34EEESJ_
CStrings:
+ "GnssPhaseDoppler"
```
