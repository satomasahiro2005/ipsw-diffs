## TipsCore

> `/System/Library/PrivateFrameworks/TipsCore.framework/TipsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3874` | `0xb46d0` | **`+0xe5c`** |
| `__TEXT.__cstring` | `0x50a3` | `0x5173` | **`+0xd0`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0xb4` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0x2350` | `0x23d0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xfdc` | `0x1040` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0xe8f0` | `0xe950` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d70` | `0x3dc0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x141e` | `0x1465` | **`+0x47`** |
| `__AUTH_CONST.__cfstring` | `0x55a0` | `0x55e0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8c08` | `0x8c38` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3478` | `0x34a8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x11c8` | `0x11f0` | **`+0x28`** |
| `__DATA.__bss` | `0x2b10` | `0x2b30` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x488` | `0x4a0` | **`+0x18`** |
| `__TEXT.__const` | `0x2b44` | `0x2b54` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7d0` | `0x7d8` | **`+0x8`** |

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking

-  Functions: 5428
-  Symbols:   5823
-  CStrings:  1137
+  Functions: 5447
+  Symbols:   5851
+  CStrings:  1149
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
