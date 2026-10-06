## com.apple.iokit.IOTimeSyncFamily

> `com.apple.iokit.IOTimeSyncFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x32a78` | `0x31b44` | **`-0xf34`** |
| `__TEXT.__os_log` | `0x8f3a` | `0x8c04` | **`-0x336`** |
| `__TEXT.__cstring` | `0x4004` | `0x3eb8` | **`-0x14c`** |
| `__DATA_CONST.__kalloc_type` | `0xe00` | `0xd40` | **`-0xc0`** |
| `__DATA_CONST.__const` | `0xc550` | `0xc510` | **`-0x40`** |

### Other Changes

```diff

-1510.7.0.0.0
-  Functions: 1492
+1510.8.0.0.0
+  Functions: 1474

-  CStrings:  749
+  CStrings:  728
CStrings:
+ "121111121222121212112221211222221211112111121111222222211111112122222222222"
+ "getTransmitTimestamp(packet, &timestamp) == kIOReturnSuccess"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/TimeSync_kext/IOTimeSyncFamily/TimeSensitiveNetworking/TSNBSDTestInterface.cpp"
- "1211111212221212121122212112222212111121111211112222222111111121222222222221"
- "12222"
- "2222222222222222221"
- "Dropping %llu packets from sequence diff (%llu -> %llu)"
- "First t1 timestamp = %llu"
- "First t2 timestamp = %llu"
- "Maximum timestamp, resetting replay"
- "Starting timestamp replay"
- "Stopped timestamp replay"
- "Stopping timestamp replay"
- "Unexpected sync received on GM"
- "[%u] delay request Replayed t3 = %llu -> %llu"
- "[%u] delay request Replayed t4 = %llu -> %llu"
- "[%u] delay response Replayed t4 = %llu -> %llu"
- "[%u] follow up Replayed t1, %llu -> %llu"
- "[%u] sync Replayed t1, %llu -> %llu"
- "[%u] sync Replayed t2, %llu -> %llu"
- "getTransmitTimestamp(packet, &timestamp, &futurePermitted) == kIOReturnSuccess"
- "length == packetLength"
- "payload != nullptr"
- "site.TSNBSDTestInterfaceReplayTimestamps"
- "site.TSReplayTimestamps"
```
