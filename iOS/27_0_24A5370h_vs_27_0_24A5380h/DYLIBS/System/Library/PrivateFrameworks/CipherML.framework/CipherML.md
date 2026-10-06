## CipherML

> `/System/Library/PrivateFrameworks/CipherML.framework/CipherML`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x205d7c` | `0x2076c8` | **`+0x194c`** |
| `__DATA.__bss` | `0x17af8` | `0x17178` | **`-0x980`** |
| `__DATA_DIRTY.__bss` | `0x6588` | `0x6f08` | **`+0x980`** |
| `__AUTH.__data` | `0x11f0` | `0x1408` | **`+0x218`** |
| `__DATA.__data` | `0x2b28` | `0x2958` | **`-0x1d0`** |
| `__TEXT.__eh_frame` | `0x14a54` | `0x14944` | **`-0x110`** |
| `__TEXT.__oslogstring` | `0x360b` | `0x368b` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x7440` | `0x73f0` | **`-0x50`** |
| `__DATA.__common` | `0x260` | `0x238` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x1e0` | `0x208` | **`+0x28`** |
| `__TEXT.__const` | `0x14940` | `0x14960` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8578` | `0x8558` | **`-0x20`** |
| `__AUTH.__objc_data` | `0x50` | `0x48` | **`-0x8`** |
| `__AUTH_CONST.__auth_got` | `0x19a0` | `0x19a8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x12d8` | `0x12e0` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0xbe0` | `0xbe8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xcec` | `0xce8` | **`-0x4`** |

### Other Changes

```diff

-383.0.7.0.0
+383.0.15.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 11139
-  Symbols:   23260
-  CStrings:  619
+  Functions: 11140
+  Symbols:   23261
+  CStrings:  621
Symbols:
+ _$s8CipherML13NetworkConfigV05fetchD8ViaProxySbvg
+ _$s8CipherML13NetworkConfigV05fetchD8ViaProxySbvpMV
+ _$s8CipherML18NetworkManagerTypeOMaTm
+ _$sSS3key_10Foundation4DateV5valuetWOhTm
+ _$ss10_NativeSetV11subtractingyAByxGqd__7ElementQyd__RszSTRd__lFSS_SaySSGTg5
+ _$ss10_NativeSetV11subtractingyAByxGqd__7ElementQyd__RszSTRd__lFSS_ShySSGTg5
+ _$ss10_NativeSetV19genericIntersectionyAByxGqd__7ElementQyd__RszSTRd__lFSS_SD4KeysVySS8CipherML7UseCaseO_GTg5
+ _$ss10_NativeSetV19genericIntersectionyAByxGqd__7ElementQyd__RszSTRd__lFSS_SaySSGTg5
+ _$ss17_NativeDictionaryV07extractB05using5countAByxq_Gs13_UnsafeBitsetV_SitFSS_8CipherML15AspireApiConfigVTg5Tm
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_CipherML
+ _swift_deallocBox
- _$s2os18OSLogInterpolationV06appendC0_7privacy10attributesys5Error_pSgyXA_AA0B7PrivacyVSStFfA1_
- _$s8CipherML11KeyRotationC3runyyYaKFTY6_
- _$s8CipherML11KeyRotationCACScAAAWL
- _$s8CipherML19NetworkManagerErrorOMaTm
- _$sSh11subtractingyShyxGABFSS_Tg5
- _$sSh11subtractingyShyxGqd__7ElementQyd__RszSTRd__lFSS_SaySSGTg5
- _$sSh12intersectionyShyxGqd__7ElementQyd__RszSTRd__lFSS_SD4KeysVySS8CipherML7UseCaseO_GTg5
- _$sSh12intersectionyShyxGqd__7ElementQyd__RszSTRd__lFSS_SaySSGTg5
- _$ss10_NativeSetV11subtractingyAByxGqd__7ElementQyd__RszSTRd__lFADs13_UnsafeBitsetVXEfU_SS_SaySSGTG5TA
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_AiBq_xRi_zRi0_zRi__Ri0__r0_lys5NeverOxIsgyrzr_xA2KRs_r0_lIetygrzo_Tpq5s10_NativeSetVySSG_Tg506$ss13_ab7V17withd32Copy2of4bodyxAB_xABq_YKXEtq_YKs5i9R_r0_lFZxr23_YKXEfU_A3Bq_xRi_zRi0_zz7__Ri0__u5_lys5k17OxIsgyrzr_xA2HRs_u20_lIetyygrzo_TPq5s10_lM9VySSG_TG5A2Bq_xRi_zRi0_zRi__Ri0__r0_lyAkNIsgyrzr_Tf1nc_n
- _$ss17_NativeDictionaryV6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5ErrorRd__lFSS_10Foundation4DateVs5NeverOTg5
CStrings:
+ "URL would fail sanitization in production, endpoint: %{public}s"
+ "URL would fail sanitization in production, issuer: %{public}s"
```
