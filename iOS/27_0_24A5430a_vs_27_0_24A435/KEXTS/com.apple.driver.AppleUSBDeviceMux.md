## com.apple.driver.AppleUSBDeviceMux

> `com.apple.driver.AppleUSBDeviceMux`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x58f8` | `0x5a08` | **`+0x110`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _panic : 128 -> 132
~ __ZN17AppleUSBDeviceMux9bmsRetainEP17BulkUSBMuxSessionPKc : 84 -> 88
~ __ZN17AppleUSBDeviceMux10bmsReleaseEP17BulkUSBMuxSessionPKc : 84 -> 88
~ sub_fffffff009a58778 -> sub_fffffff009ae31f4 : 72 -> 76
~ sub_fffffff009a587c8 -> sub_fffffff009ae3248 : 68 -> 72
~ sub_fffffff009a5880c -> sub_fffffff009ae3290 : 68 -> 72
~ sub_fffffff009a58860 -> sub_fffffff009ae32e8 : 68 -> 72
~ sub_fffffff009a588cc -> sub_fffffff009ae3358 : 72 -> 76
~ sub_fffffff009a58914 -> sub_fffffff009ae33a4 : 120 -> 124
~ sub_fffffff009a589a0 -> sub_fffffff009ae3434 : 104 -> 108
~ sub_fffffff009a58a08 -> sub_fffffff009ae34a0 : 104 -> 108
~ __ZN17AppleUSBDeviceMux5startEP9IOService : 984 -> 988
~ __ZN17AppleUSBDeviceMux17asyncReadCompleteEP6__mbufij : 1024 -> 1028
~ __ZN17AppleUSBDeviceMux18asyncWriteCompleteEP14USBWriteBufferij : 1108 -> 1112
~ __ZN17AppleUSBDeviceMux22asyncMbufWriteCompleteEP6__mbufij : 604 -> 608
~ __ZN17AppleUSBDeviceMux13sessionUpcallEP19IOSocketEventSourceP8__socketP17BulkUSBMuxSession : 460 -> 464
~ __ZN17AppleUSBDeviceMux12startUSBReadEv : 644 -> 648
~ __ZN17AppleUSBDeviceMux14resyncWithHostEv : 456 -> 460
~ __ZN17AppleUSBDeviceMux23allocateUSBWriteBuffersEv : 280 -> 284
~ sub_fffffff009a5a028 -> sub_fffffff009ae4ae4 : 208 -> 212
~ __ZN17AppleUSBDeviceMux22allocateUSBReadBuffersEv : 204 -> 208
~ _IOLog : 136 -> 140
~ sub_fffffff009a5a298 -> sub_fffffff009ae4d60 : 352 -> 356
~ sub_fffffff009a5a3f8 -> sub_fffffff009ae4ec4 : 332 -> 336
~ sub_fffffff009a5a544 -> sub_fffffff009ae5014 : 288 -> 292
~ sub_fffffff009a5a664 -> sub_fffffff009ae5138 : 64 -> 68
~ __ZN17AppleUSBDeviceMux18setPropertiesGatedEP8OSObject : 236 -> 240
~ __ZN17AppleUSBDeviceMux7messageEjP9IOServicePv : 892 -> 896
~ sub_fffffff009a5ab60 -> sub_fffffff009ae5640 : 164 -> 168
~ __ZN17AppleUSBDeviceMux11reportStatsEb : 184 -> 188
~ __ZN17AppleUSBDeviceMux14freeBufferListEP14USBWriteBuffer : 260 -> 264
~ __ZN17AppleUSBDeviceMux14sendMuxSegmentEP17BulkUSBMuxSession : 964 -> 968
~ __ZN17AppleUSBDeviceMux19handleConnectResultEP17BulkUSBMuxSessioni : 660 -> 664
~ sub_fffffff009a5b47c -> sub_fffffff009ae5f70 : 44 -> 48
~ sub_fffffff009a5b4a8 -> sub_fffffff009ae5fa0 : 92 -> 96
~ __ZN17AppleUSBDeviceMux14writeMbufToUSBEP6__mbufj : 652 -> 656
~ __ZN17AppleUSBDeviceMux10newSessionEP6tcphdr : 960 -> 964
~ sub_fffffff009a5bb50 -> sub_fffffff009ae6654 : 44 -> 48
~ __ZN17AppleUSBDeviceMux17handleMuxTCPInputEP6__mbuf : 1608 -> 1612
~ __ZN17AppleUSBDeviceMux26handleMuxHostLogLevelInputEP6__mbuf : 188 -> 192
~ __ZN17AppleUSBDeviceMux21handleMuxVersionInputEP6__mbuf : 384 -> 388
~ __ZN17AppleUSBDeviceMux14writeMbufToUSBEP6__mbuf : 316 -> 320
~ __ZN17AppleUSBDeviceMux14handleMuxInputEP6__mbuf : 1908 -> 1912
~ __ZN17AppleUSBDeviceMux11dumpUSBLogsEv : 308 -> 312
~ sub_fffffff009a5cdf0 -> sub_fffffff009ae7910 : 180 -> 184
~ sub_fffffff009a5ceac -> sub_fffffff009ae79d0 : 72 -> 76
~ __ZN17AppleUSBDeviceMux14writeToUSBPipeEP14USBWriteBuffer : 576 -> 580
~ __ZN17AppleUSBDeviceMux13startUSBWriteEP14USBWriteBufferjb : 360 -> 364
~ sub_fffffff009a5d29c -> sub_fffffff009ae7dcc : 360 -> 364
~ __ZN17AppleUSBDeviceMux11vsendMuxRSTEP6tcphdrbPKcPc : 440 -> 444
~ __ZN17AppleUSBDeviceMux14socketIsClosedEP8__socket : 196 -> 200
~ sub_fffffff009a5d83c -> sub_fffffff009ae8378 : 80 -> 84
~ sub_fffffff009a5d8bc -> sub_fffffff009ae83fc : 72 -> 76
~ sub_fffffff009a5d90c -> sub_fffffff009ae8450 : 52 -> 56
~ sub_fffffff009a5d940 -> sub_fffffff009ae8488 : 52 -> 56
~ sub_fffffff009a5d984 -> sub_fffffff009ae84d0 : 68 -> 72
~ sub_fffffff009a5d9f0 -> sub_fffffff009ae8540 : 72 -> 76
~ sub_fffffff009a5da38 -> sub_fffffff009ae858c : 104 -> 108
~ sub_fffffff009a5dab4 -> sub_fffffff009ae860c : 88 -> 92
~ sub_fffffff009a5db0c -> sub_fffffff009ae8668 : 88 -> 92
~ sub_fffffff009a5db64 -> sub_fffffff009ae86c4 : 196 -> 200
~ sub_fffffff009a5dc34 -> sub_fffffff009ae8798 : 224 -> 228
~ sub_fffffff009a5dd14 -> sub_fffffff009ae887c : 116 -> 120
~ sub_fffffff009a5dd88 -> sub_fffffff009ae88f4 : 76 -> 80
~ sub_fffffff009a5dddc -> sub_fffffff009ae894c : 80 -> 84
~ __ZN17AppleUSBDeviceMux10bmsReleaseEP17BulkUSBMuxSessionPKc.cold.1 : 40 -> 44
~ __ZN17AppleUSBDeviceMux9bmsRetainEP17BulkUSBMuxSessionPKc.cold.1 : 40 -> 44
~ __ZN17AppleUSBDeviceMux14freeBufferListEP14USBWriteBuffer.cold.1 : 56 -> 60
CStrings:
+ "21:31:46"
- "22:16:38"
```
