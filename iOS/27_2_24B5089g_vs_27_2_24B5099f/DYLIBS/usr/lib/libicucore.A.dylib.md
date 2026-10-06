## libicucore.A.dylib

> `/usr/lib/libicucore.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26aa34` | `0x26b324` | **`+0x8f0`** |
| `__AUTH.__thread_bss` | `0x2310` | `0x2640` | **`+0x330`** |
| `__TEXT.__const` | `0x6b3c0` | `0x6b440` | **`+0x80`** |
| `__DATA.__bss` | `0x1119` | `0x10c9` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x1800` | `0x1850` | **`+0x50`** |
| `__DATA.__data` | `0x938` | `0x934` | **`-0x4`** |

### Other Changes

```diff

-78136.0.0.0.0
+78138.0.0.0.0

-  Functions: 12208
-  Symbols:   8966
+  Functions: 12214
+  Symbols:   8968
Symbols:
+ __ZN3icu17HinduCalendarBase17setSolarEphemerisENS_18CalendarAstronomer20SolarEphemerisChoiceE
+ _ucal_setSolarEphemeris
```
