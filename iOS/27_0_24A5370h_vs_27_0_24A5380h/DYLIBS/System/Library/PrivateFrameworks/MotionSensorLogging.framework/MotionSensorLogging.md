## MotionSensorLogging

> `/System/Library/PrivateFrameworks/MotionSensorLogging.framework/MotionSensorLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x266e84` | `0x26819c` | **`+0x1318`** |
| `__TEXT.__cstring` | `0x127b9` | `0x12810` | **`+0x57`** |
| `__AUTH_CONST.__const` | `0xb3c0` | `0xb410` | **`+0x50`** |
| `__TEXT.__const` | `0x491a` | `0x493a` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6880` | `0x68a0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x3c94` | `0x3ca4` | **`+0x10`** |

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 10474
-  Symbols:   11913
-  CStrings:  3849
+  Functions: 10492
+  Symbols:   11934
+  CStrings:  3857
Symbols:
+ __ZN5CMMsl11ButtonPress8readFromERN2PB6ReaderE
+ __ZN5CMMsl11ButtonPressC1EOS0_
+ __ZN5CMMsl11ButtonPressC1ERKS0_
+ __ZN5CMMsl11ButtonPressC1Ev
+ __ZN5CMMsl11ButtonPressC2EOS0_
+ __ZN5CMMsl11ButtonPressC2ERKS0_
+ __ZN5CMMsl11ButtonPressC2Ev
+ __ZN5CMMsl11ButtonPressD0Ev
+ __ZN5CMMsl11ButtonPressD1Ev
+ __ZN5CMMsl11ButtonPressD2Ev
+ __ZN5CMMsl11ButtonPressaSEOS0_
+ __ZN5CMMsl11ButtonPressaSERKS0_
+ __ZN5CMMsl4Item15makeButtonPressEv
+ __ZN5CMMsl4swapERNS_11ButtonPressES1_
+ __ZNK5CMMsl11ButtonPress10formatTextERN2PB13TextFormatterEPKc
+ __ZNK5CMMsl11ButtonPress10hash_valueEv
+ __ZNK5CMMsl11ButtonPress7writeToERN2PB6WriterE
+ __ZNK5CMMsl11ButtonPresseqERKS0_
+ __ZTIN5CMMsl11ButtonPressE
+ __ZTSN5CMMsl11ButtonPressE
+ __ZTVN5CMMsl11ButtonPressE
CStrings:
+ "accelBias0"
+ "accelBias1"
+ "buttonPress"
+ "deltaPositionAltimeterZ"
+ "down"
+ "usage"
+ "usagePage"
+ "yOffset"
```
