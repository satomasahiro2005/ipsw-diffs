## ANECompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANECompilerService.xpc/ANECompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x167c8` | `0x1819c` | **`+0x19d4`** |
| `__DATA_CONST.__cfstring` | `0x12c0` | `0x1880` | **`+0x5c0`** |
| `__TEXT.__cstring` | `0xe77` | `0x1255` | **`+0x3de`** |
| `__TEXT.__gcc_except_tab` | `0x1048` | `0x1210` | **`+0x1c8`** |
| `__TEXT.__objc_stubs` | `0x1fc0` | `0x2160` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x2332` | `0x246d` | **`+0x13b`** |
| `__TEXT.__oslogstring` | `0x2025` | `0x20e8` | **`+0xc3`** |
| `__DATA.__objc_selrefs` | `0x9d0` | `0xa40` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x188` | `0x1b8` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x7a0` | `0x7d0` | **`+0x30`** |
| `__DATA.__data` | `0x3c8` | `0x3f0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x300` | `0x320` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x3e8` | `0x400` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x944` | `0x954` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.9.0.0.0
+382.11.0.0.0

-  Functions: 286
-  Symbols:   907
-  CStrings:  779
+  Functions: 291
+  Symbols:   933
+  CStrings:  842
Symbols:
+ +[_ANESandboxingHelper issueSandboxExtensionForWeights:]
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_NSMutableArray
+ __ANECompilerServiceRUsageDict
+ __dispatch_main_q
+ _kANEFCompilerServiceBundleIdentifierKey
+ _kANEFCompilerServiceRUsageAfterKey
+ _kANEFCompilerServiceRUsageBeforeKey
+ _kANEFInMemoryModelFileHashesKey
+ _kANEFInMemoryModelFileNamesKey
+ _objc_msgSend$allValues
+ _objc_msgSend$array
+ _objc_msgSend$bundleIdentifier
+ _objc_msgSend$containsObject:
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$largeModelCompilerServiceAccessEntitlement
+ _objc_msgSend$largeModelCompilerServiceBundleID
+ _objc_msgSend$longLongValue
+ _objc_msgSend$mainBundle
+ _objc_msgSend$numberWithLongLong:
+ _objc_msgSend$objectAtIndexedSubscript:
+ _objc_msgSend$setExternConstants:
+ _objc_msgSend$verifyBundleAtPath:expectedHashes:error:
+ _proc_pid_rusage
+ _proc_reset_footprint_interval
+ _xpc_transaction_exit_clean
CStrings:
+ "%@: failed to consume sandbox extension for %@: %@"
+ "%@: releaseSandboxExtension failed for token=%@ handle=%@ errno=%d"
+ "Exiting ANELargeModelCompilerService after compile to avoid VA fragmentation"
+ "Path"
+ "_SBExtension"
+ "allValues"
+ "array"
+ "bundleIdentifier"
+ "com.apple.ANELargeModelCompilerService"
+ "containsObject:"
+ "dictionaryWithCapacity:"
+ "handle"
+ "issueSandboxExtensionForWeights:"
+ "kANEFCompilerServiceBundleIdentifierKey"
+ "kANEFCompilerServiceRUsageAfterKey"
+ "kANEFCompilerServiceRUsageBeforeKey"
+ "kANEFInMemoryModelFileHashesKey"
+ "kANEFInMemoryModelFileNamesKey"
+ "largeModelCompilerServiceAccessEntitlement"
+ "largeModelCompilerServiceBundleID"
+ "longLongValue"
+ "mainBundle"
+ "numberWithLongLong:"
+ "objectAtIndexedSubscript:"
+ "ri_billed_energy"
+ "ri_billed_system_time"
+ "ri_child_elapsed_abstime"
+ "ri_child_interrupt_wkups"
+ "ri_child_pageins"
+ "ri_child_pkg_idle_wkups"
+ "ri_child_system_time"
+ "ri_child_user_time"
+ "ri_cpu_time_qos_background"
+ "ri_cpu_time_qos_default"
+ "ri_cpu_time_qos_legacy"
+ "ri_cpu_time_qos_maintenance"
+ "ri_cpu_time_qos_user_initiated"
+ "ri_cpu_time_qos_user_interactive"
+ "ri_cpu_time_qos_utility"
+ "ri_cycles"
+ "ri_diskio_bytesread"
+ "ri_diskio_byteswritten"
+ "ri_flags"
+ "ri_instructions"
+ "ri_interrupt_wkups"
+ "ri_interval_max_phys_footprint"
+ "ri_lifetime_max_phys_footprint"
+ "ri_logical_writes"
+ "ri_pageins"
+ "ri_phys_footprint"
+ "ri_pkg_idle_wkups"
+ "ri_proc_exit_abstime"
+ "ri_proc_start_abstime"
+ "ri_resident_size"
+ "ri_runnable_time"
+ "ri_serviced_energy"
+ "ri_serviced_system_time"
+ "ri_system_time"
+ "ri_user_time"
+ "ri_wired_size"
+ "setExternConstants:"
+ "token"
+ "verifyBundleAtPath:expectedHashes:error:"
```
