## apsd

> `/System/Library/PrivateFrameworks/ApplePushService.framework/apsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1175bc` | `0x1177f0` | **`+0x234`** |
| `__TEXT.__oslogstring` | `0x13fd5` | `0x14125` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0x8480` | `0x8560` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x880` | `0x938` | **`+0xb8`** |
| `__TEXT.__gcc_except_tab` | `0x2650` | `0x2680` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x9948` | `0x9970` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x10b80` | `0x10ba0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb808` | `0xb7f0` | **`-0x18`** |
| `__DATA.__objc_const` | `0x1c530` | `0x1c540` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x34a0` | `0x34b0` | **`+0x10`** |
| `__TEXT.__const` | `0xd973` | `0xd983` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x5660` | `0x5668` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1a68` | `0x1a70` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4208` | `0x4210` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xbac` | `0xbb0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1161.100.1.0.0
+1163.100.1.0.0

-  Functions: 6775
-  Symbols:   1193
-  CStrings:  8601
+  Functions: 6772
+  Symbols:   1194
+  CStrings:  8610
Symbols:
+ _nw_connection_copy_tcp_info_async
CStrings:
+ "%@ Schedule server update with change %@; isPowerEfficientToSendFilter %@"
+ "%@ tcp_info[%{public}@]: srtt=%ums rtt=%ums rttvar=%ums bw=%llubps cwnd=%u snd_wnd=%u rto=%ums unacked=%u tx=%llu rx=%llu retx=%llu"
+ "%@ tcp_info[%{public}@]: state=%u opts=%x snd_wscale=%u rcv_wscale=%u flags=%x rto=%u snd_mss=%u rcv_mss=%u rttcur=%u srtt=%u rttvar=%u ssthresh=%u cwnd=%u rcv_space=%u snd_wnd=%u snd_nxt=%u rcv_nxt=%u outif=%d sbbytes=%u tx=%llu retx=%llu unacked=%llu rx=%llu rxdup=%llu bw=%llu"
+ "<%@; connectedFor: %.1fs; isConnected: %@; serverIPAddress: %@; serverHostname: %@; linkQuality: %d; srtt: %@ms>"
+ "ContainerID"
+ "ZoneID"
+ "_lastTCPInfoLogTimeMach"
+ "_logTCPInfoAsync"
+ "_scheduleServerUpdateForChange:"
+ "cid"
+ "ck"
+ "com.apple.icloud-container."
+ "logTCPInfoIfNeeded"
+ "met"
+ "n/a"
+ "smoothedRTTMilliseconds"
+ "smoothedRTTMillisecondsForInterface:"
+ "zid"
- " %u %x %u %u %x %u %u %u %u %u %u %u %u %u %u %u %u %d %u %llu %llu %llu %llu %llu %llu"
- "%@ Schedule server update with change %@; withTimer %@; shortInterval %@; isPowerEfficientToSendFilter %@"
- "<%@; connectedFor: %.1fs; isConnected: %@; serverIPAddress: %@; serverHostname: %@; linkQuality: %d>"
- "Failed to get tcp info data"
- "_scheduleServerUpdateWithChange:timer:"
- "_scheduleServerUpdateWithChange:timer:shortInterval:"
- "tcpInfoDescription"
- "tcpInfoDescriptionForInterface:"
- "tcp_info: %@"
```
