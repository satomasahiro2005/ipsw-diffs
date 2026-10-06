## scrod

> `/System/Library/CoreServices/VoiceOverTouch.app/scrod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb48` | `0xbc94` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x12f2` | `0x138e` | **`+0x9c`** |
| `__TEXT.__objc_methname` | `0x1bbb` | `0x1c0a` | **`+0x4f`** |
| `__DATA.__objc_const` | `0xaa8` | `0xae8` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x794` | `0x7bc` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x8b0` | `0x8b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x850` | `0x858` | **`+0x8`** |
| `__TEXT.__cstring` | `0x386` | `0x388` | **`+0x2`** |
| `__TEXT.__objc_methtype` | `0x3d7` | `0x3d9` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-330.1.0.0.0
+330.1.1.0.0

-  Functions: 159
-  Symbols:   224
-  CStrings:  518
+  Functions: 160
+  Symbols:   225
+  CStrings:  524
Symbols:
+ _OBJC_CLASS_$_NSConstantIntegerNumber
CStrings:
+ "BluetoothManager unavailable, not handling device removal: %@"
+ "Braille service still not connected after %@ attempts (connected services: 0x%lx) - falling back to the reconnection timer for [%{public}@]"
+ "Device remove: %@ [%p]"
+ "Handling device removal: %@ [%p]"
+ "Ignoring device removal for %@: not our address (%@) [%p]"
+ "Q"
+ "Reconnecting braille services to device [%{public}@] (attempt %@ of %@, connected services: 0x%lx)"
+ "Should reload: %@ required services: 0x%lx, connected services: 0x%lx, service connected: %@, display: %p"
+ "_brailleServiceRetryCount"
+ "_lastBrailleServiceRetry"
+ "_resetBrailleServiceRetries"
- "Device remove: %@"
- "Handling device removal: %@"
- "Should reload: %@ required service: %@ service connected: %@, connected services: %@, device: %p"
- "_delayedRemoveDeviceNotification: bluetoothAddress == nil (%@) or address (%@) != bluetoothAddress (%@) or BluetoothManager.sharedInstance not available (%@)"
- "_isDriverLoading set to YES in _delayedRemoveDeviceNotification"
```
