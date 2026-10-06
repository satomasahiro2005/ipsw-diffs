## GameControllerIO

> `/System/Library/PrivateFrameworks/GameControllerIO.framework/GameControllerIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xf0` | **`+0xf0`** |
| `__TEXT.__text` | `0x5464` | `0x5428` | **`-0x3c`** |

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

-  Symbols:   525
+  Symbols:   527
Symbols:
+ _objc_getProperty
+ _objc_setProperty_atomic
Functions:
~ -[GCGamepadHIDServicePlugin updateHapticMotor:] : 184 -> 156
~ -[GCGamepadHIDServicePlugin enqueueTransient:hapticMotor:] : 168 -> 136
~ -[GCGamepadHIDServicePlugin hapticMotors] : 8 -> 12
~ -[GCGamepadHIDServicePlugin setHapticMotors:] : 12 -> 8
```
