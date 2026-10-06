## jetpackassetd

> `/System/Library/PrivateFrameworks/JetCore.framework/Support/jetpackassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba58c` | `0xbc988` | **`+0x23fc`** |
| `__TEXT.__cstring` | `0x6314` | `0x6444` | **`+0x130`** |
| `__DATA.__bss` | `0x4280` | `0x4380` | **`+0x100`** |
| `__TEXT.__const` | `0x3ed8` | `0x3fb8` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x2ed0` | `0x2f80` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x3108` | `0x3198` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x1229` | `0x129f` | **`+0x76`** |
| `__DATA_CONST.__auth_got` | `0x1770` | `0x17c8` | **`+0x58`** |
| `__TEXT.__objc_methname` | `0xe7e` | `0xebe` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xae0` | `0xb20` | **`+0x40`** |
| `__DATA.__data` | `0x1cc8` | `0x1d00` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x1098` | `0x10c8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x133c` | `0x1364` | **`+0x28`** |
| `__DATA.__common` | `0x1a8` | `0x1c8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1104` | `0x1120` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2a18` | `0x2a30` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x8880` | `0x8890` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x178` | `0x17c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-10.1.9.0.0
+10.1.11.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 2208
-  Symbols:   1165
-  CStrings:  745
+  Functions: 2220
+  Symbols:   1177
+  CStrings:  756
Symbols:
+ _$s10Foundation3URLV06isFileB0Sbvg
+ _$s10Foundation3URLV6schemeSSSgvg
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s10Foundation6LocaleVMn
+ _$s7JetCore0A9PackAssetV12HTTPResponseV7headersSDyS2SGvg
+ _$s7JetCore0A9PackAssetV8MetadataV12httpResponseAC12HTTPResponseVSgvg
+ _$s7JetCore16LocalPreferencesC16bundleIdentifierACSS_tcfc
+ _$s7JetCore22URLJetPackAssetRequestV11withUsageIDyACSSSgF
+ _$s7JetCore22URLJetPackAssetRequestV3url12sourcePolicyAC10Foundation3URLV_AA0adef6SourceI0OtcfC
+ _$sSS10lowercasedSSyF
+ _$sSo8NSBundleC7JetCoreE10isTvFamilyySbSSFZ
+ _$sSo8NSBundleC7JetCoreE13isMusicFamilyySbSSFZ
+ _$sSy10FoundationE22caseInsensitiveCompareySo18NSComparisonResultVqd__SyRd__lF
+ _$sSy10FoundationE5range2of7optionsAB6localeSnySS5IndexVGSgqd___So22NSStringCompareOptionsVAiA6LocaleVSgtSyRd__lF
+ _kSecPolicyNameAppleAMPService
- _$s10Foundation4DateVSLAAMc
- _$s7JetCore22URLJetPackAssetRequestV3url12sourcePolicy7usageIDAC10Foundation3URLV_AA0adef6SourceI0OSSSgtcfC
- _$sSL2leoiySbx_xtFZTj
CStrings:
+ " cached assets, no stale versions detected"
+ " is not from production, skipping version check"
+ "AMSIgnoreServerTrustEvaluation"
+ "ISIgnoreExtendedValidation"
+ "com.apple.AppleMediaServices"
+ "com.apple.itunesstored"
+ "jetPackDisableDownloadSecurity"
+ "recently deployed"
+ "set_alwaysPerformDefaultTrustEvaluation:"
+ "set_tlsTrustPinningPolicyName:"
+ "x-apple-application-env"
+ "x-daiquiri-instance"
- " valid cached assets are up to date"
```
