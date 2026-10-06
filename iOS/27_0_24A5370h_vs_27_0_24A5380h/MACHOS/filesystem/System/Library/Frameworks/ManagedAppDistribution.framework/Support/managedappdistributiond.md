## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e041c` | `0x6df1ac` | **`-0x1270`** |
| `__TEXT.__eh_frame` | `0x3a628` | `0x39c20` | **`-0xa08`** |
| `__TEXT.__unwind_info` | `0x12ec0` | `0x128e0` | **`-0x5e0`** |
| `__TEXT.__const` | `0x400e0` | `0x3fc10` | **`-0x4d0`** |
| `__DATA.__bss` | `0x2ecd0` | `0x2ea50` | **`-0x280`** |
| `__DATA_CONST.__const` | `0x2f640` | `0x2f458` | **`-0x1e8`** |
| `__TEXT.__auth_stubs` | `0x7350` | `0x74e0` | **`+0x190`** |
| `__DATA_CONST.__auth_got` | `0x39b8` | `0x3a80` | **`+0xc8`** |
| `__DATA.__data` | `0x10cb8` | `0x10d48` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x16082` | `0x16002` | **`-0x80`** |
| `__TEXT.__cstring` | `0xf985` | `0xf915` | **`-0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x5f00` | `0x5eb0` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x1f88` | `0x1fb8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x85a5` | `0x8575` | **`-0x30`** |
| `__TEXT.__swift_as_ret` | `0x19e4` | `0x19b4` | **`-0x30`** |
| `__TEXT.__swift_as_entry` | `0xc4c` | `0xc20` | **`-0x2c`** |
| `__TEXT.__objc_stubs` | `0x5b00` | `0x5ae0` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x3544` | `0x3524` | **`-0x20`** |
| `__DATA.__common` | `0xed8` | `0xef0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x19dc` | `0x19c8` | **`-0x14`** |
| `__TEXT.__constg_swiftt` | `0x7478` | `0x7468` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1eb0` | `0x1ea8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x6524` | `0x652a` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0xa68` | `0xa64` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4.0.33.0.0
+4.0.37.0.0

-  - /System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities

+  - /System/Library/PrivateFrameworks/HTTPTypesInternal.framework/HTTPTypesInternal

-  Functions: 16930
-  Symbols:   3310
-  CStrings:  4581
+  Functions: 16856
+  Symbols:   3339
+  CStrings:  4572
Symbols:
+ _$s10Foundation15ContiguousBytesP04withC0yqd__qd__s7RawSpanVqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFTq
+ _$s17HTTPTypesInternal10HTTPFieldsV17dictionaryLiteralAcA9HTTPFieldV4NameV_SStd_tcfC
+ _$s17HTTPTypesInternal10HTTPFieldsVMa
+ _$s17HTTPTypesInternal10HTTPFieldsVMn
+ _$s17HTTPTypesInternal10HTTPFieldsVSTAAMc
+ _$s17HTTPTypesInternal10HTTPFieldsVSlAAMc
+ _$s17HTTPTypesInternal11HTTPRequestV6MethodV3getAEvgZ
+ _$s17HTTPTypesInternal11HTTPRequestV6MethodV4headAEvgZ
+ _$s17HTTPTypesInternal11HTTPRequestV6MethodV4postAEvgZ
+ _$s17HTTPTypesInternal11HTTPRequestV6MethodV8rawValueSSvg
+ _$s17HTTPTypesInternal11HTTPRequestV6MethodVMa
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV12unauthorizedAEvgZ
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV14partialContentAEvgZ
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV2eeoiySbAE_AEtFZ
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV2okAEvgZ
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV4code12reasonPhraseAESi_SStcfC
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV4codeSivg
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusV9forbiddenAEvgZ
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusVMa
+ _$s17HTTPTypesInternal12HTTPResponseV6StatusVSQAAMc
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV03rawD0SSvg
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV09canonicalD0SSvg
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV11contentTypeAEvgZ
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV13authorizationAEvgZ
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV5rangeAEvgZ
+ _$s17HTTPTypesInternal9HTTPFieldV4NameV9userAgentAEvgZ
+ _$s17HTTPTypesInternal9HTTPFieldV4NameVMa
+ _$s17HTTPTypesInternal9HTTPFieldV4NameVMn
+ _$s17HTTPTypesInternal9HTTPFieldV4NameVyAESgSScfC
+ _$s17HTTPTypesInternal9HTTPFieldV4nameAC4NameVvg
+ _$s17HTTPTypesInternal9HTTPFieldV5valueSSvg
+ _$s17HTTPTypesInternal9HTTPFieldVMa
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- _OBJC_CLASS_$_DMCCodeUtilities
CStrings:
+ "[%@] App Store is the only installed distributor, disabling the install confirmation sheet"
- "Authorization"
- "Content-Type"
- "ManagedAppDistributionDaemon/TaskLocalContext.swift"
- "Range"
- "User-Agent"
- "[%@] Expected composed identifier but none found"
- "[%@] Expected declaration status but none found for %{public}s"
- "[%@] Record not found for '%{public}s'"
- "[%@] Signature invalid for '%{public}s'"
- "verifySignatureForPath:composedIdentifier:"
```
