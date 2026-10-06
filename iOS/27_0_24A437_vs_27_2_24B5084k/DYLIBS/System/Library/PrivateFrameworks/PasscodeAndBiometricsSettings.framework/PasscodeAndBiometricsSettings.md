## PasscodeAndBiometricsSettings

> `/System/Library/PrivateFrameworks/PasscodeAndBiometricsSettings.framework/PasscodeAndBiometricsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bd70` | `0x3c29c` | **`+0x52c`** |
| `__AUTH.__objc_data` | `0x508` | `0x5b8` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x5165` | `0x50f5` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x2ea0` | `0x2f00` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x2128` | `0x2188` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1050` | `0x1000` | **`-0x50`** |
| `__TEXT.__const` | `0xc34` | `0xc74` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2144` | `0x2184` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xaa0` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x3b4` | `0x3e0` | **`+0x2c`** |
| `__AUTH.__data` | `0xe8` | `0x110` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xa88` | `0xa68` | **`-0x20`** |
| `__DATA.__data` | `0x674` | `0x694` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x8c4` | `0x8a4` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x6b0` | `0x6c8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3698` | `0x36a8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x264` | `0x274` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x718` | `0x720` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e40` | `0x1e48` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1098` | `0x10a0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x40` | `0x44` | **`+0x4`** |
| `__DATA.__common` | `—` | `0x1` | **`+0x1`** |

### Other Changes

```diff

-35.3.0.0.0
+40.0.0.0.0

-  Functions: 1320
-  Symbols:   1838
-  CStrings:  885
+  Functions: 1324
+  Symbols:   1851
+  CStrings:  884
Symbols:
+ -[PABSTouchIDPasscodeController restingUnlock:]
+ -[PABSTouchIDPasscodeController setRestingUnlock:specifier:]
+ -[PABSTouchIDPasscodeController shouldShowRestingUnlock]
+ GCC_except_table104
+ GCC_except_table39
+ GCC_except_table43
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table67
+ GCC_except_table74
+ GCC_except_table84
+ _CFPreferencesCopyAppValue
+ _MobileGestalt_get_appleInternalInstallCapability
+ _OBJC_CLASS_$__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ _OBJC_METACLASS_$__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ __AXSHomeButtonRestingUnlock
+ __AXSHomeButtonSetRestingUnlock
+ __CLASS_METHODS__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ __CLASS_PROPERTIES__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ __DATA__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ __INSTANCE_METHODS__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ __METACLASS_DATA__TtC29PasscodeAndBiometricsSettings17PABSDebugSettings
+ _swift_arrayInitWithCopy
+ _symbolic SaySSG
+ _symbolic _____ 29PasscodeAndBiometricsSettings09PABSDebugD0C
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
- -[PABSBiometricController updateWithReplacedUUIDs:]
- -[PABSFingerprintController replaceFingerprint:]
- -[PABSTouchIDPasscodeController updateWithReplacedUUIDs:]
- GCC_except_table105
- GCC_except_table49
- GCC_except_table59
- GCC_except_table65
- GCC_except_table73
- _OBJC_CLASS_$_CIDVUIBiometricReplacementFlowManager
- ___48-[PABSFingerprintController replaceFingerprint:]_block_invoke
- ___48-[PABSFingerprintController replaceFingerprint:]_block_invoke_2
- ___block_descriptor_48_e8_32s40w_e29_v24?0"NSArray"8"NSError"16lw40l8s32l8
- ___block_descriptor_48_e8_32s40w_e32_v16?0"UINavigationController"8lw40l8s32l8
CStrings:
+ "%@: Set: %@"
+ "Debug Settings: Forcing biometric type [%{public}s]"
+ "Debug Settings: Unrecognized %{public}s value [%{public}s]. Expected one of: %{public}s"
+ "DeviceMesaType"
+ "ForceBiometricType"
+ "RESTING_UNLOCK"
+ "RESTING_UNLOCK_GROUP"
+ "RESTING_UNLOCK_TEXT"
- "Did not show biometric replacement UI"
- "Error replacing biometric identity: %@"
- "Has shown biometric replacement UI in modal sheet"
- "Proceed replacing biobinding identity"
- "REPLACE_FINGERPRINT"
- "Replaced biometric identity with new UUIDs: %@, current identity binding status: %d"
- "Showing biometric replacement UI"
- "v16@?0@\"UINavigationController\"8"
- "v24@?0@\"NSArray\"8@\"NSError\"16"
```
