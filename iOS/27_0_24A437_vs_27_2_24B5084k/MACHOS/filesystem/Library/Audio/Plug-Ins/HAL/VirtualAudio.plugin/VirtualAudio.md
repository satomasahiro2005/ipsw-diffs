## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5477f4` | `0x5582dc` | **`+0x10ae8`** |
| `__TEXT.__gcc_except_tab` | `0x611d0` | `0x65bec` | **`+0x4a1c`** |
| `__TEXT.__oslogstring` | `0x58164` | `0x58ca1` | **`+0xb3d`** |
| `__TEXT.__unwind_info` | `0x14a20` | `0x14f80` | **`+0x560`** |
| `__DATA_CONST.__const` | `0x294d8` | `0x296b0` | **`+0x1d8`** |
| `__TEXT.__realtime` | `0x14ab0` | `0x14c60` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x375c2` | `0x376f2` | **`+0x130`** |
| `__DATA_CONST.__cfstring` | `0x2fa0` | `0x2ec0` | **`-0xe0`** |
| `__TEXT.__auth_stubs` | `0x29b0` | `0x2a40` | **`+0x90`** |
| `__DATA.__bss` | `0x25ed0` | `0x25e60` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x14f0` | `0x1538` | **`+0x48`** |
| `__TEXT.__const` | `0xb4918` | `0xb4938` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x530` | `0x540` | **`+0x10`** |
| `__DATA.__data` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__TEXT.__init_offsets` | `0x1048` | `0x104c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
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

-1451.115.30.0.0
+1451.208.0.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Functions: 12452
-  Symbols:   827
-  CStrings:  12292
+  Functions: 12517
+  Symbols:   836
+  CStrings:  12319
Symbols:
+ _SCDynamicStoreCopyComputerName
+ _SCPreferencesCreate
+ _SCPreferencesSetCallback
+ _SCPreferencesSetDispatchQueue
+ __ZN5caulk10concurrent7details23lf_read_sync_write_impl10end_mutateEj
+ __ZN5caulk10concurrent7details23lf_read_sync_write_impl12begin_mutateEv
+ __ZN5caulk10concurrent7details23lf_read_sync_write_implC1Ev
+ __ZN5caulk14cf_preferences19interpret_log_levelEPKv
+ __ZN5caulk14cf_preferences7monitor12_add_handlerEPK10__CFStringS4_ONSt3__18functionIFbPKvEEE
+ __ZN5caulk14cf_preferences7monitor8instanceEv
+ __ZN5caulk14cf_preferences8get_boolEPK10__CFStringS3_
+ __ZN5caulk14cf_preferences9get_int64EPK10__CFStringS3_
+ __ZN5caulk7product11_aid_prefixEv
+ __ZNK5caulk10concurrent7details23lf_read_sync_write_impl10end_accessEv
+ __ZNK5caulk10concurrent7details23lf_read_sync_write_impl12begin_accessEv
+ __ZNSt13runtime_errorC2ERKS_
+ __ZNSt3__112system_errorC1EiRKNS_14error_categoryE
+ __ZNSt3__112system_errorD1Ev
+ __ZNSt3__115system_categoryEv
+ __ZTVNSt3__112system_errorE
+ __dispatch_main_q
- _CFPreferencesCopyAppValue
- _CFSetAddValue
- _CFSetApplyFunction
- _CFSetCreateMutable
- _MGCancelNotifications
- _MGGetStringAnswer
- _MGRegisterForUpdates
- __ZTVN10__cxxabiv121__vmi_class_type_infoE
- ___atomic_load
- ___atomic_store
- __dispatch_source_type_signal
- _kCFTypeSetCallBacks
CStrings:
+ "%25s:%-5d ASSERTION FAILURE: \"Empty routing manager state to restore\""
+ "%25s:%-5d Applying state with category mode: %s"
+ "%25s:%-5d Cached format map resolved client format %s to physical format %s, which the hardware no longer publishes. Refreshing formats before attempting to set."
+ "%25s:%-5d Cached port for filter %s has expired. Re-searching for a suitable port."
+ "%25s:%-5d Client format %s maps to physical format %s, which the hardware does not publish. Failing the set rather than waiting for it to time out."
+ "%25s:%-5d Could not apply state: Empty routing manager state"
+ "%25s:%-5d Defaults key %s was defined to %f milliseconds"
+ "%25s:%-5d Encountered invalid port in disconnections list."
+ "%25s:%-5d Error '%s' getting physical format for client format %s after refreshing stream formats"
+ "%25s:%-5d Error '%s' reading available physical formats from actual stream; assuming %s is available"
+ "%25s:%-5d HapticAttenuationAnalytics: Attenuation in this session ranged from dB=%.2f (for %s%s) to dB=%.2f (for %s%s)"
+ "%25s:%-5d HapticAttenuationAnalytics: Attenuation in this session was constant at dB=%.2f for %s%s"
+ "%25s:%-5d HapticAttenuationAnalytics: No attenuation applied in this session"
+ "%25s:%-5d HapticAttenuationAnalytics: no open session; dropping Stop"
+ "%25s:%-5d HapticAttenuationAnalytics: no reporter ID; retrying on the next haptics session"
+ "%25s:%-5d HapticAttenuationAnalytics: session already open; dropping Start"
+ "%25s:%-5d Invalidating route cache for %s after a route-change failure in VA_PlugIn."
+ "%25s:%-5d No sample rate in the description for physical device %s; leaving its rate unchanged."
+ "%25s:%-5d Omitting an expired physical device from the sample rate description."
+ "%25s:%-5d On-demand audio session requires HFP input. Disallowing A2DP port type"
+ "%25s:%-5d Purged %zu expired port(s) from mConnectedPorts."
+ "%25s:%-5d Requested to set %u, which resolved to the buffer frame size of %u already in use on aggregate device %u."
+ "%25s:%-5d Route change failed. Invalidating VAD contexts: %s"
+ "%25s:%-5d Sample rate description holds %s entries for %s live physical devices; devices without an entry will be left alone."
+ "%25s:%-5d Skipped %zu expired port(s) while collecting VA port IDs."
+ "%25s:%-5d The buffer frame size of %u is below the voice-processing threshold of %u at the new sample rate of %f Hz, re-applying the requested frame size of %u on aggregate device %u."
+ "%25s:%-5d The master physical device has expired; matching each physical device to the requested rate."
+ "%25s:%-5d The master physical device has no entry in the sample rate description; not waiting for the aggregate device's rate."
+ "%25s:%-5d The requested frame size (%u) resolved to %u, which is below the performant threshold of %u (%.2f ms) for a voice-processing chat route, setting the frame size to that threshold on aggregate device %u."
+ "%25s:%-5d [POTENTIAL_VA_RACE] Current physical stream format %s is absent from HAL's pre-culling format list as well: %s (culled list: %s). The available format list disagrees with the current format, so failing the format update instead of setting a closest match computed from a list the device has already moved off. This stream's initialization and the route activation will fail rather than block. This is the only record of the two lists, as the update fails here before GetClientFormatForPhysicalFormat() runs its own format dump."
+ "(inSampleRateDescription.size() == 0) && (liveDeviceCount != 0)"
+ "@@ Strips Sep  3 2026 00:42:08"
+ "Endpoint Type Policy: {}"
+ "HapticAttenuationAnalytics.cpp"
+ "Invariant failure: CurrentRouteHasReceiverRoute()"
+ "VPMinFrameDurationMilliseconds"
+ "VirtualAudio_HDMI"
+ "com.apple.virtualaudio.hapticattenuationanalytics"
+ "forgetting-factor"
+ "haptics_device_hinge_angle_degrees"
+ "haptics_device_hinge_state"
+ "haptics_device_state_stable"
+ "haptics_final_attenuation_db"
+ "haptics_initial_attenuation_db"
+ "haptics_least_attenuation_db"
+ "haptics_least_attenuation_optional_angle"
+ "haptics_least_attenuation_source"
+ "haptics_most_attenuation_db"
+ "haptics_most_attenuation_optional_angle"
+ "haptics_most_attenuation_source"
- "!haveCachedPort"
- "!result"
- "%25s:%-5d EXCEPTION (std::logic_error) [%s is true]: \"Failed to cache result due to overlapping cache values\""
- "%25s:%-5d Encountered invalid port in disconnections list. Purging expired ports from mConnectedPorts."
- "%25s:%-5d HapticAttenuationIODelegate: Maximum attenuation applied in this session was for %s%s (dB=%.2f)"
- "%25s:%-5d HapticAttenuationIODelegate: No attenuation applied in this session"
- "%25s:%-5d On-demand audio session allows HFP input. Disallowing A2DP port type"
- "%d"
- "@@ Strips Aug  8 2026 18:42:51"
- "Bluetooth port must be a headset-type"
- "CAException"
- "Failed to cache result due to overlapping cache values"
- "Invariant failure: CategoryHasReceiverRoute(mCurrentCategoryMode.mCategory)"
- "UserAssignedDeviceName"
- "details"
- "error"
- "inSampleRateDescription.size() != mPhysicalDevicePtrList.size()"
- "info"
- "minutiae"
- "note"
- "notice"
- "spew"
- "warning"
```
