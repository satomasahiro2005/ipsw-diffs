## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd58` | `0x1bdc8` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x1440` | `0x1460` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3356` | `0x3364` | **`+0xe`** |
| `__TEXT.__cstring` | `0x1375` | `0x137f` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-180.0.0.0.0
+182.0.0.0.0

-  CStrings:  1484
+  CStrings:  1485
Functions:
~ sub_100002b4c : 2080 -> 2192
CStrings:
+ "AssistantMode changing from %@ to %@ (siriRemoteSession=%d, siriLocalSession=%d, assistantUI=%d, nanoSiriX=%d)"
+ "NanoSiriX"
+ "evaluatePowerMode: %@: %d display %d, carPlaySession %d, nFCSession %d, audioSession %d, sleepInProgress %d, wakeInProgress %d, onenessSession %d, siriAudio %d, siriRemoteSession %d, siriLocalSession %d, assistantUI %d, nanoSiriX %d, fitnessIntelligence %d, dataMigrationInProgress %d, dischargeInProgress %d, usbDeviceMode %d, pluggedIn %d (allowOnCharger: %d)"
- "AssistantMode changing from %@ to %@ (siriRemoteSession=%d, siriLocalSession=%d, assistantUI=%d, siriAudio=%d)"
- "evaluatePowerMode: %@: %d display %d, carPlaySession %d, nFCSession %d, audioSession %d, sleepInProgress %d, wakeInProgress %d, onenessSession %d, siriAudio %d, siriRemoteSession %d, siriLocalSession %d, assistantUI %d, fitnessIntelligence %d, dataMigrationInProgress %d, dischargeInProgress %d, usbDeviceMode %d, pluggedIn %d (allowOnCharger: %d)"
```
