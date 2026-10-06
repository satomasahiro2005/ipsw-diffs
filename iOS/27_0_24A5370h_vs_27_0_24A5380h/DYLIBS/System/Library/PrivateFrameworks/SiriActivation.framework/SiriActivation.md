## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6eae0` | `0x6f024` | **`+0x544`** |
| `__TEXT.__oslogstring` | `0x8f6f` | `0x90a8` | **`+0x139`** |
| `__TEXT.__cstring` | `0xc9a2` | `0xca12` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0xb010` | `0xb068` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x2050` | `0x2000` | **`-0x50`** |
| `__DATA.__data` | `0x1610` | `0x1660` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4fa0` | `0x4fe0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x6ea4` | `0x6ec4` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x714` | `0x732` | **`+0x1e`** |
| `__AUTH_CONST.__auth_got` | `0xb70` | `0xb88` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1e28` | `0x1e40` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x34c8` | `0x34d8` | **`+0x10`** |
| `__TEXT.__const` | `0x119c` | `0x11ac` | **`+0x10`** |
| `__DATA.__common` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x714` | `0x71c` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x17f8` | `0x1800` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x504` | `0x508` | **`+0x4`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 2869
-  Symbols:   4601
-  CStrings:  1781
+  Functions: 2870
+  Symbols:   4610
+  CStrings:  1789
Symbols:
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isAssistedLinwoodVoiceResponseFromCompanionEnabled]
+ -[SASPreheatRequest initWithRequestSource:configuration:activationReferenceIdentifier:speechRequestOptions:]
+ -[SASPreheatRequest speechRequestOptions]
+ -[_SASPreheatRequestMutation setSpeechRequestOptions:]
+ _AFPreferencesHeadphonesAlwaysAuthenticatedEnabled
+ _OBJC_IVAR_$_SASPreheatRequest._speechRequestOptions
+ _OBJC_IVAR_$__SASPreheatRequestMutation._speechRequestOptions
+ ___56-[SASRemoteRequestManager _handleRemotePrewarmWithInfo:]_block_invoke
+ ___swift_closure_destructor.240Tm
+ _dispatch_block_create
+ _swift_retain_x26
+ _symbolic So24SASTimeIntervalTransportC
- -[SASPreheatRequest initWithRequestSource:configuration:activationReferenceIdentifier:]
- ___swift_closure_destructor.227Tm
- ___swift_closure_destructor.245Tm
CStrings:
+ "\""
+ "%s #activation #prewarm Remote request manager is preheating presentation"
+ "%s #activation Rejecting VT/RTS activation request since we have a Starting or Active presentation"
+ "%s #prewarm Remote request manager is handling prewarm for %@"
+ "%s 🎧 Headphones Always Authenticated internal setting is ON, returning YES"
+ "SASPreheatRequest::speechRequestOptions"
+ "assisted_linwood_voice_response_from_companion"
+ "speechRequestOptions = %@"
```
