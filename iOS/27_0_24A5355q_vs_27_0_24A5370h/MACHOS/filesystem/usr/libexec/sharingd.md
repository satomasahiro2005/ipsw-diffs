## sharingd

> `/usr/libexec/sharingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x691814` | `0x6950a4` | **`+0x3890`** |
| `__TEXT.__unwind_info` | `0x139e0` | `0x14268` | **`+0x888`** |
| `__TEXT.__oslogstring` | `0x3c3d3` | `0x3c963` | **`+0x590`** |
| `__TEXT.__cstring` | `0x3e661` | `0x3eb61` | **`+0x500`** |
| `__TEXT.__objc_methname` | `0x4e395` | `0x4e735` | **`+0x3a0`** |
| `__DATA.__objc_const` | `0x37f50` | `0x38200` | **`+0x2b0`** |
| `__TEXT.__objc_stubs` | `0x37160` | `0x373c0` | **`+0x260`** |
| `__TEXT.__objc_methlist` | `0x1e304` | `0x1e4a4` | **`+0x1a0`** |
| `__DATA.__bss` | `0x15850` | `0x15960` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `0x19560` | `0x19660` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x1c970` | `0x1ca40` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x10f80` | `0x11020` | **`+0xa0`** |
| `__TEXT.__const` | `0x159f8` | `0x15a88` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x23ffc` | `0x2406c` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x5130` | `0x5188` | **`+0x58`** |
| `__DATA.__objc_data` | `0xa048` | `0xa098` | **`+0x50`** |
| `__DATA.__data` | `0x14880` | `0x148c8` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x5dfc` | `0x5e30` | **`+0x34`** |
| `__DATA.__objc_ivar` | `0x28d0` | `0x2900` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xa930` | `0xa960` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x58e9` | `0x5919` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x7828` | `0x784c` | **`+0x24`** |
| `__TEXT.__gcc_except_tab` | `0x67d8` | `0x67f8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xbc03` | `0xbc22` | **`+0x1f`** |
| `__DATA_CONST.__auth_got` | `0x54a8` | `0x54c0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x22b0` | `0x229c` | **`-0x14`** |
| `__TEXT.__objc_classname` | `0x5ad5` | `0x5ae7` | **`+0x12`** |
| `__TEXT.__swift5_typeref` | `0x7f76` | `0x7f84` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x38e8` | `0x38e0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe00` | `0xe08` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x6e8` | `0x6f0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xca0` | `0xca8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xe10` | `0xe18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5e0` | `0x5e4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xef4` | `0xef8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-2118.10.4.2.3
+2122.10.2.2.1

-  Functions: 26174
-  Symbols:   4883
-  CStrings:  27384
+  Functions: 26227
+  Symbols:   4885
+  CStrings:  27467
Symbols:
+ _$s7Sharing21SFAirDropUserDefaultsC28readNearbyInfoBuffersEnabledSbvg
+ _$ss15ContinuousClockV7InstantV8duration2tos8DurationVAD_tF
+ _$ss8DurationV10componentss5Int64V7seconds_AE11attosecondstvg
- _$s7Sharing17SFNWInterfaceTypeOs23CustomStringConvertibleAAMc
CStrings:
+ "### Activate failed: %@\n"
+ "### CBDiscovery class unavailable\n"
+ "### Start NearbyInfo buffer failed: %@\n"
+ "-[SDBLENearbyInfoBuffer _activateWithCompletion:]"
+ "-[SDBLENearbyInfoBuffer _activateWithCompletion:]_block_invoke_2"
+ "-[SDBLENearbyInfoBuffer _handleBufferedDevices:]"
+ "-[SDBLENearbyInfoBuffer _invalidate]"
+ "-[SDBLENearbyInfoBuffer readBuffers]_block_invoke"
+ "-[SDNearbyAgent _bleNearbyInfoBufferDeviceFound:]"
+ "-[SDNearbyAgent _bleNearbyInfoBufferEnsureStarted]"
+ "-[SDNearbyAgent _bleNearbyInfoBufferEnsureStarted]_block_invoke_2"
+ "-[SDNearbyAgent _bleNearbyInfoBufferEnsureStopped]"
+ "-[SDNearbyAgent _purgeNearbyInfoBufferedDevices]"
+ "-[SDNearbyAgent readNearbyInfoBuffers]_block_invoke"
+ "26.6"
+ "@\"SDBLENearbyInfoBuffer\""
+ "Activated\n"
+ "AirDropReadNearbyInfoBuffers"
+ "BLE NearbyInfo buffer start\n"
+ "BLE NearbyInfo buffer stop\n"
+ "BLE NearbyInfo buffered %@\n"
+ "CBDiscovery still active during dealloc"
+ "Created bound stream pair, adapterBufferSize=%ld"
+ "Device Unlocked. Notifying pencil pairing server"
+ "Dispatch queue must be set before activate"
+ "Ignoring proximity TVColorCalibration (disabled) for %@\n"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Peer device on older OS version (%{public}@), not using session ranging key for attested protocol"
+ "Purging buffered NearbyInfo device %@\n"
+ "Ranging key exists %@, shouldUseSessionKey: %@"
+ "ReadNearbyInfoBuffers\n"
+ "Received %ld total bytes in %ld chunks, awaiting decompression"
+ "SDAirDropSendCompressionAdapter: init streamBufferSize=%ld, archiveType=%s"
+ "SDBLENearbyInfoBuffer"
+ "T@\"NSArray\",C,N,V_observerIdentifiers"
+ "T@?,C,N,V_deviceFoundHandler"
+ "TVColorCalibration enabled: %s -> %s\n"
+ "_activateWithCompletion:"
+ "_bleNearbyInfoBuffer"
+ "_bleNearbyInfoBufferDeviceFound:"
+ "_bleNearbyInfoBufferEnsureStarted"
+ "_bleNearbyInfoBufferEnsureStopped"
+ "_bleNearbyInfoBufferShouldRun"
+ "_bleNearbyInfoBufferedDevices"
+ "_bleNearbyInfoBufferedDevicesPurgeBlock"
+ "_buildBLEDeviceFromCBDevice:"
+ "_cbDiscovery"
+ "_deviceFoundHandler"
+ "_ensureNearbyInfoBufferedDevicesPurgeTimerStarted"
+ "_handleBufferedDevices:"
+ "_observerIdentifiers"
+ "_parseNearbyInfoFromManufacturerData:fields:"
+ "_purgeNearbyInfoBufferedDevices"
+ "_tvColorCalibrationEnabled"
+ "buffered"
+ "com.apple.private.tcc.allow"
+ "com.apple.security.personal-information.addressbook"
+ "com.apple.sharingd.contactHashesUpdated"
+ "decompress: partial write, retrying remaining %ld bytes"
+ "decompress: writing %ld bytes to pipe, totalReceivedBytes=%ld"
+ "decompress: wrote %ld of %ld bytes to pipe"
+ "deviceDidUnlock"
+ "kDarwinContactHashesUpdated"
+ "kTCCServiceAddressBook"
+ "mfrD"
+ "nearbyAuthTag"
+ "observerIdentifiers"
+ "parseNearbyInfoPtr:end:fields:"
+ "readBuffers"
+ "readBuffers\n"
+ "readNearbyInfoBuffers"
+ "receiveFileData: decompress returned for chunk #%ld"
+ "receiveFileData: received chunk #%ld, size=%ld, totalData=%ld"
+ "receiveFileData: waiting for network chunk #%ld"
+ "receiveUploadData: calling nw_connection_receive with streamSize=%ld"
+ "receiveUploadData: received %ld bytes, isComplete=%{bool}d"
+ "saTVCCS"
+ "sd_connectionHasContactsEntitlement"
+ "sendAdapter: delegate send completed for read #%ld, sendTimeMs=%.*f"
+ "sendAdapter: read #%ld, readSize=%ld, totalBytesRead=%ld, readTimeMs=%.*f"
+ "sendAdapter: read loop finished, totalBytesRead=%ld, iterations=%ld"
+ "sendAdapter: starting read loop, maxReadSize=%ld"
+ "sendConnection: upload call returned, isComplete=%{bool}d"
+ "sendConnection: uploading %ld bytes, streamSize=%ld, isComplete=%{bool}d"
+ "sendHTTPMessage: nw_connection_send completed, %ld bytes"
+ "sendHTTPMessage: sending %ld bytes, isComplete=%{bool}d"
+ "sendStreamedHTTPMessage: body=%ld bytes, streamSize=%ld, isComplete=%{bool}d"
+ "sendStreamedHTTPMessage: chunk #%ld, size=%ld, isLast=%{bool}d"
+ "setBuffered:"
+ "setObserverIdentifiers:"
+ "v32@0:8@\"NSURL\"16@?<v@?BBB>24"
+ "waitForStreamSpace: output stream closed"
+ "waitForStreamSpace: pipe full, spinning until zipper drains"
+ "waitForStreamSpace: stream closed while waiting"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "Output stream closed"
- "Ranging key exists %@"
- "Reading compressed data %ld"
- "Received %ld total bytes, awaiting decompression"
- "Sending %ld bytes"
- "Sending compressed data %s on interface %s"
- "Streamed %ld bytes"
- "Wrote %ld bytes of %ld to output stream"
- "Wrote remaining %s to output stream"
- "v32@0:8@\"NSURL\"16@?<v@?BB>24"
```
