## TextInputCore

> `/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2221c8` | `0x2228b4` | **`+0x6ec`** |
| `__AUTH_CONST.__cfstring` | `0x13d60` | `0x13e80` | **`+0x120`** |
| `__TEXT.__cstring` | `0x1c939` | `0x1ca14` | **`+0xdb`** |
| `__TEXT.__oslogstring` | `0x43e8` | `0x4479` | **`+0x91`** |
| `__AUTH_CONST.__objc_const` | `0x1a610` | `0x1a6a0` | **`+0x90`** |
| `__DATA_CONST.__objc_arraydata` | `0x1050` | `0x10a0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1868` | `0x18b0` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x10aa0` | `0x10ae8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xa048` | `0xa078` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x8850` | `0x8870` | **`+0x20`** |
| `__TEXT.__const` | `0x2e60` | `0x2e40` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__DATA.__bss` | `0x1ed0` | `0x1ee0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x12c0` | `0x12cc` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1b00` | `0x1af8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x65f8` | `0x6600` | **`+0x8`** |

### Other Changes

```diff

-3559.100.0.0.0
+3562.0.0.0.0

-  Functions: 10533
-  Symbols:   17412
-  CStrings:  4076
+  Functions: 10540
+  Symbols:   17432
+  CStrings:  4086
Symbols:
+ -[CoreTelephonyMockObject cellularImei1]
+ -[CoreTelephonyMockObject cellularImei2]
+ -[CoreTelephonyMockObject cellularNal]
+ -[CoreTelephonyMockObject initWithCellularEid:cellularImei:cellularImei1:cellularImei2:cellularNal:]
+ -[CoreTelephonyMockObject setCellularImei1:]
+ -[CoreTelephonyMockObject setCellularImei2:]
+ -[CoreTelephonyMockObject setCellularNal:]
+ _OBJC_IVAR_$_CoreTelephonyMockObject._cellularImei1
+ _OBJC_IVAR_$_CoreTelephonyMockObject._cellularImei2
+ _OBJC_IVAR_$_CoreTelephonyMockObject._cellularNal
+ _TIKeyboardOutputInfoTypeCellularIMEI1Str
+ _TIKeyboardOutputInfoTypeCellularIMEI2Str
+ _TIKeyboardOutputInfoTypeCellularNALStr
+ _TIKeyboardSecureCandidateCellularIMEI1Str
+ _TIKeyboardSecureCandidateCellularIMEI2Str
+ _TIKeyboardSecureCandidateCellularNALStr
+ _TITextContentTypeCellularIMEI1
+ _TITextContentTypeCellularIMEI2
+ _TITextContentTypeCellularNAL
+ __ZZ61-[TIKeyboardInputManagerMecabra onScreenContextForCandidates]E25screenScrapingAllowedApps
+ __ZZ61-[TIKeyboardInputManagerMecabra onScreenContextForCandidates]E9onceToken
+ ___61-[TIKeyboardInputManagerMecabra onScreenContextForCandidates]_block_invoke
- -[CoreTelephonyMockObject initWithCellularEid:cellularImei:]
- __ZNSt3__19to_stringEd
CStrings:
+ "%s  most_probable_lexicon_for_context_and_stems returned lexicon %u that is not owned by any loaded model; skipping single-model prediction step"
+ "AUTOFILL_CELLULAR_IMEI1_TITLE"
+ "AUTOFILL_CELLULAR_IMEI2_TITLE"
+ "AUTOFILL_CELLULAR_NAL_TITLE"
+ "DELETE FROM shapes WHERE timestamp <= ?"
+ "SELECT COUNT(*) FROM shapes WHERE string_representation LIKE ?"
+ "com.alibaba.dingtalklit"
+ "com.sina.weibo"
+ "com.soulapp.cn"
+ "com.ss.iphone.ugc.Aweme"
+ "com.tencent.ww"
+ "com.xingin.discover"
+ "unified_predictions"
- "';"
- "DELETE From shapes WHERE timestamp <= "
- "SELECT COUNT(*) FROM shapes WHERE string_representation LIKE '"
```
