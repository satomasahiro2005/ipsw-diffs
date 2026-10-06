## libsysdiagnose.dylib

> `/usr/lib/libsysdiagnose.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ecc` | `0x2eb0` | **`-0x1c`** |

### Other Changes

```diff

-1587.0.0.0.0
+1593.0.0.0.0
Functions:
~ +[Libsysdiagnose createSysdiagnoseRequest:] : 836 -> 832
~ +[Libsysdiagnose isSysdiagnoseInProgressWithError:] : 684 -> 680
~ +[Libsysdiagnose fetchDiagnosticIDFromDeviceSource:WithMaxCount:withError:] : 1232 -> 1224
~ +[Libsysdiagnose getSysdiagnoseCrashLog] : 932 -> 920
```
