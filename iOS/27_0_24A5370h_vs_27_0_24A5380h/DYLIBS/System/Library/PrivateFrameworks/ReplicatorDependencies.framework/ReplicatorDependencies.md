## ReplicatorDependencies

> `/System/Library/PrivateFrameworks/ReplicatorDependencies.framework/ReplicatorDependencies`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0xdc0` | `0x1008` | **`+0x248`** |
| `__TEXT.__text` | `0x29c98` | `0x29a94` | **`-0x204`** |
| `__AUTH.__data` | `0x238` | `0x38` | **`-0x200`** |
| `__DATA.__bss` | `0x1710` | `0x1910` | **`+0x200`** |
| `__TEXT.__const` | `0x1cb4` | `0x1e94` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x1f80` | `0x2120` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1321` | `0x11a1` | **`-0x180`** |
| `__TEXT.__eh_frame` | `0x948` | `0xa58` | **`+0x110`** |
| `__DATA_DIRTY.__bss` | `0x800` | `0x900` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xa88` | `0xb58` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x9ac` | `0xa6c` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x798` | `0x838` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x1228` | `0x1288` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x10cc` | `0x1118` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0xb88` | `0xbc8` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xbce` | `0xc00` | **`+0x32`** |
| `__DATA.__data` | `0x558` | `0x540` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x464` | `0x47c` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x130` | `0x148` | **`+0x18`** |
| `__TEXT.__cstring` | `0x501` | `0x511` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xb0` | **`+0xc`** |

### Other Changes

```diff

-168.0.0.0.0
+172.0.0.0.0

-  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 1152
-  Symbols:   604
-  CStrings:  123
+  Functions: 1190
+  Symbols:   618
+  CStrings:  114
Symbols:
+ ___swift_memcpy42_8
+ ___swift_memcpy49_8
+ ___swift_memcpy50_8
+ _associated conformance 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV0E4TypeOSHAASQ
+ _associated conformance 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV0cdE5ErrorOSHAASQ
+ _nw_browse_descriptor_set_include_txt_record
+ _nw_endpoint_copy_txt_record
+ _nw_txt_record_access_key
+ _nw_txt_record_is_dictionary
+ _os_unfair_lock_assert_not_owner
+ _swift_unknownObjectRetain_n
+ _symbolic _____ 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV
+ _symbolic _____ 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV0E4TypeO
+ _symbolic _____ 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV0cdE5ErrorO
+ _symbolic _____SgXwz_Xx 22ReplicatorDependencies14NetworkBrowserC
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _type_layout_string 22ReplicatorDependencies14NetworkBrowserC0cD6ResultV
- ___swift_memcpy34_8
- _nw_endpoint_access_custom_metadata_for_key
- _symbolic ______p So14OS_nw_listenerP
CStrings:
+ "%{public}s: %{public}s %{public}s will be used for connection: %{public}s"
+ "%{public}s: %{public}s created: %s"
+ "%{public}s: Browse results changed"
+ "%{public}s: Browser created %{public}s"
+ "%{public}s: Browser found device with ID: %{public}s; name: %{public}s; isMeDevice: %{bool,public}d"
+ "%{public}s: Browser state changed"
+ "%{public}s: Browser state: cancelled"
+ "%{public}s: Browser state: failed"
+ "%{public}s: Browser state: ready"
+ "%{public}s: Browser state: waiting"
+ "%{public}s: Canceling browser"
+ "%{public}s: Discarding monitor"
+ "%{public}s: Listener failed with error: %{public}s"
+ "%{public}s: Listener is ready"
+ "%{public}s: Listener state changed to %{public}s"
+ "%{public}s: Monitor found remote device with ID %{public}s but it is not the 'me' device"
+ "%{public}s: Monitor found remote device with ID: %{public}s"
+ "%{public}s: Monitor results changed"
+ "%{public}s: Monitor state changed"
+ "%{public}s: Monitor state: cancelled"
+ "%{public}s: Monitor state: failed"
+ "%{public}s: Monitor state: ready"
+ "%{public}s: Monitor state: waiting"
+ "%{public}s: Received new connection: %{public}s: DeviceID: %{public}s"
+ "%{public}s: Skipping browser event: %{public}@"
+ "%{public}s: Unable to get DeviceID from connection: %{public}s: Using uuidString %{public}s instead"
+ "%{public}s; Skipping monitor event: %{public}@"
- "%{public}s %{public}s will be used for connection: %{public}s"
- "%{public}s created %{public}s"
- "%{public}s; Browse results changed"
- "%{public}s; Browser added device"
- "%{public}s; Browser found an uninteresting change"
- "%{public}s; Browser removed device"
- "%{public}s; Browser state changed"
- "%{public}s; Browser state: cancelled"
- "%{public}s; Browser state: failed"
- "%{public}s; Browser state: ready"
- "%{public}s; Browser state: waiting"
- "%{public}s; Listener failed with error: %{public}s"
- "%{public}s; Listener is ready"
- "%{public}s; Listener state changed to %{public}s"
- "%{public}s; Monitor added device"
- "%{public}s; Monitor found an uninteresting change"
- "%{public}s; Monitor removed device"
- "%{public}s; Monitor results changed"
- "%{public}s; Monitor state changed"
- "%{public}s; Monitor state: cancelled"
- "%{public}s; Monitor state: failed"
- "%{public}s; Monitor state: ready"
- "%{public}s; Monitor state: waiting"
- "%{public}s; No usable endpoint found in browser results"
- "%{public}s; No usable endpoint found in monitor results"
- "%{public}s; Received new connection: %{public}s; DeviceID: %{public}s"
- "Already cancelled"
- "Browser created %{public}s"
- "Browser found Remote device with no name"
- "Browser found device with ID: %{public}s; name: %{public}s; isMeDevice: %{bool,public}d"
- "Browser found remote device with no ID"
- "Canceling browser: %{public}s"
- "Monitor found device with ID: %{public}s"
- "Monitor found remote device with ID %{public}s but it is not the 'me' device"
- "Monitor found remote device with no ID"
- "Unable to get DeviceID from connection: %{public}s; Using uuidString %{public}s instead"
```
