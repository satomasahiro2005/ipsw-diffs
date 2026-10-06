## DeviceIdentity

> `/System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c524` | `0x1d9c8` | **`+0x14a4`** |
| `__TEXT.__cstring` | `0x3f78` | `0x429d` | **`+0x325`** |
| `__AUTH_CONST.__cfstring` | `0x4580` | `0x4860` | **`+0x2e0`** |
| `__DATA_CONST.__got` | `0x0` | `0x248` | **`+0x248`** |
| `__TEXT.__gcc_except_tab` | `0x950` | `0xaa0` | **`+0x150`** |
| `__DATA_CONST.__const` | `0x3c48` | `0x3ca0` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x438` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x488` | `0x4a0` | **`+0x18`** |
| `__AUTH.__data` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a0` | `0x6b0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x10` | `0x20` | **`+0x10`** |

### Other Changes

```diff

-1144.0.0.0.0
+1145.0.1.0.0

-  Functions: 272
-  Symbols:   970
-  CStrings:  662
+  Functions: 288
+  Symbols:   998
+  CStrings:  696
Symbols:
+ GCC_except_table12
+ GCC_except_table19
+ GCC_except_table7
+ GCC_except_table9
+ _DeviceIdentityCreateClientCertificateRequestWithBody
+ _DeviceIdentityRequestRKPropertiesCreateData
+ ___assert_rtn
+ ___destructor_8_s0_s8_s16_s24
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208_s216_s224_s232_s240_s248_s256_s264_s272
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
+ _objc_retain_x24
+ _objc_retain_x25
+ _udid_from_chipid_and_ecid
+ _udid_from_rkproperties_data
- GCC_except_table11
- GCC_except_table18
CStrings:
+ "%08X-%016llX"
+ "Could not convert data to dictionary."
+ "DeviceLocalPolicyCertificate"
+ "Failed to create RKProperties data."
+ "Failed to create certificate request."
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
- "iOS Device Activator (MobileActivation-1144)"
```
