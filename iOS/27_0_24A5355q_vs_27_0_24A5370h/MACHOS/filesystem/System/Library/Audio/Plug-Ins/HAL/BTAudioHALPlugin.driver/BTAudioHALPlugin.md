## BTAudioHALPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BTAudioHALPlugin.driver/BTAudioHALPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x16f80` | `0x21050` | **`+0xa0d0`** |
| `__TEXT.__text` | `0x76df4` | `0x7ccd4` | **`+0x5ee0`** |
| `__TEXT.__oslogstring` | `0x15687` | `0x16233` | **`+0xbac`** |
| `__DATA_CONST.__const` | `0x4bd8` | `0x5318` | **`+0x740`** |
| `__TEXT.__const` | `0x18bc` | `0x1aac` | **`+0x1f0`** |
| `__TEXT.__cstring` | `0x4dea` | `0x4f78` | **`+0x18e`** |
| `__TEXT.__gcc_except_tab` | `0x1f0c` | `0x2064` | **`+0x158`** |
| `__TEXT.__unwind_info` | `0x1bb0` | `0x1cd8` | **`+0x128`** |
| `__TEXT.__objc_methname` | `0x3f5f` | `0x3ecc` | **`-0x93`** |
| `__DATA.__objc_const` | `0x1f78` | `0x1f20` | **`-0x58`** |
| `__TEXT.__objc_methlist` | `0x11cc` | `0x118c` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x27e0` | `0x2800` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xe50` | `0xe40` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x184` | `0x17c` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0xa0` | `0xa4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

-  Functions: 2749
+  Functions: 2861

-  CStrings:  2925
+  CStrings:  2976
Symbols:
+ _dispatch_assert_queue$V2
+ _dispatch_sync
+ _objc_release_x23
+ _objc_release_x24
- _objc_copyWeak
- _objc_destroyWeak
- _objc_initWeak
- _objc_loadWeak
CStrings:
+ " SetProperty kBluetoothAudioDevicePropertySoftwareVolumeOnPublish %{public}s "
+ "#Error BTAudioXpcConnection::SendSoftwareVolumeOnPublish null args"
+ "#Error BTAudioXpcConnection::SendSoftwareVolumeOnPublish null values[0]"
+ "3p head tracking support set to %d for mAudioObjectID %d"
+ "AudioAccessoryMsgIdHeadTrackingStateChanged"
+ "AudioAccessoryd hasn't registered a connection, can't send head tracking state"
+ "BTAudioAVNotificationMonitor: shutdown already completed, ignoring duplicate call"
+ "Delayed Transport Disconnect: Disconnect Timer Fired..Disconnect CIS"
+ "Device sample rate changed %f -> %f [encoder = %d, decoder = %d]"
+ "High quality FarfieldMic Update to %s"
+ "Input Decode: Bytes read is 0 bytesRead %lu"
+ "LC3"
+ "LECA Delayed Transport Disconnect: Cancelling current Dispatch"
+ "LECA Delayed Transport Disconnect: cisConnected = %d. Transport = %d"
+ "LECA Device XPC connection for UID %s connected to[ %d ] "
+ "LECA GetLatency: mLinkLatency=%u mPluginLatency=%u sampleRate=%.0f latency=%u"
+ "LECA StartIO Audio start condition timed out waiting for signal"
+ "LECA StartIO BTAudioPlugin start condition timed out"
+ "LECA StartIO CIS Already up"
+ "LECA StartIO Device had a transport error, StartIO return immediately"
+ "LECA StartIO Waiting for Start Condition"
+ "LECA StartIO on profile %{public}s, activeIO:%llu to %{public}@ mAudioObjectID: %u Wait IO Start %d"
+ "LECA StartIO returns %x (%llu)"
+ "LECA StartIO: CIS connected, shared memory allocated"
+ "LECA StartIO: failed to allocate shared memory"
+ "LECA StartIO: failed to start because the ref count was maxed out"
+ "LECA Status: IO = %{public}s. CIS Up = %{public}s. Delayed Transport Disconnect: %{public}s"
+ "LECA StopIO %{public}s, activeIO:%llu, need immediate CIS disconnect:%d"
+ "LECA StopIO returns noErr (%llu)"
+ "LECA StopIO: failed to stop because the ref count was already 0"
+ "LECA StopIO: mNeedImmediateCISDisconnect not set, using delayed transport disconnect"
+ "LECA StopIO: mNeedImmediateCISDisconnect set, performing immediate CIS disconnect"
+ "LECA Update content type via config change, new content type =%d"
+ "LECA setImmediateCISDisconnect: delayed transport disconnect cancelled=%d"
+ "LECA setImmediateCISDisconnect: disconnect=%d, activeIO=%llu"
+ "LECA: Codec Update completed Input = %{public}s Decoder = %d , Output = %{public}s Encoder = %d"
+ "LECA: Direction %x Stream state output = %d input = %d"
+ "LECA: Setting Supported Codecs"
+ "LECA: UpdateSamplingRate minRate %f, maxRate %f"
+ "LECA: Updating Codecs Input = %{public}s Decoder = %d , Output = %{public}s Encoder = %d"
+ "LEConnectedAudioDevice::UpdateProperty: received kBTAudioMsgCISNeedImmediateDisconnect, triggering immediate CIS disconnect"
+ "Not disconnecting CIS"
+ "Request For route change to non-existing AppleAudioAccessoryDevice"
+ "Send software volume on publish %d"
+ "Sending head tracking state %s to AudioAccessoryDaemon"
+ "UpdateCurrentBTAudioDeviceFromSampleRate LE Connected Audio  %f = %f"
+ "_activePersonalizedVolumeAddresses"
+ "getPropertyData: not enough space for the return value of kBluetoothAudioDevicePropertySoftwareVolumeOnPublish"
+ "kAccAudioMsgArgHeadTrackingEnabled"
+ "kBTAudioMsgCISNeedImmediateDisconnect"
+ "kBTAudioMsgProperty3pHeadTrackingSupport"
+ "kBTAudioMsgPropertyCAPProcStatus"
+ "kBTAudioMsgPropertyEnableSoftwareVolumeOnPublish"
+ "kBTAudioMsgPropertyMaxChannels"
+ "setPropertyData: no active profile while processing of kBluetoothAudioDevicePropertySoftwareVolumeOnPublish"
+ "setPropertyData: not enough space for the return value of kBluetoothAudioDevicePropertySoftwareVolumeOnPublish"
+ "unRegisterPersonalizedVolumeListener %@ "
+ "xpc_get_type(maxChannelsProp) == XPC_TYPE_INT64"
- "High quality FarfieldMic is %s"
- "T@\"NSObject<OS_dispatch_queue>\",N,V_avNotificationMonitorQueue"
- "_avNotificationMonitorQueue"
- "_btPersonalizedVolumeDeviceMutex"
- "avNotificationMonitorQueue"
- "setAvNotificationMonitorQueue:"
- "unRegisterPersonalizedVolumeListener %@ lookupDevice retainCount %d"
```
