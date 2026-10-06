## SeymourSessionServices

> `/System/Library/PrivateFrameworks/SeymourSessionServices.framework/SeymourSessionServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b9d44` | `0x1bbb68` | **`+0x1e24`** |
| `__TEXT.__eh_frame` | `0xde4c` | `0xe174` | **`+0x328`** |
| `__TEXT.__oslogstring` | `0x6b98` | `0x6df8` | **`+0x260`** |
| `__DATA.__data` | `0x1148` | `0x11a8` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x13308` | `0x13358` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x4230` | `0x4280` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x24f8` | `0x24b8` | **`-0x40`** |
| `__TEXT.__const` | `0x55f0` | `0x5630` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x16a0` | `0x16c8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1f7e` | `0x1f88` | **`+0xa`** |

### Other Changes

```diff

-2027.0.124.0.3
+2027.0.134.0.0

-  Functions: 2986
-  Symbols:   1149
-  CStrings:  570
+  Functions: 2999
+  Symbols:   1150
+  CStrings:  577
Symbols:
+ _symbolic Say_____G 11SeymourCore21RemoteParticipantRoleO
+ _symbolic _____7voucher______7sessionScCyyt______pG12continuation_____yyt_____G10launchTaskt 10Foundation4UUIDV 11SeymourCore7SessionV s5ErrorP 0c6ClientA010TaskHandleC s5NeverO
+ _symbolic _____y_____G 23SeymourClientFoundation20AsyncFlushingChannelV 0A15SessionServices0G6SystemC9Operation33_08AA3A537DC5284B46BAA30D1A0547F1LLO
+ _symbolic _____y______G 23SeymourClientFoundation20AsyncFlushingChannelV8IteratorV 0A15SessionServices0H6SystemC9Operation33_08AA3A537DC5284B46BAA30D1A0547F1LLO
+ _symbolic _____yyt_____G 23SeymourClientFoundation10TaskHandleC s5NeverO
+ _symbolic _____yyt_____GSg 23SeymourClientFoundation10TaskHandleC s5NeverO
+ _symbolic _____yyt______pG 23SeymourClientFoundation10TaskHandleC s5ErrorP
- _symbolic _____7voucher______7sessionScCyyt______pG12continuation_____yyt_____G10launchTaskt 10Foundation4UUIDV 11SeymourCore7SessionV s5ErrorP 0C6Client10TaskHandleC s5NeverO
- _symbolic _____y_____G 13SeymourClient20AsyncFlushingChannelV 0A15SessionServices0F6SystemC9Operation33_08AA3A537DC5284B46BAA30D1A0547F1LLO
- _symbolic _____y______G 13SeymourClient20AsyncFlushingChannelV8IteratorV 0A15SessionServices0G6SystemC9Operation33_08AA3A537DC5284B46BAA30D1A0547F1LLO
- _symbolic _____yyt_____G 13SeymourClient10TaskHandleC s5NeverO
- _symbolic _____yyt_____GSg 13SeymourClient10TaskHandleC s5NeverO
- _symbolic _____yyt______pG 13SeymourClient10TaskHandleC s5ErrorP
CStrings:
+ "Received fetchKeyCertificateContext on remote participant channel from pid %{public}ld"
+ "Received fetchKeyContext on remote participant channel from pid %{public}ld"
+ "Received releaseKeyContext on remote participant channel from pid %{public}ld"
+ "Received remoteParticipantHandshake on remote participant channel from pid %{public}ld"
+ "Received renewKeyContext on remote participant channel from pid %{public}ld"
+ "Received requestDistributedSessionActivation on remote participant channel from pid %{public}ld"
+ "Received sessionUpdated on remote participant channel from pid %{public}ld"
```
