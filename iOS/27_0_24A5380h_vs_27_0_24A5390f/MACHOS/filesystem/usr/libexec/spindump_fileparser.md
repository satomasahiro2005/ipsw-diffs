## spindump_fileparser

> `/usr/libexec/spindump_fileparser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc20c8` | `0xc312c` | **`+0x1064`** |
| `__TEXT.__gcc_except_tab` | `0x31b4` | `0x3364` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x28949` | `0x28a7f` | **`+0x136`** |
| `__TEXT.__cstring` | `0x15ed3` | `0x15ff8` | **`+0x125`** |
| `__DATA_CONST.__cfstring` | `0xa380` | `0xa440` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x13b0` | `0x1410` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1590` | `0x15e0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x437e` | `0x43ca` | **`+0x4c`** |
| `__TEXT.__objc_stubs` | `0x4440` | `0x4480` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xce8` | `0xd20` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x9e8` | `0xa18` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1d68` | `0x1d88` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1228` | `0x1238` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x9f4` | `0xa04` | **`+0x10`** |
| `__DATA.__bss` | `0x818` | `0x820` | **`+0x8`** |
| `__TEXT.__const` | `0x280` | `0x288` | **`+0x8`** |
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

-  Functions: 1831
-  Symbols:   394
-  CStrings:  3981
+  Functions: 1845
+  Symbols:   400
+  CStrings:  3994
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
