## MultitouchHID

> `/System/Library/Extensions/AppleMultitouchSPI.kext/PlugIns/MultitouchHID.plugin/MultitouchHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x510a4` | `0x514fc` | **`+0x458`** |
| `__AUTH_CONST.__cfstring` | `0x5d40` | `0x5ee0` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x53b0` | `0x5456` | **`+0xa6`** |
| `__DATA_CONST.__const` | `0x780` | `0x7c0` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2a78` | `0x2a98` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x361a` | `0x3630` | **`+0x16`** |
| `__TEXT.__const` | `0x18f1` | `0x1901` | **`+0x10`** |

### Other Changes

```diff

-10100.40.2.0.0
+10100.44.0.0.0

-  Functions: 1598
-  Symbols:   2337
-  CStrings:  1290
+  Functions: 1601
+  Symbols:   2343
+  CStrings:  1306
Symbols:
+ _MGGetSInt32Answer
+ ____ZN18MultitouchHIDClass5probeEPK14__CFDictionaryjPi_block_invoke
+ ____ZN18MultitouchHIDClass5probeEPK14__CFDictionaryjPi_block_invoke_2
+ _analytics_send_event_lazy
+ _xpc_dictionary_create
+ _xpc_dictionary_set_int64
CStrings:
+ "AirPlay"
+ "Audio"
+ "BT-AACP"
+ "Blocked Transport: %@"
+ "BluetoothLowEnergy"
+ "DeviceClassNumber"
+ "FIFO"
+ "I2C"
+ "Inductive In-Band"
+ "SPI"
+ "SPU"
+ "Serial"
+ "Virtual"
+ "^v8@?0"
+ "com.apple.MultitouchSupport.TransportMatching"
+ "iAP"
```
