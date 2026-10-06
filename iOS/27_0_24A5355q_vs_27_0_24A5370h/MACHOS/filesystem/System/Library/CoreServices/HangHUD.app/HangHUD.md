## HangHUD

> `/System/Library/CoreServices/HangHUD.app/HangHUD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e73c` | `0x2f59c` | **`+0xe60`** |
| `__TEXT.__objc_methname` | `0xa350` | `0xa716` | **`+0x3c6`** |
| `__TEXT.__objc_stubs` | `0x5860` | `0x5b20` | **`+0x2c0`** |
| `__DATA.__objc_const` | `0x6898` | `0x6aa8` | **`+0x210`** |
| `__DATA_CONST.__cfstring` | `0x5160` | `0x52e0` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x3254` | `0x3364` | **`+0x110`** |
| `__TEXT.__cstring` | `0x3771` | `0x386c` | **`+0xfb`** |
| `__DATA.__objc_selrefs` | `0x2058` | `0x2138` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x50c0` | `0x5130` | **`+0x70`** |
| `__DATA.__objc_data` | `0xe60` | `0xeb0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x19b6` | `0x19f9` | **`+0x43`** |
| `__DATA_CONST.__const` | `0x1a80` | `0x1aa8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xbd0` | `0xbf0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x600` | `0x61c` | **`+0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x324` | `0x33c` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x45a` | `0x46d` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x5f8` | `0x608` | **`+0x10`** |
| `__TEXT.__const` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc28` | `0xc38` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Functions: 1511
-  Symbols:   292
-  CStrings:  3036
+  Functions: 1531
+  Symbols:   294
+  CStrings:  3094
Symbols:
+ _OBJC_CLASS_$_NSJSONSerialization
+ _objc_retain_x26
+ _objc_retain_x7
- __os_log_default
CStrings:
+ "<HTLostPerfInterval: reason=%@ [%llu..%llu]>"
+ "@\"NSSet\""
+ "@32@0:8@16Q24"
+ "@40@0:8@16Q24Q32"
+ "@52@0:8B16B20B24@28Q36@44"
+ "@68@0:8@16@24i32Q36Q44Q52C60S64"
+ "B32@0:8^{?=II}16^@24"
+ "Considering process exit %@: applications allowed"
+ "HTLostPerf: failed to serialize lost-perf payload: %{public}@"
+ "HTLostPerfInterval"
+ "HangTracerEnableTerminationsApplicationsTracked"
+ "Resources"
+ "Security Bounds Safety"
+ "T@\"NSSet\",&,N,V_knownApplications"
+ "T@\"NSSet\",&,N,V_knownCriticalProcesses"
+ "T@\"NSString\",C,N,V_reason"
+ "T@\"NSString\",R,C,V_bundleIdentifier"
+ "TB,N,V_allowsApplications"
+ "TB,R,V_areApplicationTerminationsMonitored"
+ "TQ,N,V_endMATU"
+ "TQ,N,V_startMATU"
+ "_allowsApplications"
+ "_areApplicationTerminationsMonitored"
+ "_bundleIdentifier"
+ "_endMATU"
+ "_knownApplications"
+ "_reason"
+ "_startMATU"
+ "all processes:      %@\ncritical processes: %@\napplications:       %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
+ "allowsApplications"
+ "appendInterval:coalescingWithTailOf:"
+ "applicationBundleIdentifierFromLaunchdLabel:"
+ "areApplicationTerminationsMonitored"
+ "arrayWithCapacity:"
+ "bundleIdentifier"
+ "coalescedIntervalsFromSampleStore:"
+ "configurationAllowingAllProcesses:criticalProcesses:applications:processNames:reasons:subReasons:"
+ "dataWithJSONObject:options:error:"
+ "endMATU"
+ "end_ms"
+ "enumeratorWithOptions:"
+ "getPowerInfo:error:"
+ "initWithData:encoding:"
+ "initWithInfo:bundleIdentifier:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
+ "intervalFromSALostPerfEvent:"
+ "intervals"
+ "intervalsByClippingIntervals:toWindowStart:end:"
+ "jsonStringForIntervals:hangStartMATU:"
+ "knownApplications"
+ "lostPerf"
+ "lostPerfEvents"
+ "machAbsTime"
+ "rangeOfString:"
+ "reason"
+ "resources"
+ "security bounds safety"
+ "setAllowsApplications:"
+ "setEndMATU:"
+ "setKnownApplications:"
+ "setReason:"
+ "setStartMATU:"
+ "startMATU"
+ "start_ms"
+ "substringFromIndex:"
- "@48@0:8B16B20@24Q32@40"
- "@60@0:8@16i24Q28Q36Q44C52S56"
- "T@\"NSArray\",&,N,V_knownCriticalProcesses"
- "all processes:      %@\ncritical processes: %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
- "configurationAllowingAllProcesses:criticalProcesses:processNames:reasons:subReasons:"
- "initWithInfo:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
```
