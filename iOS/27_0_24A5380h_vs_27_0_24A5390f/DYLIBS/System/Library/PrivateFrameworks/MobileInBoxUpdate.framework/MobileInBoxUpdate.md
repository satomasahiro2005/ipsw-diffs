## MobileInBoxUpdate

> `/System/Library/PrivateFrameworks/MobileInBoxUpdate.framework/MobileInBoxUpdate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xff0` | `0x1698` | **`+0x6a8`** |
| `__TEXT.__text` | `0x332bc` | `0x333d8` | **`+0x11c`** |
| `__AUTH_CONST.__cfstring` | `0x1d60` | `0x1de0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1871` | `0x18c1` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x2699` | `0x26b9` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x18e8` | `0x18f8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf38` | `0xf40` | **`+0x8`** |

### Other Changes

```diff

-274.0.0.0.0
+274.0.9.0.0

-  Functions: 1401
-  Symbols:   1918
-  CStrings:  493
+  Functions: 1402
+  Symbols:   1923
+  CStrings:  497
Symbols:
+ +[MIBUCertHelper _pandoraCertificatesForContext:error:]
+ +[MIBUCertHelper pandoraCertsDataForContext:error:]
+ -[MIBUTestPreferences reportingServerURL]
+ ___55+[MIBUCertHelper _pandoraCertificatesForContext:error:]_block_invoke
+ _fdr_pandoraks_personalization_nonprod_cert_pem
+ _fdr_pandoraks_personalization_nonprod_cert_pem_len
+ _fdr_pandoraks_personalization_prod_cert_pem
+ _fdr_pandoraks_personalization_prod_cert_pem_len
- +[MIBUCertHelper _pandoraCertificates:]
- +[MIBUCertHelper pandoraCertsData:]
- ___39+[MIBUCertHelper _pandoraCertificates:]_block_invoke
CStrings:
+ "ReportingServerURL"
+ "Unrecognized pandora cert context: %@"
+ "Use Pandora Key Server certificates of grade: %{public}@, use case: %{public}@"
+ "personalization"
+ "seaship"
- "Use Pandora Key Server certificates of grade: %{public}@"
```
