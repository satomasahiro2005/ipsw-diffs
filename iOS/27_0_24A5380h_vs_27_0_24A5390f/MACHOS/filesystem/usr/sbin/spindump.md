## spindump

> `/usr/sbin/spindump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8e10` | `0xb9eb4` | **`+0x10a4`** |
| `__TEXT.__gcc_except_tab` | `0x3094` | `0x3244` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x26ded` | `0x26f23` | **`+0x136`** |
| `__TEXT.__cstring` | `0x1532b` | `0x15450` | **`+0x125`** |
| `__DATA_CONST.__cfstring` | `0x9d60` | `0x9e20` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x1370` | `0x13d0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1540` | `0x1590` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x4265` | `0x42b1` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0x41a0` | `0x41e0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xcd0` | `0xd08` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x9c8` | `0x9f8` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1d68` | `0x1d88` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x11c0` | `0x11d0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9f4` | `0xa04` | **`+0x10`** |
| `__DATA.__bss` | `0x818` | `0x820` | **`+0x8`** |
| `__TEXT.__const` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x214` | `0x218` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-443.0.0.0.0
+445.0.0.0.0

-  Functions: 1818
-  Symbols:   389
-  CStrings:  3878
+  Functions: 1833
+  Symbols:   395
+  CStrings:  3891
Symbols:
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
+ _objc_terminate
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
CStrings:
+ " exclave %-*s"
+ "%-*s"
+ "%@%lu"
+ "%@:%@"
+ "Heaviest stack"
+ "Parsing spindump text: Unable to filter heaviest callstack to specific index range, it remains unfiltered"
+ "SaveReportSerialized"
+ "Unable to format: Parsing spindump text: Unable to filter heaviest callstack to specific index range, it remains unfiltered"
+ "Unable to format: Waited %.1f to get report lock"
+ "Waited %.1f to get report lock"
+ "^(?<indentWhitespace> +(?<kernelDot>\\*)?)(?<countAndWhitespace>(?<count>\\d+)\\s+)(?:\\?\\?\\?(?:\\s+\\+\\s+(?<offsetIntoUnknownSymbol>\\d+))?|(?<symbolName>.*?)\\s+\\+\\s+(?<offsetIntoSymbol>\\d+))(?:\\s+\\((?:(?:(?<sourceFilepath>.+?)(?::(?<sourceLineNumber>\\d+)(?:[:\\.,](?<sourceColumnNumber>\\d+))?)?\\s+in\\s+)?(?:<(?<binaryUuid>[\\dabcdef\\-]{32,36})>|(?<binaryName>.+?))\\s+\\+\\s+(?<offsetIntoBinary>\\d+))?(?:\\s*(?<exclaveInfo>exclave\\s+.+?))?\\))?(?:\\s+\\[(?<address>(?:0x)?[\\dabcdef]+)\\])?(?:\\s+\\((?<stateInfo>.+?)\\))?(?:\\s+(?<startIndex>\\d+)(?:\\s*-\\s*(?<endIndex>\\d+))?)?$"
+ "^\\s*(?<kernelDot>\\*)?(?:(?<startAddress>(?:0x)?[\\dabcdef]+)|\\?\\?\\?)\\s*\\-\\s*(?:(?<endAddress>(?:0x)?[\\dabcdef]+)|\\?\\?\\?)\\s*(?:\\?\\?\\?|(?<bundleIdentifier>\\S+\\.\\S+\\.\\S+)|(?<name>.+?\\b))\\s+(?<version>(?:.*?)?(?:\\s*\\(.*?\\)))?\\s*(?:exclave\\s+(?<exclaveName>.+?)\\s+)?\\s*<(?<binaryUuid>[\\dabcdef\\-]{32,36})>(?<segmentName>\\S+?)?(?:\\s+(?<binaryPath>.+?)?)?$"
+ "_exclaveName"
+ "_serializeReportToStream:withSampleStore:"
+ "exclaveInfo"
+ "exclaveName"
+ "unsignedIntegerValue"
- "%@-%@"
- "SaveReport"
- "^(?<indentWhitespace> +(?<kernelDot>\\*)?)(?<countAndWhitespace>(?<count>\\d+)\\s+)(?:\\?\\?\\?(?:\\s+\\+\\s+(?<offsetIntoUnknownSymbol>\\d+))?|(?<symbolName>.*?)\\s+\\+\\s+(?<offsetIntoSymbol>\\d+))(?:\\s+\\((?:(?<sourceFilepath>.+?)(?::(?<sourceLineNumber>\\d+)(?:[:\\.,](?<sourceColumnNumber>\\d+))?)?\\s+in\\s+)?(?:<(?<binaryUuid>[\\dabcdef\\-]{32,36})>|(?<binaryName>.+?))\\s+\\+\\s+(?<offsetIntoBinary>\\d+)\\))?(?:\\s+\\[(?<address>(?:0x)?[\\dabcdef]+)\\])?(?:\\s+\\((?<stateInfo>.+?)\\))?(?:\\s+(?<startIndex>\\d+)(?:\\s*-\\s*(?<endIndex>\\d+))?)?$"
- "^\\s*(?<kernelDot>\\*)?(?:(?<startAddress>(?:0x)?[\\dabcdef]+)|\\?\\?\\?)\\s*\\-\\s*(?:(?<endAddress>(?:0x)?[\\dabcdef]+)|\\?\\?\\?)\\s*(?:\\?\\?\\?|(?<bundleIdentifier>\\S+\\.\\S+\\.\\S+)|(?<name>.+?\\b))\\s+(?<version>(?:.*?)?(?:\\s*\\(.*?\\)))?\\s*<(?<binaryUuid>[\\dabcdef\\-]{32,36})>(?<segmentName>\\S+?)?(?:\\s+(?<binaryPath>.+?)?)?$"
```
