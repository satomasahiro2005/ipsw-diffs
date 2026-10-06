## com.apple.driver.AppleSEPCredentialManager

> `com.apple.driver.AppleSEPCredentialManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4d300` | `0x4dd10` | **`+0xa10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x660` | **`+0x660`** |
| `__DATA_CONST.__kalloc_var` | `0x15e0` | `0x14a0` | **`-0x140`** |
| `__TEXT.__cstring` | `0x13130` | `0x13126` | **`-0xa`** |

### Other Changes

```diff

-944.0.0.0.0
-  Functions: 1015
+949.0.4.0.0
+  Functions: 1016

-  CStrings:  1970
+  CStrings:  1971
CStrings:
+ "!entitlement || ACMKernelUtils::isEntitled(params.owningTask, entitlement)"
+ "%s: %s: DENIED: Entitlement '%s' not found!.\n"
+ "%s: %s: DENIED: Kernel call not allowed!.\n"
+ "%s: %s: Unable to detect EDU mode, will retry on next call.\n"
+ "%s: %s: cmd(%u) requestId(%u) != responseId(%u).\n"
+ "%s: %s: multiuser config not yet populated in _COMM_PAGE_MULTIUSER_CONFIG.\n"
+ "19:41:16"
+ "Jun 18 2026"
+ "checkCallerPermissions"
+ "com.apple.private.applecredentialmanager.daemon.allow"
+ "credential->type == kACMCredentialTypePasscodeValidated2"
+ "params.kernelCaller.allowed"
+ "params.userModeCaller.allowed"
- "%s: %s: requestId(%u) != responseId(%u).\n"
- "22:51:49"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "May 27 2026"
- "_COMM_PAGE_MULTIUSER_CONFIG not available yet"
- "credential->type == kACMCredentialTypePasscodeValidated2 || credential->type == kACMCredentialTypePKITokenValidated2"
- "dataLength == sizeof(ACMCredentialDataPKITokenValidated)"
- "dataLength == sizeof(ACMCredentialDataPKITokenValidated2)"
- "multiuser_flags != 0"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated2"
```
