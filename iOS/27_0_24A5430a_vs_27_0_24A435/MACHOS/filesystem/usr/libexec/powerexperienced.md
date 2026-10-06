## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b58c` | `0x1c2cc` | **`+0xd40`** |
| `__TEXT.__objc_methname` | `0x42e7` | `0x4508` | **`+0x221`** |
| `__DATA.__objc_const` | `0x5840` | `0x5a40` | **`+0x200`** |
| `__TEXT.__objc_stubs` | `0x3ac0` | `0x3ca0` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x32fc` | `0x3455` | **`+0x159`** |
| `__TEXT.__objc_methlist` | `0x2484` | `0x25c4` | **`+0x140`** |
| `__DATA.__objc_selrefs` | `0x11c0` | `0x1260` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1361` | `0x13e4` | **`+0x83`** |
| `__DATA.__data` | `0x600` | `0x660` | **`+0x60`** |
| `__DATA.__objc_data` | `0x910` | `0x960` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x780` | `0x7d0` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x8a6` | `0x8eb` | **`+0x45`** |
| `__DATA_CONST.__const` | `0x918` | `0x940` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x420` | `0x442` | **`+0x22`** |
| `__DATA_CONST.__cfstring` | `0x13e0` | `0x1400` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x278` | `0x290` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x48` | `0x5c` | **`+0x14`** |
| `__DATA.__bss` | `0x280` | `0x290` | **`+0x10`** |
| `__DATA_CONST.__objc_floatobj` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__const` | `0x150` | `0x158` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 860
-  Symbols:   175
-  CStrings:  1457
+  Functions: 889
+  Symbols:   178
+  CStrings:  1502
Symbols:
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_NSConstantFloatNumber
+ _OBJC_CLASS_$_NSHashTable
CStrings:
+ "@\"AngleMonitor\""
+ "@\"CMAngleManager\""
+ "@\"NSHashTable\""
+ "AngleMonitor"
+ "AngleMonitorDelegate"
+ "CMAngleManager not available on this device"
+ "Initiated CMAngleManager with update interval %f"
+ "Invalid angle sample: state=%ld eventPhase=%ld"
+ "Received angle update: angleDegrees=%f angleValid=%d state=%ld eventPhase=%ld"
+ "T@\"AngleMonitor\",&,N,V_angleMonitor"
+ "T@\"CMAngleManager\",&,V_angleManager"
+ "T@\"NSHashTable\",&,V_delegates"
+ "T@\"NSOperationQueue\",&,V_angleQueue"
+ "TB,R,N,GisAvailable"
+ "_angleManager"
+ "_angleMonitor"
+ "_angleQueue"
+ "angleDegrees"
+ "angleDidUpdate:"
+ "angleManager"
+ "angleMonitor"
+ "angleQueue"
+ "anglemonitor"
+ "available"
+ "com.apple.powerexperienced.thermalexperience"
+ "com.apple.powerexperienced.thermalexperiencecontroller"
+ "eventPhase"
+ "initAngleMonitor"
+ "isAngleActive"
+ "isAngleValid"
+ "isAvailable"
+ "notifyDelegatesWithAngle:"
+ "numberWithFloat:"
+ "removeDelegate:"
+ "setAngleManager:"
+ "setAngleMonitor:"
+ "setAngleQueue:"
+ "setAngleUpdateInterval:"
+ "startAngleUpdatesToQueue:handler:"
+ "startMonitoring: CMAngleManager not available, skipping"
+ "startMonitoring: angle updates already active, skipping"
+ "stopAngleUpdates"
+ "v16@?0@\"CMAngle\"8"
+ "v24@0:8@\"CMAngle\"16"
+ "weakObjectsHashTable"
```
