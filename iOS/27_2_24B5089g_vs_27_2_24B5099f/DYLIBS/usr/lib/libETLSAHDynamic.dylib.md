## libETLSAHDynamic.dylib

> `/usr/lib/libETLSAHDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2514` | `0x2258` | **`-0x2bc`** |
| `__TEXT.__cstring` | `0x95d` | `0x7fe` | **`-0x15f`** |

### Other Changes

```diff

-  Symbols:   55
-  CStrings:  75
+  Symbols:   54
+  CStrings:  67
Symbols:
- __ETLDebugPrintBinaryVerbose
Functions:
~ _ETLSAHCommandSend : 200 -> 112
~ _ETLSAHSendReadData : 160 -> 120
~ _ETLSAHCommandReceive : 400 -> 308
~ _ETLSAHCommandExecute : 832 -> 724
~ _ETLSAHCommandCreateHelloResponseExt : 176 -> 108
~ _ETLSAHGetDebugRecordCount : 476 -> 420
~ _ETLSAHGetDebugRecordCount64Bit : 472 -> 416
~ _ETLSAHGetRecordEx : 656 -> 560
~ _ETLSAHGetRecordEx64Bit : 668 -> 572
CStrings:
- "Command buffer has invalid length %u, which is less than the size of the command header (%zu)\n"
- "Couldn't allocate memory for memory read buffer\n"
- "ETLSAHCommandCreateHelloResponseExt"
- "ETLSAHCommandSend"
- "ETLSAHSendReadData"
- "Error: Given Reserved Length cannot be more than %lu bytes\n"
- "Got Command of type %u, length %u\n"
- "Sending command of length %u, type %u\n"
```
