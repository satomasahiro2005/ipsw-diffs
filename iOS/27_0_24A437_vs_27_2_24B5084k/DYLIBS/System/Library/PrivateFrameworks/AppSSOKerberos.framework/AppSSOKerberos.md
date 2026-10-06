## AppSSOKerberos

> `/System/Library/PrivateFrameworks/AppSSOKerberos.framework/AppSSOKerberos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x201c4` | `0x209c0` | **`+0x7fc`** |
| `__TEXT.__oslogstring` | `0x283b` | `0x28dd` | **`+0xa2`** |
| `__TEXT.__cstring` | `0x1ac0` | `0x1b13` | **`+0x53`** |
| `__AUTH_CONST.__cfstring` | `0x1800` | `0x1840` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1e74` | `0x1eb4` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a8` | `0x14d8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x34d0` | `0x34f0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x850` | `0x868` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x820` | `0x824` | **`+0x4`** |

### Other Changes

```diff

-643.0.47.0.0
+643.40.23.0.0

-  Functions: 1010
-  Symbols:   1543
-  CStrings:  554
+  Functions: 1018
+  Symbols:   1547
+  CStrings:  558
Symbols:
+ +[SOKerberosAuthentication updateADPasswordHighWaterMark:]
+ -[SOKerberosRealmSettings dateADPasswordLastChangedHighWaterMark]
+ -[SOKerberosRealmSettings setDateADPasswordLastChangedHighWaterMark:]
+ -[SOKerberosRealmSettings setUserPrincipalNameForADPasswordHighWaterMark:]
+ -[SOKerberosRealmSettings userPrincipalNameForADPasswordHighWaterMark]
+ GCC_except_table21
+ GCC_except_table66
+ GCC_except_table67
+ GCC_except_table68
+ GCC_except_table69
- GCC_except_table15
- GCC_except_table20
- GCC_except_table58
- GCC_except_table59
- GCC_except_table60
- GCC_except_table61
CStrings:
+ "AD password high water mark: %@ -> %@"
+ "Ignoring stale AD password data: KDC returned passwordLastSet %@ which is older than the newest value seen for this user %@"
+ "dateADPasswordLastChangedHighWaterMark"
+ "userPrincipalNameForADPasswordHighWaterMark"
```
