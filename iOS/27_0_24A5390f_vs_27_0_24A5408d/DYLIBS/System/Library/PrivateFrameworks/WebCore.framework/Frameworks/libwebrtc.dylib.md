## libwebrtc.dylib

> `/System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaac6a4` | `0xaaca98` | **`+0x3f4`** |
| `__TEXT.__cstring` | `0x55f47` | `0x55fae` | **`+0x67`** |
| `__TEXT.__unwind_info` | `0x10db0` | `0x10dc8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1880` | `0x1888` | **`+0x8`** |

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 18368
-  Symbols:   23603
-  CStrings:  9078
+  Functions: 18374
+  Symbols:   23609
+  CStrings:  9080
Symbols:
+ _CFDictionaryGetValueIfPresent
+ __ZN4absl22internal_any_invocable12LocalInvokerILb0EbRZN6webrtc25WebRtcVideoReceiveChannel16OnPacketReceivedENS2_17RtpPacketReceivedEE3$_0JRKS4_EEET0_PNS0_15TypeErasedStateEDpNS0_18ForwardedParameterIT2_E4typeE
+ __ZN4absl22internal_any_invocable12LocalInvokerILb0EbRZN6webrtc25WebRtcVoiceReceiveChannel16OnPacketReceivedENS2_17RtpPacketReceivedEE3$_0JRKS4_EEET0_PNS0_15TypeErasedStateEDpNS0_18ForwardedParameterIT2_E4typeE
+ __ZN4absl22internal_any_invocable22LocalManagerNontrivialIZN6webrtc25WebRtcVideoReceiveChannel16OnPacketReceivedENS2_17RtpPacketReceivedEE3$_0EEvNS0_14FunctionToCallEPNS0_15TypeErasedStateES8_
+ __ZN4absl22internal_any_invocable22LocalManagerNontrivialIZN6webrtc25WebRtcVoiceReceiveChannel16OnPacketReceivedENS2_17RtpPacketReceivedEE3$_0EEvNS0_14FunctionToCallEPNS0_15TypeErasedStateES8_
+ __ZN6webrtc10I010Buffer12MutableDataUEv
+ __ZN6webrtc10I010Buffer12MutableDataVEv
+ __ZN6webrtc10I010Buffer12MutableDataYEv
+ __ZN6webrtc10I010Buffer6CreateEii
+ __ZN6webrtc10I420Buffer6CreateEii
+ __ZZN6webrtc5Event4WaitENS_9TimeDeltaES1_ENK3$_0clENSt3__18optionalI8timespecEE
- _CFDictionaryContainsKey
- __ZN4absl22internal_any_invocable13RemoteInvokerILb0EbRNSt3__114__bind_front_tIMN6webrtc25WebRtcVideoReceiveChannelEFbRKNS4_17RtpPacketReceivedEEJPS5_EEEJS8_EEET0_PNS0_15TypeErasedStateEDpNS0_18ForwardedParameterIT2_E4typeE
- __ZN4absl22internal_any_invocable13RemoteInvokerILb0EbRNSt3__114__bind_front_tIMN6webrtc25WebRtcVoiceReceiveChannelEFbRKNS4_17RtpPacketReceivedEEJPS5_EEEJS8_EEET0_PNS0_15TypeErasedStateEDpNS0_18ForwardedParameterIT2_E4typeE
- __ZN6webrtc25WebRtcVideoReceiveChannel31MaybeCreateDefaultReceiveStreamERKNS_17RtpPacketReceivedE
- __ZN6webrtc25WebRtcVoiceReceiveChannel31MaybeCreateDefaultReceiveStreamERKNS_17RtpPacketReceivedE
CStrings:
+ "Event::Wait pthread_cond_timedwait failed with error "
+ "Event::Wait pthread_cond_wait failed with error "
```
