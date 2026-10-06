## HangTracerSettingsClient

> `/System/Library/PrivateFrameworks/HangTracerSettingsClient.framework/HangTracerSettingsClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1685c` | `0x16a08` | **`+0x1ac`** |
| `__AUTH_CONST.__cfstring` | `0x38c0` | `0x3960` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x310b` | `0x31a2` | **`+0x97`** |
| `__AUTH_CONST.__objc_const` | `0x1570` | `0x15b0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xbec` | `0xc2c` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf8` | `0xb20` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xd58` | `0xd78` | **`+0x20`** |
| `__DATA.__bss` | `0x36a0` | `0x36b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x650` | `0x660` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x360` | `0x368` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc8` | `0xcc` | **`+0x4`** |

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  Functions: 784
-  Symbols:   1147
-  CStrings:  574
+  Functions: 790
+  Symbols:   1157
+  CStrings:  580
Symbols:
+ +[HTProcessExitFilteringConfiguration configurationAllowingAllProcesses:criticalProcesses:applications:processNames:reasons:subReasons:]
+ -[HTProcessExitFilteringConfiguration allowsApplications]
+ -[HTProcessExitFilteringConfiguration setAllowsApplications:]
+ -[HTProcessTerminationSettings _setTracksApplications:]
+ -[HTProcessTerminationSettings setTracksApplications:]
+ -[HTProcessTerminationSettings tracksApplications]
+ _HTUIInternalTerminationsApplicationsToggle
+ _HTUIInternalTerminationsApplicationsToggle.str
+ _OBJC_IVAR_$_HTProcessExitFilteringConfiguration._allowsApplications
+ _kHTExtendedAttributePerformance
+ _kHTPrefsTerminationsApplicationsTracked
+ _objc_retain_x7
- +[HTProcessExitFilteringConfiguration configurationAllowingAllProcesses:criticalProcesses:processNames:reasons:subReasons:]
- _objc_retain_x6
CStrings:
+ "HTUIInternalTerminationsApplicationsToggle"
+ "Resources"
+ "Security Bounds Safety"
+ "all processes:      %@\ncritical processes: %@\napplications:       %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
+ "allowsApplications"
+ "resources"
+ "security bounds safety"
- "all processes:      %@\ncritical processes: %@\nprocess names:      %@\nreasons:            %llu\nsub-reasons:        %@"
```
