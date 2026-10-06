## libETLSAHDynamic.dylib

> `/usr/lib/libETLSAHDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2258` | `0x2514` | **`+0x2bc`** |
| `__TEXT.__cstring` | `0x7fe` | `0x95d` | **`+0x15f`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Symbols:   54
-  CStrings:  67
+  Symbols:   55
+  CStrings:  75
Symbols:
+ __ETLDebugPrintBinaryVerbose
Functions:
~ _ETLSAHCommandSend : 112 -> 200
~ _ETLSAHSendReadData : 120 -> 160
~ _ETLSAHCommandReceive : 308 -> 400
~ _ETLSAHCommandExecute : 724 -> 832
~ _ETLSAHCommandCreateHelloResponseExt : 108 -> 176
~ _ETLSAHGetDebugRecordCount : 420 -> 476
~ _ETLSAHGetDebugRecordCount64Bit : 416 -> 472
~ _ETLSAHGetRecordEx : 560 -> 656
~ _ETLSAHGetRecordEx64Bit : 572 -> 668
CStrings:
+ "Command buffer has invalid length %u, which is less than the size of the command header (%zu)\n"
+ "Couldn't allocate memory for memory read buffer\n"
+ "ETLSAHCommandCreateHelloResponseExt"
+ "ETLSAHCommandSend"
+ "ETLSAHSendReadData"
+ "Error: Given Reserved Length cannot be more than %lu bytes\n"
+ "Got Command of type %u, length %u\n"
+ "Sending command of length %u, type %u\n"
```
