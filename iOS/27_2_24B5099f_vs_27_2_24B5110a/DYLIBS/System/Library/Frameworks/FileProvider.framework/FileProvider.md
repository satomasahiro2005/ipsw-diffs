## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e738` | `0x12e7c8` | **`+0x90`** |
| `__TEXT.__cstring` | `0x14f9f` | `0x15005` | **`+0x66`** |
| `__AUTH_CONST.__cfstring` | `0x116c0` | `0x11720` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x250f8` | `0x25128` | **`+0x30`** |
| `__TEXT.__ustring` | `0x25a` | `0x288` | **`+0x2e`** |
| `__TEXT.__objc_methlist` | `0xeaa4` | `0xeabc` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x7150` | `0x7160` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x62a0` | `0x62a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x59a8` | `0x59b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10d4` | `0x10d8` | **`+0x4`** |

### Other Changes

```diff

-4838.40.130.0.2
+4838.42.2.0.0

-  Functions: 7488
-  Symbols:   11246
-  CStrings:  4071
+  Functions: 7491
+  Symbols:   11249
+  CStrings:  4076
Symbols:
+ -[FPProviderDomain owningApplicationIsInstallationHeld]
+ -[FPProviderDomain setOwningApplicationIsInstallationHeld:]
+ _OBJC_IVAR_$_FPProviderDomain._owningApplicationIsInstallationHeld
Functions:
~ -[FPProviderDomain encodeWithCoder:] : 948 -> 968
~ -[FPProviderDomain initWithCoder:] : 1448 -> 1468
~ -[FPProviderDomain description] : 1524 -> 1560
~ -[FPProviderDomain isHidden] : 88 -> 100
+ sub_1a98a1ca8
~ -[FPProviderDomain localizedDisconnectionBannerText] : 444 -> 428
- -[FPProviderDomain setSupportedSearchFilters:]
+ -[FPProviderDomain setSupportedSearchFilters:]
- -[FPProviderDomain setDomainUserInfo:]
+ -[FPProviderDomain setDomainUserInfo:]
- -[FPProviderDomain setProgress:]
+ -[FPProviderDomain progress]
+ -[FPProviderDomain setDomain:]
+ -[FPProviderDomain purposeIdentifier]
~ _FPConnectionStateToPrettyString : 284 -> 296
CStrings:
+ "(⏹  installation held)"
+ ",appHeld"
+ ",installationHeld"
+ "4838.42.2"
+ "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
+ "DISCONNECTION_REASON_INSTALLATION_HELD_%@"
+ "_owningApplicationIsInstallationHeld"
- "4838.40.130.0.2"
- "<%@:%p id:\"%@\" name:\"%@\" urls(%d%s):%@ db:%@%@ state:%s%s%s%s%s%s%s%s features:%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%s%@%@>"
```
