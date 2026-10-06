## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fd69c` | `0x1fed90` | **`+0x16f4`** |
| `__TEXT.__oslogstring` | `0x20f97` | `0x2115b` | **`+0x1c4`** |
| `__AUTH_CONST.__cfstring` | `0x1cf60` | `0x1d060` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x752c` | `0x75ec` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x2556c` | `0x25616` | **`+0xaa`** |
| `__AUTH_CONST.__objc_intobj` | `0x3db0` | `0x3e28` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x1261c` | `0x12674` | **`+0x58`** |
| `__DATA_CONST.__objc_arraydata` | `0x2070` | `0x2030` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x9320` | `0x9358` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6d68` | `0x6da0` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x4c8` | `0x498` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x18288` | `0x182b0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x50b8` | `0x50d8` | **`+0x20`** |
| `__DATA.__bss` | `0xd9a8` | `0xd9c8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x5cb0` | `0x5cc8` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x2f0` | `0x2e0` | **`-0x10`** |

### Other Changes

```diff

-1030.74.0.0.0
+1030.81.0.0.0

-  Functions: 9432
-  Symbols:   1184
-  CStrings:  6340
+  Functions: 9446
+  Symbols:   1185
+  CStrings:  6350
Symbols:
+ _CWFNetworkProfilePropertyConnectivityAssistEnabledKey
CStrings:
+ "ConnectivityAssistEnabled"
+ "GET NAN RADIO SCHEDULE"
+ "NANRTM"
+ "[corewifi] @[%llu.%06llu] %{public}s (%{public}s:%u) Matched cached hybrid interface %{public}@ for APPLE80211_VIRT_IF_ROLE_NAN_DISCOVERY"
+ "[corewifi] AUTO-JOIN: [internal] Applying defaults override for [CWFAutoJoinTriggerAssociatedToNetworkRetry : CWFAutoJoinTriggerNANRealTimeModeEnded] throttle interval (default=%lus, override=%lus)"
+ "[corewifi] [wifi-network-sharing] Already added network for clientID (clientID=%{public}@, knownNetwork=%{public}@)"
+ "assoc_retry_nan_rt_throttle_interval"
+ "connectivityAssist=no, "
+ "isConnectivityAssistEnabled"
+ "nan_rt_ended"
+ "remotedevicekitwifid"
- "hrmwifid"
```
