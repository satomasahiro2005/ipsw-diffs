## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3350` | `0xb4220` | **`+0xed0`** |
| `__TEXT.__cstring` | `0x5043` | `0x5103` | **`+0xc0`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0xb4` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0x2340` | `0x23c0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xfdc` | `0x1040` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xe8c0` | `0xe920` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d40` | `0x3d90` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x141e` | `0x1465` | **`+0x47`** |
| `__AUTH_CONST.__cfstring` | `0x5460` | `0x54a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8bc0` | `0x8bf0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3470` | `0x34a0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x11c8` | `0x11e8` | **`+0x20`** |
| `__DATA.__bss` | `0x2b10` | `0x2b30` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x488` | `0x4a0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7cc` | `0x7d4` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 5422
-  Symbols:   5817
-  CStrings:  1127
+  Functions: 5442
+  Symbols:   5844
+  CStrings:  1139
Symbols:
+ -[TPSURLSessionACAuthHandler setSsoAuthenticator:]
+ -[TPSURLSessionACAuthHandler ssoAuthenticator]
+ -[TPSURLSessionManager setUrlRedirector:]
+ -[TPSURLSessionManager urlRedirector]
+ _OBJC_IVAR_$_TPSURLSessionACAuthHandler._ssoAuthenticator
+ _OBJC_IVAR_$_TPSURLSessionManager._urlRedirector
+ _PingPongClientLibrary
+ _PingPongClientLibraryCore
+ _PingPongClientLibraryCore.frameworkLibrary
+ ___60-[TPSURLSessionACAuthHandler _authenticateWithAppleConnect:]_block_invoke
+ ___60-[TPSURLSessionACAuthHandler _authenticateWithAppleConnect:]_block_invoke_2
+ ___PingPongClientLibraryCore_block_invoke
+ ___block_descriptor_40_e8_32r_e5_v8?0lr32l8
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ ___getPPCExtensibleSSOAuthenticatorClass_block_invoke
+ ___getPPCRedirectClass_block_invoke
+ ___getkExtensibleSSOTokenKeySymbolLoc_block_invoke
+ ___getkExtensibleSSOUsernameKeySymbolLoc_block_invoke
+ __sl_dlopen
+ _abort_report_np
+ _audit_stringPingPongClient
+ _dlerror
+ _dlsym
+ _getPPCExtensibleSSOAuthenticatorClass.softClass
+ _getPPCRedirectClass.softClass
+ _getkExtensibleSSOTokenKeySymbolLoc.ptr
+ _getkExtensibleSSOUsernameKeySymbolLoc.ptr
+ _objc_getClass
- _swift_retain_x9
CStrings:
+ "Mapped URL Request: %@"
+ "PPCExtensibleSSOAuthenticator"
+ "PPCRedirect"
+ "PPCRedirect initialized."
+ "PPCRedirect not found."
+ "Unable to find class %s"
+ "X-AppleConnect-Token"
+ "X-AppleConnect-User"
+ "kExtensibleSSOTokenKey"
+ "kExtensibleSSOUsernameKey"
+ "softlink:o:path:/System/Library/PrivateFrameworks/PingPongClient.framework/PingPongClient"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
```
