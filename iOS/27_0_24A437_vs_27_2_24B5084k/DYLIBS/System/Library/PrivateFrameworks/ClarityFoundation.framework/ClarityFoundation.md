## ClarityFoundation

> `/System/Library/PrivateFrameworks/ClarityFoundation.framework/ClarityFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74c8` | `0x7c80` | **`+0x7b8`** |
| `__TEXT.__dlopen_cstrs` | `0x1a3` | `0x207` | **`+0x64`** |
| `__TEXT.__gcc_except_tab` | `0xf4` | `0x140` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x4a3` | `0x4d9` | **`+0x36`** |
| `__TEXT.__cstring` | `0x858` | `0x886` | **`+0x2e`** |
| `__DATA_CONST.__const` | `0x230` | `0x248` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6f0` | `0x708` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x370` | `0x388` | **`+0x18`** |
| `__DATA.__bss` | `0x448` | `0x458` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xafc` | `0xb04` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 227
-  Symbols:   559
-  CStrings:  124
+  Functions: 231
+  Symbols:   568
+  CStrings:  128
Symbols:
+ -[CLFAppAvailabilityChecker requiresMigrationForBundleIdentifier:]
+ GCC_except_table161
+ GCC_except_table167
+ _InstallCoordinationLibraryCore.frameworkLibrary
+ ___InstallCoordinationLibraryCore_block_invoke
+ ___getIXAppInstallCoordinatorClass_block_invoke
+ ___getIXApplicationIdentityClass_block_invoke
+ _audit_stringInstallCoordination
+ _getIXAppInstallCoordinatorClass.softClass
+ _getIXApplicationIdentityClass.softClass
- GCC_except_table159
CStrings:
+ "Failed to determine app replacement source for %@: %@"
+ "IXAppInstallCoordinator"
+ "IXApplicationIdentity"
+ "softlink:r:path:/System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination"
```
