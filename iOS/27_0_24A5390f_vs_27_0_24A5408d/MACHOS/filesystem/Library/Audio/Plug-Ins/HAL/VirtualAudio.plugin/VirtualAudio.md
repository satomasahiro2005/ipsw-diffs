## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x56013` | `0x56a41` | **`+0xa2e`** |
| `__DATA_CONST.__const` | `0x294c8` | `0x28c80` | **`-0x848`** |
| `__TEXT.__realtime` | `0x145e4` | `0x14908` | **`+0x324`** |
| `__TEXT.__text` | `0x52efb8` | `0x52ee30` | **`-0x188`** |
| `__TEXT.__unwind_info` | `0x14520` | `0x14430` | **`-0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x5f834` | `0x5f90c` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x36be6` | `0x36b5e` | **`-0x88`** |
| `__DATA.__bss` | `0x25678` | `0x25628` | **`-0x50`** |
| `__TEXT.__const` | `0xb13e0` | `0xb1418` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x2f60` | `0x2f40` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x2890` | `0x28b0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1460` | `0x1470` | **`+0x10`** |
| `__DATA.__data` | `0x5b0` | `0x5a8` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0x102c` | `0x1034` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_Aggregate`
- `__TEXT.__dof_VirtualA0`
- `__TEXT.__dof_VirtualAu`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1451.108.1.0.0
+1451.115.0.0.0

-  Functions: 12360
-  Symbols:   804
-  CStrings:  12081
+  Functions: 12158
+  Symbols:   806
+  CStrings:  12105
Symbols:
+ __ZNSt3__120__libcpp_atomic_waitEPVKvx
+ __ZNSt3__123__libcpp_atomic_monitorEPVKv
CStrings:
+ "%25s:%-5d ASSERTION FAILURE: \"DestroyObjects: RoutingMutex must not be held when acquiring the object mutex\""
+ "%25s:%-5d ASSERTION FAILURE: \"UnregisterObject: RoutingMutex must not be held when acquiring the object mutex\""
+ "%25s:%-5d Bluetooth device %u: set %s=1 at publish returned %s (VA will drive SW volume)"
+ "%25s:%-5d EXCEPTION (kAudioHardwareBadObjectError) [!objectAndMutex is true]: \"ExecuteSynchronized: no object with given ID\""
+ "%25s:%-5d EXCEPTION (kAudioHardwareBadObjectError) [!objectAndMutex is true]: \"TryExecuteSynchronized: no object with given ID\""
+ "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"GetVPMicID failed to resolve internal id '%s' (%u)\""
+ "%25s:%-5d FDR data (%lu bytes) is smaller than its header; returning empty ascf::ArrayRef"
+ "%25s:%-5d FDR data (%lu bytes) too small for %u entries of %u bytes; returning empty ascf::ArrayRef"
+ "%25s:%-5d HardwareVolumeControl::GetDefaultVolumeRangeDecibels: mPhysicalDeviceVolumeControl expired; returning empty range."
+ "%25s:%-5d HardwareVolumeControl::GetHardwareVolumeRangeDecibels: mPhysicalDeviceVolumeControl expired; returning empty range."
+ "%25s:%-5d HardwareVolumeControl::GetPropertyData: mPhysicalDeviceVolumeControl expired; skipping."
+ "%25s:%-5d HardwareVolumeControl::GetPropertyDataSize: mPhysicalDeviceVolumeControl expired; returning 0."
+ "%25s:%-5d HardwareVolumeControl::IsMuted: mPhysicalDeviceVolumeControl expired; returning false."
+ "%25s:%-5d HardwareVolumeControl::Mute: mPhysicalDeviceVolumeControl expired; skipping."
+ "%25s:%-5d HardwareVolumeControl::Reconfigure: mPhysicalDeviceVolumeControl expired; skipping."
+ "%25s:%-5d HardwareVolumeControl::SetPropertyData: mPhysicalDeviceVolumeControl expired; skipping."
+ "%25s:%-5d HardwareVolumeControl::Unmute: mPhysicalDeviceVolumeControl expired; skipping."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::GetPropertyData: owning device expired; skipping."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::GetPropertyDataSize: owning device expired; returning 0."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::HasProperty: owning device expired; returning false."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::IsPropertySettable: owning device expired; returning false."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::RegisterRelayedListener: owning device expired; returning false."
+ "%25s:%-5d Port_MicrophoneBuiltIn_Aspen::UnregisterRelayedListener: owning device expired; returning false."
+ "%25s:%-5d Removing %s for %s"
+ "%25s:%-5d Route activation failed with %lu optional alternate-VAD route(s) present; retrying activation with them dropped."
+ "%25s:%-5d Route activation failed; optional alternate-VAD route %s was present and will be dropped before retry."
+ "%25s:%-5d SelectedMicUpdater: 'chnl' changed %u -> %u; dispatching change callback"
+ "%25s:%-5d SelectedMicUpdater: observation window expired with no 'chnl' change from baseline=%u"
+ "%25s:%-5d Skipping forwarding volume due to client override."
+ "%25s:%-5d Unpublished VA port %u whose backing core port had already expired (async teardown race)."
+ "%25s:%-5d WeakObjectAdapter::GetPropertyData: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::GetPropertyDataSize: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::GetUpdatedDescription: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::HasProperty: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::IsPropertySettable: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::RegisterRelayedListener: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::SetPropertyData: wrapped object expired"
+ "%25s:%-5d WeakObjectAdapter::UnregisterRelayedListener: wrapped object expired"
+ "@@ Strips Aug  4 2026 11:01:42"
+ "ADAMCallbackQueueKey"
+ "GetVPMicID failed to resolve internal id '%s' (%u)"
+ "HardwareMuteControl.h"
+ "Precondition failure: iter != mContextAttributesMap.cend()"
- "!driverDataSourceID"
- "%25s:%-5d Bluetooth device %u: set %s=1 at publish (VA will drive SW volume)"
- "%25s:%-5d Bluetooth device %u: set %s=1 at publish failed with %s (BT side may not have adopted yet)"
- "%25s:%-5d EXCEPTION (kAudioHardwareBadObjectError) [!hasLock is true]: \"TryExecuteSynchronized: unable to lock object map mutex\""
- "%25s:%-5d EXCEPTION (kAudioHardwareBadObjectError) [iter == mObjectMap.cend() is true]: \"ExecuteSynchronized: no object with given ID\""
- "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"Could not find data source %s within ordered data sources\""
- "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"Did not find vp mic id for internal id '%s' (%u)\""
- "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"More than one data source for virtual ID %u\""
- "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"More than one mic for virtual ID %u\""
- "%25s:%-5d Resolved Internal Mic ID:%u to Data Source: %s"
- "%25s:%-5d Using defaults haptic override"
- "@@ Strips Jul 13 2026 21:40:16"
- "Could not find data source %s within ordered data sources"
- "Did not find vp mic id for internal id '%s' (%u)"
- "HapticsExternalPowerAttenuation"
- "More than one data source for virtual ID %u"
- "More than one mic for virtual ID %u"
- "config.mDataSources.size() > 1"
- "driverDataSourceID"
```
