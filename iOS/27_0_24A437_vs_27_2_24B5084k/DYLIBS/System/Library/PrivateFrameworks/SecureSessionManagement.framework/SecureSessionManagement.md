## SecureSessionManagement

> `/System/Library/PrivateFrameworks/SecureSessionManagement.framework/SecureSessionManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37828` | `0x390f0` | **`+0x18c8`** |
| `__TEXT.__eh_frame` | `0x26e0` | `0x2bf8` | **`+0x518`** |
| `__TEXT.__oslogstring` | `0x876` | `0xa96` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0xb80` | `0xce8` | **`+0x168`** |
| `__TEXT.__const` | `0x12c8` | `0x13c8` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x7ec` | `0x8c0` | **`+0xd4`** |
| `__AUTH.__data` | `0x850` | `0x8f8` | **`+0xa8`** |
| `__DATA.__bss` | `0xb90` | `0xc10` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x4d0` | `0x550` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0xc30` | `0xca8` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x6c0` | `0x728` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x6b4` | `0x718` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x620` | `0x680` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x1ec` | `0x23c` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2bb` | `0x2fb` | **`+0x40`** |
| `__DATA.__data` | `0x3d8` | `0x410` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x134` | `0x168` | **`+0x34`** |
| `__TEXT.__swift_as_entry` | `0xa4` | `0xbc` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x6c` | `0x70` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x60` | `0x64` | **`+0x4`** |

### Other Changes

```diff

-217.11.0.0.0
+242.1.0.0.0

-  Functions: 706
-  Symbols:   324
-  CStrings:  51
+  Functions: 767
+  Symbols:   332
+  CStrings:  61
Symbols:
+ ___swift_closure_destructor.175Tm
+ _swift_dynamicCast
+ _symbolic $s23SecureSessionManagement17KeyRecordOrderingP
+ _symbolic Sb
+ _symbolic _____ 23SecureSessionManagement08FollowerB7ManagerC22CaptureAlreadyInFlightV
+ _symbolic _____SgyYaYbcSg s6UInt64V
+ _symbolic ______p 23SecureSessionManagement17KeyRecordOrderingP
+ _symbolic ______p 23SecureSessionManagement18KeyRecordProvidingP
+ _symbolic ______pSg 23SecureSessionManagement17KeyRecordOrderingP
- ___swift_closure_destructor.146Tm
CStrings:
+ "Attempted to remove tag=%llu while in-flight"
+ "Debug tag %llu in use; %s"
+ "Holding rotated-out tag=%llu — capture in flight"
+ "Removed secure session tag=%llu"
+ "commitSecureSessionIndex: failed to advance tag=%llu from=%ld: %@"
+ "nextSecureSessionIndex called on key store that doesn't provide ordering"
+ "nextSecureSessionIndex: a capture is already in flight for tag=%llu"
+ "nextSecureSessionIndex: active tag=%llu has no backing record; clearing stale cache and requesting a new session"
+ "no active session"
+ "overriding active session"
```
