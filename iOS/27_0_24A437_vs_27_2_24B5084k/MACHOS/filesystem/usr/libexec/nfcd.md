## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1edfa8` | `0x1eeb98` | **`+0xbf0`** |
| `__TEXT.__oslogstring` | `0x20c81` | `0x20d8b` | **`+0x10a`** |
| `__TEXT.__objc_methlist` | `0x9f4c` | `0x9fcc` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x15f91` | `0x1600c` | **`+0x7b`** |
| `__DATA.__objc_const` | `0x15238` | `0x152a0` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x2cf8` | `0x2d20` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xe3c0` | `0xe3e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23238` | `0x23254` | **`+0x1c`** |
| `__DATA_CONST.__objc_intobj` | `0x7db8` | `0x7dd0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x4cf8` | `0x4d08` | **`+0x10`** |
| `__TEXT.__const` | `0x144c` | `0x143c` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x1180` | `0x118c` | **`+0xc`** |
| `__TEXT.__objc_classname` | `0x1d83` | `0x1d7c` | **`-0x7`** |
| `__TEXT.__objc_methtype` | `0x4e81` | `0x4e7a` | **`-0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-370.42.1.0.0
+371.7.0.0.0

-  Functions: 4334
+  Functions: 4350

-  CStrings:  11583
+  CStrings:  11591
CStrings:
+ "%{public}s:%i Dropping express capable field notification: expActive=%{public}d, sessionRequestedDrop=%{public}d, expDelayOrPaused=%{public}d"
+ "%{public}s:%i Queue error %{public}@"
+ "%{public}s:%i Session requires reader mode"
+ "%{public}s:%i Thermal pressure is moderate but cooloff already running."
+ "%{public}s:%i eUICC OS reset."
+ "-[NFSMCInterface open]"
+ "-[NFSMCInterface setReaderModeActive:]"
+ "-[NFSMCInterface updateSMC]"
+ "-[_NFHardwareManager(SessionQueue) queueSession:errorHandler:]_block_invoke"
+ "@\"NFSMCInterface\""
+ "NFCD built from (B&I) Stockholm_Base-371.7"
+ "NFSMCInterface"
+ "_currentPower"
+ "_currentTemperature"
+ "_smcInterface"
+ "getSupportedFeatures"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "queueSession:errorHandler:"
+ "updateSMC"
- "%{public}s:%i Dropping express capable field notification"
- "-[NFTemperatureReporter open]"
- "-[NFTemperatureReporter setReaderModeActive:]"
- "-[NFTemperatureReporter updateTemperature:]"
- "@\"NFTemperatureReporter\""
- "NFCD built from (B&I) Stockholm_Base-370.42.1"
- "NFTemperatureReporter"
- "_temperatureReporter"
- "eUICC OS reset"
- "queueSession:"
- "updateTemperature:"
```
