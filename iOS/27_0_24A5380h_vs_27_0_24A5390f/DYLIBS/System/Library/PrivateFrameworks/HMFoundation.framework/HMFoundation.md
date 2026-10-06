## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97cbc` | `0x981c8` | **`+0x50c`** |
| `__TEXT.__gcc_except_tab` | `0x1970` | `0x1a9c` | **`+0x12c`** |
| `__TEXT.__oslogstring` | `0x801d` | `0x8109` | **`+0xec`** |
| `__AUTH_CONST.__cfstring` | `0x4ae0` | `0x4b60` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x15c8` | `0x1638` | **`+0x70`** |
| `__TEXT.__cstring` | `0x312b` | `0x3197` | **`+0x6c`** |
| `__AUTH_CONST.__objc_const` | `0xe638` | `0xe698` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x7944` | `0x7994` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1348` | `0x1390` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3100` | `0x3130` | **`+0x30`** |
| `__TEXT.__const` | `0x3028` | `0x3010` | **`-0x18`** |
| `__DATA_DIRTY.__objc_ivar` | `0x5a4` | `0x5ac` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x31e0` | `0x31e8` | **`+0x8`** |

### Other Changes

```diff

-1484.2.0.0.0
+1490.2.0.1.1

-  Functions: 3657
-  Symbols:   5487
-  CStrings:  1415
+  Functions: 3664
+  Symbols:   5504
+  CStrings:  1426
Symbols:
+ +[HMFHTTPRequestHandler _isValidMethodPredicate:]
+ -[HMFMemoryMonitor setTriggerSuppressionExpiry:]
+ -[HMFMemoryMonitor triggerProcessMemoryWarning]
+ -[HMFMemoryMonitor triggerSuppressionExpiry]
+ -[__HMFNetAddressMonitor _handlePathUpdate:]
+ -[__HMFNetAddressMonitor currentPath]
+ -[__HMFNetAddressMonitor pathEvaluator]
+ -[__HMFNetAddressMonitor pathMonitor]
+ -[__HMFNetAddressMonitor setCurrentPath:]
+ -[__HMFNetAddressMonitor setPathEvaluator:]
+ -[__HMFNetAddressMonitor setPathMonitor:]
+ ___45-[__HMFNetAddressMonitor initWithNetAddress:]_block_invoke
+ ___HMFPathDescription
+ ___block_descriptor_40_e8_32w_e30_v16?0"NSObject<OS_nw_path>"8lw32l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ _nw_endpoint_create_host
+ _nw_parameters_create
+ _nw_path_create_evaluator_for_endpoint
+ _nw_path_evaluator_cancel
+ _nw_path_evaluator_copy_path
+ _nw_path_evaluator_set_update_handler
+ _nw_path_get_status
+ _nw_path_monitor_cancel
+ _nw_path_monitor_create
+ _nw_path_monitor_set_queue
+ _nw_path_monitor_set_update_handler
+ _nw_path_monitor_start
+ _nw_path_uses_interface_type
+ _sysctlbyname
- +[HMFHTTPRequestHandler _isValidMethodPrediate:]
- -[__HMFNetAddressMonitor currentNetworkFlags]
- -[__HMFNetAddressMonitor handleNetworkReachabilityChange:]
- -[__HMFNetAddressMonitor networkReachabilityRef]
- -[__HMFNetAddressMonitor setCurrentNetworkFlags:]
- _SCNetworkReachabilityCreateWithAddress
- _SCNetworkReachabilityCreateWithName
- _SCNetworkReachabilityGetFlags
- _SCNetworkReachabilitySetCallback
- _SCNetworkReachabilitySetDispatchQueue
- ___SCNetworkReachabilityFlagsToString
- __networkReachabilityChangeCallback
CStrings:
+ "0"
+ "Error (%s) sending internal memory pressure event"
+ "Failed to create endpoint for %@"
+ "Failed to create network path monitor"
+ "Failed to create path evaluator for %@"
+ "Received path update: %@"
+ "Success sending internal memory pressure event"
+ "Suppressing observer dispatch for triggered %@"
+ "[%{public}@] Error (%s) sending internal memory pressure event"
+ "[%{public}@] Failed to create endpoint for %@"
+ "[%{public}@] Failed to create network path monitor"
+ "[%{public}@] Failed to create path evaluator for %@"
+ "[%{public}@] Received path update: %@"
+ "[%{public}@] Success sending internal memory pressure event"
+ "[%{public}@] Suppressing observer dispatch for triggered %@"
+ "cellular"
+ "invalid"
+ "kern.memorystatus_vm_pressure_send"
+ "satisfiable"
+ "satisfied"
+ "unsatisfied"
+ "v16@?0@\"NSObject<OS_nw_path>\"8"
+ "wifi"
+ "wired"
- "Failed to create network reachability monitor%@."
- "Failed to get initial reachability"
- "Initial flags: %@"
- "Reachable"
- "Received notification of updated flags: %@"
- "Updating reachability to: %@"
- "WWAN"
- "[%{public}@] Failed to create network reachability monitor%@."
- "[%{public}@] Failed to get initial reachability"
- "[%{public}@] Initial flags: %@"
- "[%{public}@] Received notification of updated flags: %@"
- "[%{public}@] Updating reachability to: %@"
- "for %@"
```
