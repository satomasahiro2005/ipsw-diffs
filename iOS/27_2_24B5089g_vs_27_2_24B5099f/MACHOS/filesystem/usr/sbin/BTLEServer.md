## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f9e4` | `0x7fce4` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0xd8d6` | `0xd9c0` | **`+0xea`** |
| `__TEXT.__objc_stubs` | `0xcfc0` | `0xd020` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x133bc` | `0x1340d` | **`+0x51`** |
| `__DATA_CONST.__objc_intobj` | `0xa80` | `0xac8` | **`+0x48`** |
| `__DATA_CONST.__cfstring` | `0x4d00` | `0x4d40` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x4308` | `0x4320` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x7ec4` | `0x7ed4` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3694` | `0x369f` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x9b0` | `0x9b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2701.2.0.0.0
+2701.4.0.0.0

-  Functions: 3168
-  Symbols:   573
-  CStrings:  5265
+  Functions: 3169
+  Symbols:   574
+  CStrings:  5273
Symbols:
+ _OBJC_CLASS_$_UARPDeviceProperties
CStrings:
+ "Classic"
+ "LE"
+ "decOpportunisticConnection only supported for LE peripherals (%u)"
+ "decOpportunisticConnection refCount:%ld %@ (%@)"
+ "deviceInactivityTimeout for device %@"
+ "didUpdateNotificationStateForCharacteristic - peripheral:%@ characteristic:%@ error:%@ transport:%@"
+ "incOpportunisticConnection only supported for LE peripherals. Current peripheral is connected over %@ (%@)"
+ "incOpportunisticConnection refCount:%ld %@ (%@)"
+ "initWithUUID:delegate:delegateQueue:deviceProperties:"
+ "setNumPacketRetries:"
+ "setTimeoutActivity:"
+ "setTimeoutPacketRetry:"
- "decOpportunisticConnection refCount:%ld %@"
- "didUpdateNotificationStateForCharacteristic - peripheral:%@ characteristic:%@ error:%@"
- "incOpportunisticConnection refCount:%ld %@"
- "initWithUUID:delegate:delegateQueue:"
```
