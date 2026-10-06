## VisionHWAccelerationServices

> `/System/Library/PrivateFrameworks/VisionHWAccelerationServices.framework/VisionHWAccelerationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2049c` | `0x209c4` | **`+0x528`** |
| `__TEXT.__oslogstring` | `0x1859` | `0x1a15` | **`+0x1bc`** |
| `__AUTH_CONST.__const` | `0xcf8` | `0xd38` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1e8` | `0x228` | **`+0x40`** |
| `__DATA.__bss` | `0x3d8` | `0x410` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x5d8` | `0x600` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x948` | `0x958` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1570` | `0x157c` | **`+0xc`** |
| `__TEXT.__const` | `0x1118` | `0x1120` | **`+0x8`** |
| `__TEXT.__cstring` | `0x12db` | `0x12dd` | **`+0x2`** |

### Other Changes

```diff

-4.4.10.0.0
+4.4.12.0.0

-  Functions: 457
-  Symbols:   266
-  CStrings:  312
+  Functions: 460
+  Symbols:   272
+  CStrings:  320
Symbols:
+ _VisionHWServerStop
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev
+ __ZNSt3__19to_stringEj
+ _dispatch_source_cancel
+ _dispatch_sync
+ _pthread_main_np
+ _xpc_retain
- _VisionHWAccelerationServicesStart
CStrings:
+ "**************** Launching VisionHWAccelerationServices framework version %{public}s *****************"
+ "."
+ "Empty connections list for PID %d"
+ "Listing all connections for PID %d:"
+ "Releasing os_transaction during Shutdown()"
+ "Unexpected entries in pidToConnections map, should be empty. Check code for inconsistent connection clean-up."
+ "VisionHWAServer: Shutdown begin"
+ "VisionHWAServer: Shutdown complete"
+ "VisionHWAServer: Shutdown() called off the main thread -- ignoring to avoid dispatch_sync self-deadlock"
+ "VisionHWAServer: calling VisionHWServerStart()"
+ "VisionHWAServer: calling VisionHWServerStop()"
+ "VisionHWAServer: destructor reached with %zu live client(s) and no Shutdown() -- exit path did not quiesce the service"
+ "XPC connection %p was not removed properly"
- "**************** VisionHWAServer has been disabled in mediaserverd"
- "**************** VisionHWAServer has been disabled in visionserverd"
- "Cancelling all connections for PID %d:"
- "Releasing os_transaction inside DTOR -- visionhwserverd is TERMINATING"
- "VisionHWAServer: VisionHWAccelerationServicesStart is invoked."
```
