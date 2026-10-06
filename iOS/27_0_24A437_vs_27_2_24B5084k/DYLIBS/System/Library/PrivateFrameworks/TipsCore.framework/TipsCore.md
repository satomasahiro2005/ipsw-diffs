## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4220` | `0xb3750` | **`-0xad0`** |
| `__AUTH_CONST.__cfstring` | `0x54a0` | `0x55a0` | **`+0x100`** |
| `__TEXT.__dlopen_cstrs` | `0xb4` | `—` | **`-0xb4`** |
| `__DATA_CONST.__const` | `0x23c0` | `0x2350` | **`-0x70`** |
| `__TEXT.__gcc_except_tab` | `0x1040` | `0xfdc` | **`-0x64`** |
| `__AUTH_CONST.__const` | `0x4050` | `0x40b0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x5103` | `0x50a3` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0xe920` | `0xe8d0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x1465` | `0x141e` | **`-0x47`** |
| `__TEXT.__unwind_info` | `0x34a0` | `0x3470` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x11e8` | `0x11c8` | **`-0x20`** |
| `__DATA.__bss` | `0x2b30` | `0x2b10` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d90` | `0x3d70` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x4a0` | `0x488` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x8bf0` | `0x8c08` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7d4` | `0x7cc` | **`-0x8`** |

### Other Changes

```diff

-866.0.0.0.0
+866.2.2.0.0

-  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 5442
-  Symbols:   5844
-  CStrings:  1139
+  Functions: 5428
+  Symbols:   5822
+  CStrings:  1137
Symbols:
+ +[NSLocale(TPSCoreAdditions) tps_systemLanguages]
+ +[TPSCommonDefines isTVUI]
+ +[TPSContentURLController normalizeVirtualMachineModelIfNeeded:]
+ GCC_except_table75
+ GCC_except_table82
+ _TPSCommonDefinesCollectionNameHardware
+ _TPSCommonDefinesCollectionOverrideMajorVersion
+ _swift_getObjCClassFromMetadata
- -[TPSURLSessionACAuthHandler setSsoAuthenticator:]
- -[TPSURLSessionACAuthHandler ssoAuthenticator]
- -[TPSURLSessionManager setUrlRedirector:]
- -[TPSURLSessionManager urlRedirector]
- GCC_except_table59
- GCC_except_table74
- _OBJC_IVAR_$_TPSURLSessionACAuthHandler._ssoAuthenticator
- _OBJC_IVAR_$_TPSURLSessionManager._urlRedirector
- _PingPongClientLibrary
- _PingPongClientLibraryCore
- _PingPongClientLibraryCore.frameworkLibrary
- ___60-[TPSURLSessionACAuthHandler _authenticateWithAppleConnect:]_block_invoke
- ___60-[TPSURLSessionACAuthHandler _authenticateWithAppleConnect:]_block_invoke_2
- ___PingPongClientLibraryCore_block_invoke
- ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
- ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
- ___getPPCExtensibleSSOAuthenticatorClass_block_invoke
- ___getPPCRedirectClass_block_invoke
- ___getkExtensibleSSOTokenKeySymbolLoc_block_invoke
- ___getkExtensibleSSOUsernameKeySymbolLoc_block_invoke
- __sl_dlopen
- _abort_report_np
- _audit_stringPingPongClient
- _dlerror
- _dlsym
- _getPPCExtensibleSSOAuthenticatorClass.softClass
- _getPPCRedirectClass.softClass
- _getkExtensibleSSOTokenKeySymbolLoc.ptr
- _getkExtensibleSSOUsernameKeySymbolLoc.ptr
- _objc_getClass
CStrings:
+ "27"
+ "A2117"
+ "A2737"
+ "A3256"
+ "A3281"
+ "A3357"
+ "AppleTV"
+ "IsVirtualDevice"
+ "ec5be57655e13fa5afb54167ccf91580f8bd99dc"
+ "hardware"
- "Mapped URL Request: %@"
- "PPCExtensibleSSOAuthenticator"
- "PPCRedirect"
- "PPCRedirect initialized."
- "PPCRedirect not found."
- "Unable to find class %s"
- "X-AppleConnect-Token"
- "X-AppleConnect-User"
- "kExtensibleSSOTokenKey"
- "kExtensibleSSOUsernameKey"
- "softlink:o:path:/System/Library/PrivateFrameworks/PingPongClient.framework/PingPongClient"
- "v24@?0@\"NSDictionary\"8@\"NSError\"16"
```
