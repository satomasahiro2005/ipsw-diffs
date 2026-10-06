## hangtracerd

> `/usr/libexec/hangtracerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35a04` | `0x35c00` | **`+0x1fc`** |
| `__TEXT.__objc_methname` | `0x9945` | `0x9b06` | **`+0x1c1`** |
| `__DATA_CONST.__cfstring` | `0x63c0` | `0x64e0` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x5b20` | `0x5c20` | **`+0x100`** |
| `__TEXT.__cstring` | `0x4cb0` | `0x4d64` | **`+0xb4`** |
| `__DATA.__objc_const` | `0x5938` | `0x59c8` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x1e80` | `0x1ec8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x27ec` | `0x281c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xb48` | `0xb78` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x20d8` | `0x2100` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x508` | `0x514` | **`+0xc`** |
| `__TEXT.__gcc_except_tab` | `0x3c4` | `0x3d0` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x1305` | `0x130b` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Functions: 1357
+  Functions: 1362

-  CStrings:  3118
+  CStrings:  3140
Symbols:
+ _objc_retain_x7
- _objc_retain_x6
CStrings:
+ ":"
+ "@52@0:8B16B20B24@28Q36@44"
+ "@68@0:8@16@24i32Q36Q44Q52C60S64"
+ "HangTracerEnableTerminationsApplicationsTracked"
+ "Resources"
+ "Security Bounds Safety"
+ "T@\"NSString\",R,C,V_bundleIdentifier"
+ "TB,N,V_allowsApplications"
+ "TB,R,V_areApplicationTerminationsMonitored"
+ "[({<"
+ "_allowsApplications"
+ "_areApplicationTerminationsMonitored"
+ "_bundleIdentifier"
+ "all processes:      %@\ncritical processes: %@\napplications:       %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
+ "allowsApplications"
+ "applicationBundleIdentifierFromLaunchdLabel:"
+ "areApplicationTerminationsMonitored"
+ "bundleIdentifier"
+ "characterSetWithCharactersInString:"
+ "configurationAllowingAllProcesses:criticalProcesses:applications:processNames:reasons:subReasons:"
+ "initWithInfo:bundleIdentifier:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
+ "rangeOfCharacterFromSet:"
+ "resources"
+ "security bounds safety"
+ "setAllowsApplications:"
+ "substringFromIndex:"
+ "substringToIndex:"
- "@48@0:8B16B20@24Q32@40"
- "@60@0:8@16i24Q28Q36Q44C52S56"
- "all processes:      %@\ncritical processes: %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
- "configurationAllowingAllProcesses:criticalProcesses:processNames:reasons:subReasons:"
- "initWithInfo:pid:spawnTimestamp:exitTimestamp:exitReasonCode:exitReasonNamespace:jetsam_priority:"
```
