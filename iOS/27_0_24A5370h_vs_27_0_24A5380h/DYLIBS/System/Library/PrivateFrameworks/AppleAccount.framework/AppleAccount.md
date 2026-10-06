## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a534c` | `0x1a7d24` | **`+0x29d8`** |
| `__DATA_DIRTY.__bss` | `0x130` | `0x1a28` | **`+0x18f8`** |
| `__DATA.__bss` | `0x18f30` | `0x17640` | **`-0x18f0`** |
| `__DATA_DIRTY.__data` | `0x2d8` | `0xad8` | **`+0x800`** |
| `__AUTH.__data` | `0x1088` | `0xc38` | **`-0x450`** |
| `__DATA.__data` | `0x445c` | `0x40f4` | **`-0x368`** |
| `__TEXT.__oslogstring` | `0x1351d` | `0x137fd` | **`+0x2e0`** |
| `__TEXT.__eh_frame` | `0x7640` | `0x7768` | **`+0x128`** |
| `__DATA_DIRTY.__objc_data` | `0x4a68` | `0x4b78` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x1228` | `0x1128` | **`-0x100`** |
| `__AUTH_CONST.__cfstring` | `0xd520` | `0xd5e0` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x269e0` | `0x26aa0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x11392` | `0x11452` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x1b68` | `0x1bf8` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x6470` | `0x64e8` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xd2c0` | `0xd330` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xb56c` | `0xb5b4` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x804` | `0x848` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0x14f8` | `0x1538` | **`+0x40`** |
| `__TEXT.__const` | `0x10d70` | `0x10d30` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5240` | `0x5270` | **`+0x30`** |
| `__DATA.__common` | `0xc8` | `0xa8` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x28` | `0x48` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x4fc` | `0x510` | **`+0x14`** |
| `__TEXT.__swift5_fieldmd` | `0x2624` | `0x2630` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x290` | `0x29c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1148` | `0x1150` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2a60` | `0x2a68` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x3a6c` | `0x3a66` | **`-0x6`** |
| `__TEXT.__swift_as_entry` | `0x254` | `0x258` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1061.0.0.0.0
+1063.1.0.0.0

-  Functions: 9114
-  Symbols:   9988
-  CStrings:  3706
+  Functions: 9142
+  Symbols:   10003
+  CStrings:  3725
Symbols:
+ +[NSError(AppleAccount) _aa_sanitizeError:depth:]
+ +[NSError(AppleAccount) _aa_unsanitizeError:depth:]
+ +[NSError(AppleAccount) aa_sanitizeError:]
+ +[NSError(AppleAccount) aa_unsanitizeError:]
+ -[NSError(AppleAccount) _aa_secureCodingErrorAtDepth:]
+ -[NSError(AppleAccount) aa_secureCodingError]
+ _AASanitizeObjectForSecureCoding
+ _NSClassFromString
+ _NSURLErrorFailingURLPeerTrustErrorKey
+ _SecTrustDeserialize
+ _SecTrustGetTypeID
+ _SecTrustSerialize
+ __AADecodeCertChainKey
+ __AAReencodeCertChainKey
+ __OBJC_PROTOCOL_REFERENCE_$_NSSecureCoding
+ ___swift_closure_destructor.110Tm
+ ___swift_closure_destructor.114Tm
+ _serializeSecCertificates
+ _swift_dynamicCastMetatype
+ _swift_task_immediate
+ _swift_task_isCurrentExecutorWithFlags
+ _symbolic yXlXpSgSSc
+ _unserializeSecCertificates
- ___swift_closure_destructor.109Tm
- ___swift_closure_destructor.113Tm
- _get_type_metadata 15Synchronization5MutexVy12AppleAccount20IdentityLoadingStateOG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy12AppleAccount7AltDSIDCAD08IdentityD0V7account_yAD0G0Cc8callback10Foundation4UUIDVSg05knownG2ID14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceVSg06remoteR0AD0G13ObserverTokenVSg5tokentGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScTyyts5Error_pGSgG noncopyable
- _swift_release_x28
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "+aa_sanitizeError: max depth reached, returning userInfo-stripped fallback at depth %lu."
+ "AASanitizeObjectForSecureCoding: max depth exceeded, discarding object of class %@."
+ "IdentityStore initialized while app was backgrounded; deferring observer registration"
+ "NSErrorClientCertificateChainKey"
+ "NSErrorPeerCertificateChainKey"
+ "NSURLErrorFailingURLPeerTrustErrorKey"
+ "Removing object of class %@ from userInfo because it does not conform to NSSecureCoding."
+ "SecTrustSerialize failed: %@"
+ "UIApplication not available in this process"
+ "Unable to read +[UIApplication sharedApplication]"
+ "Unable to read -[UIApplication applicationState]"
+ "_AADecodeCertChainKey: exception deserializing companion key %@: %@"
+ "_AAReencodeCertChainKey: exception serializing cert chain for key %@: %@"
+ "_AA_SANITIZED"
+ "applicationState"
+ "c"
+ "com.apple.siri"
+ "sharedApplication"
+ "startObserving attempt %ld failed: %@. Retrying."
+ "startObserving failed after %ld attempts: %@"
- "Registration deferred: failed to start observing identity changes: %@"
```
