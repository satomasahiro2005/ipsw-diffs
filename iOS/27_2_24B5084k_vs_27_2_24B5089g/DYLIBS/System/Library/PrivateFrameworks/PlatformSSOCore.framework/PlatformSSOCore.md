## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x982c0` | `0x98550` | **`+0x290`** |
| `__AUTH_CONST.__objc_const` | `0x14d58` | `0x14e40` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x7bc0` | `0x7c20` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6330` | `0x6388` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x35a0` | `0x35f0` | **`+0x50`** |
| `__TEXT.__cstring` | `0xae28` | `0xae78` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1fd7` | `0x2027` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0xc20` | `0xc60` | **`+0x40`** |
| `__DATA.__bss` | `0x771` | `0x791` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d48` | `0x2d68` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2190` | `0x21b0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x9c0` | `0x9d0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdb8` | `0xdc0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x658` | `0x65c` | **`+0x4`** |

### Other Changes

```diff

-643.40.23.0.0
+643.40.27.0.0

-  Functions: 3858
-  Symbols:   5854
-  CStrings:  1769
+  Functions: 3869
+  Symbols:   5877
+  CStrings:  1775
Symbols:
+ +[POKeychainAccess isRunningInTestProcess]
+ -[POKeychainHelper .cxx_destruct]
+ -[POKeychainHelper init]
+ -[POKeychainHelper keychainAccess]
+ -[POKeychainHelper setKeychainAccess:]
+ -[POTokenHelper findInfoForTokenId:uid:]
+ _NSClassFromString
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_POKeychainAccess
+ _OBJC_IVAR_$_POKeychainHelper._keychainAccess
+ _OBJC_METACLASS_$_POKeychainAccess
+ _PO_LOG_POKeychainAccess.log
+ _PO_LOG_POKeychainAccess.once
+ __OBJC_$_CLASS_METHODS_POKeychainAccess
+ __OBJC_$_CLASS_PROP_LIST_POKeychainAccess
+ __OBJC_$_INSTANCE_VARIABLES_POKeychainHelper
+ __OBJC_$_PROP_LIST_POKeychainHelper
+ __OBJC_CLASS_RO_$_POKeychainAccess
+ __OBJC_METACLASS_RO_$_POKeychainAccess
+ ___42+[POKeychainAccess isRunningInTestProcess]_block_invoke
+ ___PO_LOG_POKeychainAccess_block_invoke
+ _isRunningInTestProcess.isTest
+ _isRunningInTestProcess.onceToken
CStrings:
+ "%s tokenId = %{public}@, uid = %{public}@ on %@"
+ "-[POTokenHelper findInfoForTokenId:uid:]"
+ "POKeychainAccess"
+ "XCTestCase"
+ "XCTestConfigurationFilePath"
+ "XCTestSessionIdentifier"
+ "isRunningInTestProcess is true"
- "-[POTokenHelper findInfoForTokenId:]"
```
