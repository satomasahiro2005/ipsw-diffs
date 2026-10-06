## com.apple.iokit.IOHIDFamily

> `com.apple.iokit.IOHIDFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x7998c` | `0x7c610` | **`+0x2c84`** |
| `__TEXT.__const` | `0x1080` | `0x1090` | **`+0x10`** |
| `__TEXT.__os_log` | `0x42dd` | `0x42ec` | **`+0xf`** |
| `__TEXT.__cstring` | `0x33af` | `0x33bb` | **`+0xc`** |

### Other Changes

```diff

-  Functions: 2793
+  Functions: 2808

-  CStrings:  941
+  CStrings:  942
CStrings:
+ "%s:0x%llx keyboard: %d digitizer: %d gameController: %d multiAxis: %d proximity: %d relative: %d scroll: %d led: %d unicode: %d %dcompass: %d orientation %d %d vendor (child): %d vendor (primary): %d biometric: %d gyro: %d temperature: %d accel: %d heartrate:%d hingeangle: %d\n\n"
+ "222111211211111221111112222221112122222222222221111111111111111112111211"
+ "HingeAngle"
- "%s:0x%llx keyboard: %d digitizer: %d gameController: %d multiAxis: %d proximity: %d relative: %d scroll: %d led: %d unicode: %d %dcompass: %d orientation %d %d vendor (child): %d vendor (primary): %d biometric: %d gyro: %d temperature: %d accel: %d heartrate:%d\n\n"
- "22211121121111122111111222222111212222222222222111111111111111112111211"
```
