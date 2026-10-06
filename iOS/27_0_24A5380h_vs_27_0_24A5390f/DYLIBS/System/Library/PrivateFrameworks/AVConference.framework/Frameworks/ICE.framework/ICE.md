## ICE

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d420` | `0x2d94c` | **`+0x52c`** |
| `__TEXT.__oslogstring` | `0xc02e` | `0xc37a` | **`+0x34c`** |
| `__TEXT.__cstring` | `0x175b` | `0x1777` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x448` | `0x458` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x358` | `0x360` | **`+0x8`** |

### Other Changes

```diff

-2235.55.1.0.0
+2235.57.1.0.0

-  Functions: 522
-  Symbols:   474
-  CStrings:  771
+  Functions: 529
+  Symbols:   479
+  CStrings:  775
Symbols:
+ _CCHmac
+ _ICEFreeRelayCandidatePairAllocsOnError
+ _MicroToMiddle32
+ _VCStunAuth_ValidateSTUNMessageIntegrity
+ _timingsafe_bcmp
CStrings:
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ICE.subproj/Sources/ICEMessage.c:%d: MESSAGE_INTEGRITY validation failed in BINDING_REQUEST."
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ICE.subproj/Sources/ICEMessage.c:%d: MESSAGE_INTEGRITY validation failed in BINDING_RESPONSE."
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ICE.subproj/Sources/ICEMessage.c:%d: Missing MESSAGE_INTEGRITY in BINDING_REQUEST."
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ICE.subproj/Sources/ICEMessage.c:%d: Missing MESSAGE_INTEGRITY in BINDING_RESPONSE."
+ " [%s] %s:%d Attempt to retain already released ICEList object %p"
+ "HRESULT ProcessBindingRequest(PICEINFO, PICELIST, PSTUNMSG, PIPPORT, double, const unsigned char *, int)"
- " [%s] %s:%d Attempt to retain already released ICEList object %x for call '%d'"
- "HRESULT ProcessBindingRequest(PICEINFO, PICELIST, PSTUNMSG, PIPPORT, double)"
```
