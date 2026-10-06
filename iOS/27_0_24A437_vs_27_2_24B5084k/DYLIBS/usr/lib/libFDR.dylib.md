## libFDR.dylib

> `/usr/lib/libFDR.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b7d4` | `0x8bf0c` | **`+0x738`** |
| `__TEXT.__cstring` | `0x235d5` | `0x23771` | **`+0x19c`** |
| `__AUTH_CONST.__cfstring` | `0xfba0` | `0xfbe0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1228` | `0x1220` | **`-0x8`** |

### Other Changes

```diff

-1636.0.17.0.0
+1636.40.9.0.0

-  Functions: 4634
-  Symbols:   1726
-  CStrings:  4198
+  Functions: 4645
+  Symbols:   1729
+  CStrings:  4208
Symbols:
+ _AMFDRModuleCertificationWithOptionsAndPermissions
+ __AMFDRModuleCertificationWithOptions
+ __getComponentTypeForInstance
CStrings:
+ "AMFDRModuleCertificationWithOptionsAndPermissions"
+ "AMSupportRsaCreateDataFromPem failed for permission cert"
+ "CFDataCreate failed for permCertDerData"
+ "CertifyPermissionCert"
+ "Failed to allocate infoOptions"
+ "_AMFDRDiagnosticCopyComponentTypesInfoFromSealingManifest"
+ "_AMFDRDiagnosticCopyComponentTypesInfoFromSealingMap"
+ "_AMFDRModuleCertificationWithOptions"
+ "_AMFDRSupportBase64Encode failed for permission cert"
+ "amfdr->cert is not a CFDataRef"
+ "x-fdr-auth-cert"
- "AMFDRModuleCertificationWithOptions"
```
