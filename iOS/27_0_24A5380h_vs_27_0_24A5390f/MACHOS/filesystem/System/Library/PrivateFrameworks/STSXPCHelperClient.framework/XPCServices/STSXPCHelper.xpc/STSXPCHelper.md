## STSXPCHelper

> `/System/Library/PrivateFrameworks/STSXPCHelperClient.framework/XPCServices/STSXPCHelper.xpc/STSXPCHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39d88` | `0x3a334` | **`+0x5ac`** |
| `__TEXT.__cstring` | `0x9207` | `0x95a4` | **`+0x39d`** |
| `__TEXT.__ustring` | `—` | `0x268` | **`+0x268`** |
| `__DATA_CONST.__cfstring` | `0x5b20` | `0x5d00` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0xb14` | `0xb4e` | **`+0x3a`** |
| `__TEXT.__auth_stubs` | `0xae0` | `0xb00` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4660` | `0x4680` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x590` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x625a` | `0x6263` | **`+0x9`** |
| `__DATA.__objc_selrefs` | `0x17d8` | `0x17e0` | **`+0x8`** |
| `__TEXT.__const` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xae8` | `0xaf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-6.0.11.0.0
+6.0.13.0.0

-  Symbols:   289
-  CStrings:  2505
+  Symbols:   291
+  CStrings:  2530
Symbols:
+ _clock_gettime_nsec_np
+ _dispatch_queue_get_label
Functions:
~ sub_100003700 -> sub_100003750 : 484 -> 524
~ sub_100017d4c -> sub_100017dc4 : 544 -> 1116
~ sub_1000181b8 -> sub_10001846c : 500 -> 692
~ sub_1000183ac -> sub_100018720 : 120 -> 144
~ sub_1000184d4 -> sub_100018860 : 272 -> 228
~ sub_100032d6c -> sub_1000330cc : 108 -> 364
~ sub_100034a2c -> sub_100034e8c : 828 -> 848
~ sub_100034d68 -> sub_1000351dc : 480 -> 772
~ sub_100034f58 -> sub_1000354f0 : 104 -> 204
CStrings:
+ " created DCPresentmentRequest: %@ "
+ "(no label)"
+ "-[ISO18013_3_Central peripheralIsReadyToSendWriteWithoutResponse:]"
+ "-[ISO18013_3_Central writeData:toUUID:]_block_invoke_3"
+ "-[STSISO18013Handler _interpretPresentmentRequest:callback:]"
+ "BT_SendData_BoundaryRace"
+ "Invalidated"
+ "LE: BLESender invalidate, pendingBytes=%lu"
+ "LE: Done TX (frags=%lu bytes=%lu)"
+ "LE: TX frag #%lu size=%lu mtu=%u lastPkt=%d"
+ "LE: anomaly — frag #%lu size=%lu mtu=%u (expected full chunk on non-last)"
+ "LE: canSendWriteWithoutResponse=NO; deferring"
+ "LE: closure invoked, fragSize=%lu canSendWWR=%d"
+ "LE: maximumWriteValueLengthForType=%lu (clamped uint16=%u, cap=%u)"
+ "LE: maximumWriteValueLengthForType=%u exceeds cap; clamping to %u"
+ "LE: parking at frag #%lu (dataIndex=%lu remaining=%lu)"
+ "LE: peripheralReady MISMATCH expected=%@ — dropping spurious ready notification"
+ "LE: peripheralReady peripheral=%@ match=%d senderPresent=%d cbQueue=%s"
+ "LE: spaceIsAvailable invalidated=%d pendingBytes=%lu"
+ "LE: writeData %s"
+ "LE: writeData boundary race — signal observed only on non-blocking poll after %.3fs"
+ "LE: writeData timed out after %.1fs; pendingBytes=%lu — failing write"
+ "LE: writeData unblocked after %.3fs (gotSignal=%d, raceRecovered=%d)"
+ "LE: writeData uuid=%@ peripheralID=%@ delegateIsSelf=%d canSendWWR=%d isConnected=%d hasL2CAP=%d state=%ld dataLen=%lu queue=%s"
+ "LE: writing %lu bytes (mtu=%u)"
+ "completed"
+ "delegate"
+ "elapsed=%.3f"
+ "unblocked by invalidate (failure)"
- "Data unavailable"
- "LE: Read MTU=%d is too large; override to MAX_ATTRIBUTE_SIZE"
- "LE: writing %lu bytes"
- "Session invalidated"
```
