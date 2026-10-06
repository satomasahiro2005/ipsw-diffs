## RemoteManagement

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2357` | `0x2397` | **`+0x40`** |
| `__TEXT.__text` | `0x4bc9c` | `0x4bcc8` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x1ae0` | `0x1b00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x13f8` | `0x1418` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1be0` | `0x1bf0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x658` | `0x660` | **`+0x8`** |

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Functions: 1388
-  Symbols:   1621
-  CStrings:  689
+  Functions: 1389
+  Symbols:   1623
+  CStrings:  691
Symbols:
+ +[RMFeatureFlags isAccountTakeoverEnabled]
+ -[RMManagedDevice isAwaitingConfigurationWithScope:]
+ _RMConfigurationTypeExtensibleSSO
- -[RMManagedDevice isAwaitingConfiguration]
CStrings:
+ "AccountTakeover"
+ "com.apple.configuration.extensible-sso"
```
