## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a01c` | `0x34b994` | **`+0x1978`** |
| `__TEXT.__cstring` | `0xeb94` | `0xeea5` | **`+0x311`** |
| `__DATA_CONST.__cfstring` | `0xd200` | `0xd4e0` | **`+0x2e0`** |
| `__TEXT.__gcc_except_tab` | `0x1a94` | `0x1b88` | **`+0xf4`** |
| `__DATA_CONST.__const` | `0x1c008` | `0x1c088` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x11f8` | `0x1238` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x498` | `0x4b0` | **`+0x18`** |
| `__DATA.__bss` | `0x558` | `0x568` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1230` | `0x1240` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x928` | `0x930` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1144.0.0.0.0
+1145.0.1.0.0

-  Functions: 1643
-  Symbols:   4001
-  CStrings:  3033
+  Functions: 1658
+  Symbols:   4027
+  CStrings:  3067
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileActivation/install/TempContent/Objects/MobileActivation.build/mobileactivationd.build/Objects-normal/arm64e/baa_request.o
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/MobileActivation/install/TempContent/Objects/MobileActivation.build/mobileactivationd.build/Objects-normal/arm64e/baa_rkproperties.o
+ _OUTLINED_FUNCTION_40
+ _OUTLINED_FUNCTION_46
+ _OUTLINED_FUNCTION_48
+ ___assert_rtn
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208_s216_s224_s232_s240_s248_s256_s264_s272
+ ___redactOptionsForLogging_block_invoke
+ _baa_request_body_create_dictionary
+ _baa_request_body_has_required_fields
+ _baa_request_create_with_body
+ _baa_rkproperties_create_data
+ _baa_rkproperties_from_data
+ _baa_rkproperties_has_required_fields
+ _kMAOptionsBAABoardId
+ _kMAOptionsBAAChipID
+ _kMAOptionsBAADeviceLocalPolicyCertificate
+ _kMAOptionsBAARequestVersion
+ _kMAOptionsBAASCRT
+ _kMAOptionsBAASecurityDomain
+ _kMAOptionsBAASerialNumber
+ _kMAOptionsBAAUCRT
+ _kMAOptionsBAAUniqueChipID
+ _kMAOptionsBAAUseIM4C
+ _kMAOptionsBAAVMIdentityAttestation
+ _udid_from_chipid_and_ecid
+ _udid_from_rkproperties_data
+ baa_request.m
+ baa_request_body_create_dictionary
+ baa_rkproperties.m
+ redactOptionsForLogging.onceToken
+ redactOptionsForLogging.sensitiveKeys
- _OUTLINED_FUNCTION_21
- _OUTLINED_FUNCTION_28
- _OUTLINED_FUNCTION_41
- _OUTLINED_FUNCTION_44
- _OUTLINED_FUNCTION_57
- _OUTLINED_FUNCTION_58
CStrings:
+ "%08X-%016llX"
+ "1145.0.1"
+ "<private>"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.0.1 built on Jun 26 2026 at 22:45:04)"
+ "Could not convert data to dictionary."
+ "DeviceLocalPolicyCertificate"
+ "Failed to create RKProperties data."
+ "Input data incomplete."
+ "Missing RKCertification."
+ "Missing RKProperties."
+ "Missing RKPropertiesSignature."
+ "Missing boardID."
+ "Missing chipID."
+ "Missing ecid."
+ "Missing required input."
+ "Missing rkCertificationPub."
+ "Missing securityDomain."
+ "Missing sikPub."
+ "RKProperties is nil."
+ "Request body is nil."
+ "RequestVersion"
+ "UseIM4C"
+ "VMIdentityAttestation"
+ "baa_request.m"
+ "baa_request_body_create_dictionary"
+ "baa_request_body_has_required_fields"
+ "baa_request_create_with_body"
+ "baa_rkproperties_create_data"
+ "baa_rkproperties_from_data"
+ "baa_rkproperties_has_required_fields"
+ "iOS Device Activator (MobileActivation-1145.0.1)"
+ "requestBody"
+ "requestBody->rkCertification"
+ "requestBody->rkProperties"
+ "requestBody->rkPropertiesSignature"
+ "scrt"
+ "ucrt"
- "1144"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1144 built on Jun 15 2026 at 23:58:33)"
- "iOS Device Activator (MobileActivation-1144)"
```
