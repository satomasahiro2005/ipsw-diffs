## HelpKit

> `/System/Library/PrivateFrameworks/HelpKit.framework/HelpKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c244` | `0x2d2a0` | **`+0x105c`** |
| `__TEXT.__dlopen_cstrs` | `—` | `0x10e` | **`+0x10e`** |
| `__TEXT.__cstring` | `0x1d1f` | `0x1dbf` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xf18` | `0xfb0` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0xb00` | `0xb6c` | **`+0x6c`** |
| `__AUTH_CONST.__objc_const` | `0x5658` | `0x56b8` | **`+0x60`** |
| `__DATA.__bss` | `0x1f8` | `0x238` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2788` | `0x27c8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xbb8` | `0xbf8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x383c` | `0x386c` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x550` | `0x578` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x43c` | `0x444` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1262
-  Symbols:   2355
-  CStrings:  468
+  Functions: 1283
+  Symbols:   2383
+  CStrings:  476
Symbols:
+ -[HLPURLSessionACAuthHandler setSsoAuthenticator:]
+ -[HLPURLSessionACAuthHandler ssoAuthenticator]
+ -[HLPURLSessionManager setUrlRedirector:]
+ -[HLPURLSessionManager urlRedirector]
+ _OBJC_IVAR_$_HLPURLSessionACAuthHandler._ssoAuthenticator
+ _OBJC_IVAR_$_HLPURLSessionManager._urlRedirector
+ _PingPongClientLibrary
+ _PingPongClientLibraryCore
+ _PingPongClientLibraryCore.frameworkLibrary
+ ___57-[HLPURLSessionACAuthHandler authenticateWithCompletion:]_block_invoke
+ ___57-[HLPURLSessionACAuthHandler authenticateWithCompletion:]_block_invoke_2
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
+ "%s"
+ "PPCExtensibleSSOAuthenticator"
+ "PPCRedirect"
+ "Unable to find class %s"
+ "kExtensibleSSOTokenKey"
+ "kExtensibleSSOUsernameKey"
+ "softlink:o:path:/System/Library/PrivateFrameworks/PingPongClient.framework/PingPongClient"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
```
