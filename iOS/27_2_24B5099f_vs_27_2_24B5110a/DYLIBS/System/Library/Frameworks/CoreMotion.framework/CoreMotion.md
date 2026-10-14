## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d0e64` | `0x3d3744` | **`+0x28e0`** |
| `__TEXT.__gcc_except_tab` | `0xd50c` | `0xd7ec` | **`+0x2e0`** |
| `__AUTH_CONST.__const` | `0x158b8` | `0x15b70` | **`+0x2b8`** |
| `__TEXT.__cstring` | `0x47ac5` | `0x47d4b` | **`+0x286`** |
| `__TEXT.__oslogstring` | `0x2fcd1` | `0x2ff23` | **`+0x252`** |
| `__TEXT.__const` | `0xcd60` | `0xcf70` | **`+0x210`** |
| `__AUTH_CONST.__objc_const` | `0x1dd78` | `0x1df28` | **`+0x1b0`** |
| `__TEXT.__unwind_info` | `0xbcf8` | `0xbe90` | **`+0x198`** |
| `__TEXT.__objc_methlist` | `0xd9ac` | `0xda5c` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x320` | `0x370` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x13d20` | `0x13d60` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5728` | `0x5748` | **`+0x20`** |
| `__DATA.__common` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA.__data` | `0xe10` | `0xe20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x17b8` | `0x17c8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x8e0` | `0x8e8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x7c8` | `0x7d0` | **`+0x8`** |

### Other Changes

```diff

-3186.0.21.0.0
+3186.0.22.0.0

-  Functions: 12720
+  Functions: 12788

-  CStrings:  11441
+  CStrings:  11466
CStrings:
+ "%{public}s calling setDisplayAngleHandler:%{public}p interval:%{public}f"
+ "-[CMMotionManager setDisplayAngleHandler:interval:]"
+ "22:49:05"
+ "CLHomeHubServiceNotifier"
+ "CLHomeHubServiceNotifier.mm"
+ "CMDisplayAngleService.mm"
+ "DisplayAngle"
+ "Oct  6 2026"
+ "[CLHomeHubServiceNotifier] %{public}s : Bump detected, timestamp=%{public}lf, now=%{public}lf"
+ "[CLHomeHubServiceNotifier] %{public}s : angle=%{public}f, isAngleStable=%{public}d, timestamp=%{public}lf, now=%{public}lf"
+ "[CLHomeHubServiceNotifier] Bad report,type,%{public}d,size,%{public}lu"
+ "[CLHomeHubServiceNotifier] Empty payload, returning"
+ "[CLHomeHubServiceNotifier] Event ref invalid"
+ "[CLHomeHubServiceNotifier] Failed to send EnableBumpEvents command"
+ "[CLHomeHubServiceNotifier] Failed to send EnableDisplayAngle command"
+ "angle %f, isStable: %d @ %f"
+ "fHaveActivatedAOP"
+ "fHidDriverInterface"
+ "isAngleStable"
+ "onDisplayAngleChange"
+ "reopenHIDDriverInterface"
+ "updateReportInterval"
+ "virtual void CLHomeHubServiceNotifier::visitBumpEvent(const CMHomeHubReport::BumpEvent &)"
+ "virtual void CLHomeHubServiceNotifier::visitDisplayAngleState(const DisplayAngleState &)"
+ "void CLHomeHubServiceNotifier::onIoHidEvent(IOHIDEventRef)"
+ "void CLHomeHubServiceNotifier::setBumpEventsEnabled(bool)"
+ "void CLHomeHubServiceNotifier::setDisplayAngleEnabled(bool)"
- "22:22:50"
- "Sep 28 2026"
```
