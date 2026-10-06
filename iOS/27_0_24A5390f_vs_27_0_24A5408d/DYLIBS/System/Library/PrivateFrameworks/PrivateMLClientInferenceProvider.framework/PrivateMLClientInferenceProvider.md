## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91b44` | `0x958cc` | **`+0x3d88`** |
| `__AUTH_CONST.__const` | `0x13a8` | `0x1a38` | **`+0x690`** |
| `__TEXT.__swift5_capture` | `0x33c` | `0x7ac` | **`+0x470`** |
| `__TEXT.__eh_frame` | `0x27e0` | `0x2b48` | **`+0x368`** |
| `__TEXT.__const` | `0x1e58` | `0x1ff8` | **`+0x1a0`** |
| `__TEXT.__unwind_info` | `0xcc8` | `0xdc8` | **`+0x100`** |
| `__AUTH_CONST.__auth_got` | `0x19f0` | `0x1ac8` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x648` | `0x720` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x3dcb` | `0x3e8b` | **`+0xc0`** |
| `__AUTH.__data` | `0x578` | `0x620` | **`+0xa8`** |
| `__TEXT.__cstring` | `0xdeb` | `0xe6b` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x648` | `0x68c` | **`+0x44`** |
| `__TEXT.__swift_as_cont` | `0x20c` | `0x24c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xb32` | `0xb6e` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x910` | `0x938` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0x104` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0xf0` | `0x110` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc41` | `0xc2f` | **`-0x12`** |
| `__DATA.__data` | `0x508` | `0x518` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xd0` | `0xe0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x928` | `0x920` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x74` | `0x78` | **`+0x4`** |

### Other Changes

```diff

-212.0.0.0.0
+215.2.0.0.0

-  Functions: 876
-  Symbols:   512
-  CStrings:  381
+  Functions: 960
+  Symbols:   526
+  CStrings:  388
Symbols:
+ _OBJC_CLASS_$_NSLock
+ __DATA__TtCC32PrivateMLClientInferenceProvider20NewInferenceProviderP33_BC0459B62473488D872E575A6C61BEF723SynchronizedAIRReporter
+ __IVARS__TtCC32PrivateMLClientInferenceProvider20NewInferenceProviderP33_BC0459B62473488D872E575A6C61BEF723SynchronizedAIRReporter
+ __METACLASS_DATA__TtCC32PrivateMLClientInferenceProvider20NewInferenceProviderP33_BC0459B62473488D872E575A6C61BEF723SynchronizedAIRReporter
+ ___swift_closure_destructor.140Tm
+ ___swift_closure_destructor.185Tm
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic So6NSLockC
+ _symbolic _____ 32PrivateMLClientInferenceProvider03NewcD0C23SynchronizedAIRReporter33_BC0459B62473488D872E575A6C61BEF7LLC
+ _symbolic _____SgXw 32PrivateMLClientInferenceProvider03NewcD0C
+ _symbolic _____SgXwz_Xx 32PrivateMLClientInferenceProvider03NewcD0C
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- ___swift_closure_destructor.155Tm
CStrings:
+ "%s request was cancelled: %s"
+ "Caller uid is 0 (root); clearing userID because uid 0 is an invalid XPC target and would trap the connection"
+ "Failed to emit AppleIntelligence end event: %@"
+ "Failed to emit AppleIntelligence start event: %@"
+ "Failed to emit PCC network connection report: %@"
+ "Failed to emit PCC network connection report: could not create EventReporter"
+ "PrivateMLClient request was cancelled: "
+ "Request cancelled: "
+ "com.apple.pccagent.imagecache"
+ "com.apple.privatemlclient.air_metrics"
+ "requestCancelled"
- "Failed to emit AppleIntelligence end event for %{public}s: %@"
- "Failed to emit AppleIntelligence start event for requestOneShot: %@"
- "Failed to emit AppleIntelligence start event for requestStream: %@"
- "PrivateMLRequestError.com.apple.pccagent.imagecache"
```
