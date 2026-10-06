## BluetoothSettings

> `/System/Library/PreferenceBundles/BluetoothSettings.bundle/BluetoothSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22e38` | `0x23f28` | **`+0x10f0`** |
| `__AUTH_CONST.__objc_const` | `0x2670` | `0x2280` | **`-0x3f0`** |
| `__TEXT.__objc_methlist` | `0x196c` | `0x17e4` | **`-0x188`** |
| `__TEXT.__swift5_typeref` | `0x1e8` | `0x34a` | **`+0x162`** |
| `__TEXT.__const` | `0x4c8` | `0x598` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1728` | `0x1698` | **`-0x90`** |
| `__DATA.__bss` | `0x150` | `0x1d0` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x6e0` | `0x738` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x2d0` | `0x328` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x608` | `0x660` | **`+0x58`** |
| `__DATA.__data` | `0x550` | `0x500` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x118` | `0x15c` | **`+0x44`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x50` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x84` | `0xac` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x760` | `0x788` | **`+0x28`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x41` | `0x57` | **`+0x16`** |
| `__TEXT.__cstring` | `0x1a91` | `0x1a81` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x20` | `0x10` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x10` | `0x14` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-2700.16.0.0.0
+2700.17.0.0.0

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 600
-  Symbols:   1172
-  CStrings:  512
+  Functions: 622
+  Symbols:   1180
+  CStrings:  511
Symbols:
+ _OBJC_CLASS_$_HPSConnectedHeadphoneInfo
+ _OBJC_CLASS_$_HPSConnectedHeadphonesController
+ ___swift_memcpy32_8
+ _associated conformance 17BluetoothSettings26HeadphoneDeviceWrapperViewV7SwiftUI0F0AA4BodyAdEP_AdE
+ _get_witness_table 8Settings05TupleA17ExperienceContentVyAA0acD0PAAE02onaC7OpenURL7performQrAA0acF9URLActionV6ResultVAI5InputVYacn_tFQOyAA0A4PaneVy7SwiftUI4ViewPAAE07bridgedA33FeatureDescriptionNavigationTitleyQrAP4TextVFQOy19PreferencesExtended0v10ControllerO0V_Qo_G_Qo__AOyAP012_ConditionalD0Vy09BluetoothA0022HeadphoneDeviceWrapperO0VArPE010navigationT0yQrqd__SyRd__lFQOyAX_SSQo_GSgGQPGAaDHPyHC
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE15navigationTitleyQrqd__SyRd__lFQOy19PreferencesExtended0f10ControllerC0V_SSQo_HO
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_storeEnumTagMultiPayload
+ _symbolic $s7SwiftUI4ViewP
+ _symbolic SS
+ _symbolic _____ 17BluetoothSettings26HeadphoneDeviceWrapperViewV
+ _symbolic _____y_____G 7SwiftUI14ObservedObjectV 16HeadphoneManager0E6DeviceC
+ _symbolic _____y______SSQo_ 7SwiftUI4ViewPAAE15navigationTitleyQrqd__SyRd__lFQO 19PreferencesExtended0f10ControllerC0V
+ _symbolic _____y__________y______SSQo_G 7SwiftUI19_ConditionalContentV 17BluetoothSettings26HeadphoneDeviceWrapperViewV AA0J0PAAE15navigationTitleyQrqd__SyRd__lFQO 19PreferencesExtended0m10ControllerJ0V
+ _symbolic _____y__________y______SSQo_GSg 7SwiftUI19_ConditionalContentV 17BluetoothSettings26HeadphoneDeviceWrapperViewV AA0J0PAAE15navigationTitleyQrqd__SyRd__lFQO 19PreferencesExtended0m10ControllerJ0V
+ _symbolic _____y__________y______SSQo__G 7SwiftUI19_ConditionalContentV7StorageO 17BluetoothSettings26HeadphoneDeviceWrapperViewV AA0K0PAAE15navigationTitleyQrqd__SyRd__lFQO 19PreferencesExtended0n10ControllerK0V
+ _symbolic _____y_____y__________y______SSQo_GSgG 8Settings0A4PaneV 7SwiftUI19_ConditionalContentV 09BluetoothA026HeadphoneDeviceWrapperViewV AD0K0PADE15navigationTitleyQrqd__SyRd__lFQO 19PreferencesExtended0n10ControllerK0V
+ _symbolic _____y_____y_____y______Qo_G_Qo__AAy_____y__________yAB_SSQo_GSgGt 8Settings0A17ExperienceContentPAAE02onaB7OpenURL7performQrAA0abE9URLActionV6ResultVAG5InputVYacn_tFQO AA0A4PaneV 7SwiftUI4ViewPAAE07bridgedA33FeatureDescriptionNavigationTitleyQrAN4TextVFQO 19PreferencesExtended0u10ControllerN0V AN012_ConditionalC0V 09BluetoothA0022HeadphoneDeviceWrapperN0V ApNE010navigationS0yQrqd__SyRd__lFQO
+ _symbolic _____y_____y_____y_____y______Qo_G_Qo__ABy_____y__________yAC_SSQo_GSgGQPG 8Settings05TupleA17ExperienceContentV AA0acD0PAAE02onaC7OpenURL7performQrAA0acF9URLActionV6ResultVAI5InputVYacn_tFQO AA0A4PaneV 7SwiftUI4ViewPAAE07bridgedA33FeatureDescriptionNavigationTitleyQrAP4TextVFQO 19PreferencesExtended0v10ControllerO0V AP012_ConditionalD0V 09BluetoothA0022HeadphoneDeviceWrapperO0V ArPE010navigationT0yQrqd__SyRd__lFQO
+ _type_layout_string 17BluetoothSettings26HeadphoneDeviceWrapperViewV
- __OBJC_$_PROTOCOL_CLASS_METHODS_OPT_PSController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PSController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_PSController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_PSStateRestoration
- __OBJC_$_PROTOCOL_METHOD_TYPES_PSController
- __OBJC_$_PROTOCOL_METHOD_TYPES_PSStateRestoration
- __OBJC_$_PROTOCOL_REFS_PSController
- __OBJC_$_PROTOCOL_REFS_PSStateRestoration
- __OBJC_LABEL_PROTOCOL_$_PSController
- __OBJC_LABEL_PROTOCOL_$_PSStateRestoration
- __OBJC_PROTOCOL_$_PSController
- __OBJC_PROTOCOL_$_PSStateRestoration
- _get_witness_table qd__8Settings0A17ExperienceContentHD2_AaBPAAE02onaB7OpenURL7performQrAA0abE9URLActionV6ResultVAG5InputVYacn_tFQOyAA0A4PaneVy7SwiftUI4ViewPAAE07bridgedA33FeatureDescriptionNavigationTitleyQrAN4TextVFQOy19PreferencesExtended0u10ControllerN0V_Qo_G_Qo_HO
- _swift_dynamicCastMetatype
- _swift_dynamicCastObjCClass
- _swift_dynamicCastTypeToObjCProtocolConditional
CStrings:
- "BTSDevicesController"
```
