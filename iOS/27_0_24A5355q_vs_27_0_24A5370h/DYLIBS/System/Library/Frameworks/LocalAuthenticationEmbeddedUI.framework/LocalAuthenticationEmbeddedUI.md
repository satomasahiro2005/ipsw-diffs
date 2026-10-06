## LocalAuthenticationEmbeddedUI

> `/System/Library/Frameworks/LocalAuthenticationEmbeddedUI.framework/LocalAuthenticationEmbeddedUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x212a8` | `0x21b88` | **`+0x8e0`** |
| `__AUTH_CONST.__objc_const` | `0xa2d0` | `0xa510` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0x3788` | `0x3938` | **`+0x1b0`** |
| `__AUTH_CONST.__cfstring` | `0x1060` | `0x1180` | **`+0x120`** |
| `__TEXT.__cstring` | `0x234f` | `0x244f` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c48` | `0x1ca0` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x1648` | `0x1698` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xed8` | `0xf28` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xbd8` | `0xc00` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x378` | `0x398` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x670` | `0x678` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x230` | `0x238` | **`+0x8`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 1194
-  Symbols:   2351
-  CStrings:  303
+  Functions: 1228
+  Symbols:   2402
+  CStrings:  313
Symbols:
+ +[LAPSPasscodeChangeSystemBuilder passcodeVerificationSystemWithOptions:]
+ -[LAPSCurrentPasscodeServiceOptions .cxx_destruct]
+ -[LAPSCurrentPasscodeServiceOptions setUserId:]
+ -[LAPSCurrentPasscodeServiceOptions userId]
+ -[LAPSPasscodeChangeControllerProviderOptions passcodeTypeOverride]
+ -[LAPSPasscodeChangeControllerProviderOptions setPasscodeTypeOverride:]
+ -[LAPSPasscodeChangeControllerProviderOptions setUserId:]
+ -[LAPSPasscodeChangeControllerProviderOptions userId]
+ -[LAPSPasscodeChangeSystemVerificationAdapter initWithPersistence:options:]
+ -[LAPSPasscodePersistenceAdapter backoffTimeoutForUserId:]
+ -[LAPSPasscodePersistenceAdapter failedPasscodeAttemptsForUserId:]
+ -[LAPSPasscodePersistenceAdapter failedPasscodeRecoveryAttemptsForUserId:]
+ -[LAPSPasscodePersistenceAdapter isPasscodeLockedOutForUserId:]
+ -[LAPSPasscodePersistenceAdapter maxPasscodeRecoveryAttemptsForUserId:]
+ -[LAPSPasscodePersistenceAdapter verifyPasscode:userId:contextRef:]
+ -[LAPSPasscodePersistenceMKBAdapter _deviceLockStateValueForKey:userId:]
+ -[LAPSPasscodePersistenceMKBAdapter _mementoStateValueForKey:userId:]
+ -[LAPSPasscodePersistenceMKBAdapter backoffTimeoutForUserId:]
+ -[LAPSPasscodePersistenceMKBAdapter failedPasscodeAttemptsForUserId:]
+ -[LAPSPasscodePersistenceMKBAdapter failedPasscodeRecoveryAttemptsForUserId:]
+ -[LAPSPasscodePersistenceMKBAdapter isPasscodeLockedOutForUserId:]
+ -[LAPSPasscodePersistenceMKBAdapter maxPasscodeRecoveryAttemptsForUserId:]
+ -[LAPSPasscodePersistenceMKBAdapter verifyPasscode:userId:contextRef:]
+ -[LAPSPasscodeVerificationSystemOptions .cxx_destruct]
+ -[LAPSPasscodeVerificationSystemOptions passcodeTypeOverride]
+ -[LAPSPasscodeVerificationSystemOptions setPasscodeTypeOverride:]
+ -[LAPSPasscodeVerificationSystemOptions setUserId:]
+ -[LAPSPasscodeVerificationSystemOptions userId]
+ -[LAPasscodeVerificationServiceOptions passcodeType]
+ -[LAPasscodeVerificationServiceOptions setPasscodeType:]
+ -[LAPasscodeVerificationServiceOptions setUserId:]
+ -[LAPasscodeVerificationServiceOptions userId]
+ _LACPasscodeFromLAPasscodeType
+ _NSStringFromLAPasscodeType
+ _OBJC_CLASS_$_LAPSPasscodeVerificationSystemOptions
+ _OBJC_IVAR_$_LAPSCurrentPasscodeServiceOptions._userId
+ _OBJC_IVAR_$_LAPSPasscodeChangeControllerProviderOptions._passcodeTypeOverride
+ _OBJC_IVAR_$_LAPSPasscodeChangeControllerProviderOptions._userId
+ _OBJC_IVAR_$_LAPSPasscodeChangeSystemVerificationAdapter._options
+ _OBJC_IVAR_$_LAPSPasscodeVerificationSystemOptions._passcodeTypeOverride
+ _OBJC_IVAR_$_LAPSPasscodeVerificationSystemOptions._userId
+ _OBJC_IVAR_$_LAPasscodeVerificationServiceOptions._passcodeType
+ _OBJC_IVAR_$_LAPasscodeVerificationServiceOptions._userId
+ _OBJC_METACLASS_$_LAPSPasscodeVerificationSystemOptions
+ __OBJC_$_INSTANCE_METHODS_LAPSPasscodeVerificationSystemOptions
+ __OBJC_$_INSTANCE_VARIABLES_LAPSPasscodeVerificationSystemOptions
+ __OBJC_$_PROP_LIST_LAPSPasscodeVerificationSystemOptions
+ __OBJC_CLASS_RO_$_LAPSPasscodeVerificationSystemOptions
+ __OBJC_METACLASS_RO_$_LAPSPasscodeVerificationSystemOptions
+ ___75-[LAPSPasscodeChangeSystemVerificationAdapter initWithPersistence:options:]_block_invoke
+ ___82-[LAPSPasscodeChangeControllerProvider passcodeVerificationControllerWithOptions:]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e44_"LAPSPasscodeVerificationSystemOptions"8?0ls32l8
+ _objc_setProperty_nonatomic_copy
- -[LAPSPasscodePersistenceMKBAdapter _deviceLockStateValueForKey:]
- -[LAPSPasscodePersistenceMKBAdapter _mementoStateValueForKey:]
CStrings:
+ "@\"LAPSPasscodeVerificationSystemOptions\"8@?0"
+ "DeviceHandle"
+ "LAPasscodeType(%ld)"
+ "LAPasscodeTypeAlphanumeric"
+ "LAPasscodeTypeNumericCustomDigits"
+ "LAPasscodeTypeNumericFourDigits"
+ "LAPasscodeTypeNumericSixDigits"
+ "LAPasscodeTypeUnspecified"
+ "passcodeType"
+ "userId"
```
