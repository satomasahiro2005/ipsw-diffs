## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb67ec` | `0xb6550` | **`-0x29c`** |
| `__TEXT.__cstring` | `0x30a15` | `0x3095b` | **`-0xba`** |
| `__DATA_DIRTY.__data` | `0xcb0` | `0xc40` | **`-0x70`** |
| `__AUTH_CONST.__const` | `0x2dd8` | `0x2d78` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x2498` | `0x24f8` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x6600` | `0x6640` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b98` | `0x1bd8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1cec` | `0x1d2c` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2d60` | `0x2d30` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x3e08` | `0x3e28` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x2c8` | `0x2b8` | **`-0x10`** |
| `__TEXT.__const` | `0x664` | `0x674` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xa1c` | `0xa10` | **`-0xc`** |
| `__DATA_CONST.__objc_catlist` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-980.77.1.2.0
+1005.7.1.0.0

-  Functions: 5367
-  Symbols:   4406
-  CStrings:  4572
+  Functions: 5349
+  Symbols:   4412
+  CStrings:  4565
Symbols:
+ -[WiFiAwareDatapathInfo(APTNANDataSession) peerSignalStrength]
+ GCC_except_table29
+ GCC_except_table8
+ _APSSignalStrengthDBmFromScaled
+ _APTDiagnosticSendStreamInfo
+ _APTNANDataSessionGetDatapathRSSI
+ _APTransportConnectionCopyProperty
+ _APTransportConnectionGetDSCPForSocketQoS
+ _APTransportConnectionQoSFromSocketQoS
+ _APTransportSocketQoSFromConnectionQoS
+ _APTransportTrafficCapturePrepareForCollection
+ _APTransportTrafficCaptureWriteUDPMessage
+ _CFURLCreateFromFileSystemRepresentation
+ _FigFileMarkPurgeable
+ __APTNANDataSessionCopyDatapathIDAndPeerMAC
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_WiFiAwareDatapathInfo_$_APTNANDataSession
+ __OBJC_$_CATEGORY_WiFiAwareDatapathInfo_$_APTNANDataSession
+ ___62-[WiFiAwareDatapathInfo(APTNANDataSession) peerSignalStrength]_block_invoke
+ ___APTransportTrafficCapturePrepareForCollection_block_invoke
+ ___APTransportTrafficCaptureWriteUDPMessage_block_invoke
+ ___block_descriptor_48_e8_32o40o_e44_v16?0"WiFiAwareDatapathPerformanceReport"8ls32l8s40l8
+ _nw_content_context_set_metadata_for_protocol
+ _nw_ip_create_metadata
+ _nw_ip_metadata_set_dscp_value
+ _unbufnwGuts_setQualityOfServiceInternal
- GCC_except_table36
- _APTDiagnosticMulticastDataToAllHosts
- _APTPacingControllerReset
- _APTransportTrafficCaptureFlushForSysdiagnose
- _APTransportTrafficCaptureWriteMulticastMessage
- _APTransportWifiManagerClientCreate
- _APTransportWifiManagerClientRegister
- _APTransportWifiManagerClientUnregister
- _CMBaseObjectCopyProperty
- ___APTransportTrafficCaptureFlushForSysdiagnose_block_invoke
- ___APTransportTrafficCaptureWriteMulticastMessage_block_invoke
- ___APTransportWifiManagerClientRegister_block_invoke
- ___APTransportWifiManagerClientUnregister_block_invoke
- _gLogCategory_APTransportWifiManagerClient
- _kAPTransportProperty_WifiManagerClient
- _kAPTransportWifiManagerClientClass
- _session_performWifiManagerRegistration
- _wifiManagerClient_Finalize
- _wifiManagerClient_getTypeID
CStrings:
+ "%@/airplaysnoop_*.atslite"
+ "1005.7.1"
+ "APTNANDataSessionGetDatapathRSSI"
+ "APTransportTrafficCapturePrepareForCollection"
+ "APTransportTrafficCaptureWriteUDPMessage"
+ "APTransportTrafficCaptureWriteUDPMessage_block_invoke"
+ "OSStatus APTransportTrafficCapturePrepareForCollection(APTransportTrafficCaptureRef, CFAllocatorRef, CFStringRef *)_block_invoke"
+ "OSStatus APTransportTrafficCaptureWriteUDPMessage(APTransportTrafficCaptureRef, sockaddr_ip *, sockaddr_ip *, CFDataRef, APTransportTrafficCaptureMessageDirection)_block_invoke"
+ "[%{ptr}] APTransportKeepAliveControllerStandard created for stream [%{ptr}] with queue QoS class %u\n"
+ "[%{ptr}] Capturing UDP message (len: %lu, direction: %d)"
+ "[%{ptr}] PrepareForCollection fflush failed (continuing): %s (errno: %d, %s)\n"
+ "[%{ptr}] PrepareForCollection flushed: %s\n"
+ "[%{ptr}] PrepareForCollection fsync failed (continuing): %s (errno: %d, %s)\n"
+ "[%{ptr}] PrepareForCollection: no active capture file, nothing to flush\n"
+ "[%{ptr}] Renamed capture file to: %s, %s%?{end}: %#m\n"
+ "[%{ptr}] addBytesSent nowNs=%llu epochNs=%llu bytesSent=%llu burstStartNs=%llu burstBytesSent=%llu"
+ "[%{ptr}] begYield nowNs=%llu epochNs=%llu bytesSent=%llu burstStartNs=%llu burstBytesSent=%llu"
+ "[%{ptr}] created leewayNs=%llu minYieldNs=%llu maxBehindNs=%llu"
+ "[%{ptr}] re-anchor behindNs=%llu"
+ "[%{ptr}] socketQoS=%u (trafficClass=%u, dscp=%u)"
+ "_APTNANDataSessionCopyDatapathIDAndPeerMAC"
+ "_APTNANDataSessionCreateDatapathInfo"
+ "could not mark purgeable"
+ "marked purgeable"
+ "pacingController_maxBehindUs"
+ "unbufnwQoS"
+ "v16@?0@\"WiFiAwareDatapathPerformanceReport\"8"
+ "void unbufnwGuts_setQualityOfServiceInternal(APTransportConnectionUnbufferedNWGutsRef, int)"
- "980.77.1.2"
- "APTPacingControllerReset"
- "APTransportTrafficCaptureWriteMulticastMessage"
- "APTransportTrafficCaptureWriteMulticastMessage_block_invoke"
- "APTransportWifiManagerClient"
- "APTransportWifiManagerClient %{ptr} created\n"
- "APTransportWifiManagerClient %{ptr} finalizing\n"
- "APTransportWifiManagerClient.queue"
- "APTransportWifiManagerClientCreate"
- "Created CWFInterface [%{ptr}]\n"
- "Destroying CWFInterface [%{ptr}]\n"
- "OSStatus APTPacingControllerReset(APTPacingControllerRef)"
- "OSStatus APTransportTrafficCaptureFlushForSysdiagnose(APTransportTrafficCaptureRef)_block_invoke"
- "OSStatus APTransportTrafficCaptureWriteMulticastMessage(APTransportTrafficCaptureRef, sockaddr_ip *, sockaddr_ip *, CFDataRef, APTransportTrafficCaptureMessageDirection)_block_invoke"
- "OSStatus APTransportWifiManagerClientCreate(CFAllocatorRef, APTransportWifiManagerClientRef *)"
- "OSStatus wifiManagerClient_registerInternal(APTransportWifiManagerClientRef)"
- "OSStatus wifiManagerClient_unregisterInternal(APTransportWifiManagerClientRef)"
- "WifiManagerClient"
- "[%{ptr}] APTransportKeepAliveControllerStandard created for stream [%{ptr}]\n"
- "[%{ptr}] Capturing multicast message (len: %lu, direction: %d)"
- "[%{ptr}] FlushForSysdiagnose completed: %s\n"
- "[%{ptr}] FlushForSysdiagnose fflush failed: %s (errno: %d, %s)\n"
- "[%{ptr}] FlushForSysdiagnose fsync failed: %s (errno: %d, %s)\n"
- "[%{ptr}] FlushForSysdiagnose: no active capture file, nothing to flush\n"
- "[%{ptr}] Register: RegistrationCount = %d\n"
- "[%{ptr}] Renamed capture file to: %s\n"
- "[%{ptr}] Unregister: RegistrationCount = %d\n"
- "[%{ptr}] addBytesSent nowNs=%llu epochNs=%llu bytesSent=%llu"
- "[%{ptr}] begYield nowNs=%llu epochNs=%llu bytesSent=%llu"
- "[%{ptr}] created"
- "[%{ptr}] reset"
- "[%{ptr}] socketQoS=%u (trafficClass=%u)"
- "session_performWifiManagerRegistration"
- "void wifiManagerClient_Finalize(CFTypeRef)"
- "wifiManagerClient_registerInternal"
```
