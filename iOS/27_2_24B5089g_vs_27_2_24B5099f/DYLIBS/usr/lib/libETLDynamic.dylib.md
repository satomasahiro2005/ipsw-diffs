## libETLDynamic.dylib

> `/usr/lib/libETLDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47858` | `0x4749c` | **`-0x3bc`** |
| `__TEXT.__cstring` | `0x5374` | `0x5069` | **`-0x30b`** |
| `__TEXT.__gcc_except_tab` | `0x2dc` | `0x2a8` | **`-0x34`** |
| `__AUTH_CONST.__auth_got` | `0x288` | `0x258` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x7d8` | **`-0x20`** |
| `__DATA.__bss` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 716
-  Symbols:   892
-  CStrings:  640
+  Functions: 715
+  Symbols:   881
+  CStrings:  613
Symbols:
- GCC_except_table10
- _TelephonyUtilGetSystemTime
- __ZL17_ETLDebugOpenFilev
- __ZL17gETLDebugStdoutFD
- __ZN3ctu2fs16create_directoryENS_4llvm9StringRefEtb
- __ZN3ctu6assignERNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEEPKhjbb
- ___FUNCTION__.ETLEVENTProcessHeader
- ___stdoutp
- _fflush
- _fopen
- _vfprintf
Functions:
~ _ETLGSDIParseGetFeatureResponse : 288 -> 260
~ _ETLGSDIParseGetECCResponse : 192 -> 168
~ _ETLGSDIPerformGetECC : 824 -> 796
~ __ZL20_ETLDebugPrintStdoutPKcS0_Pc : 188 -> 4
~ __ZL26_ETLDebugPrintBinaryStdoutPKc23ETLDebugPrintBinaryTypePKvj : 300 -> 4
- __ZL17_ETLDebugOpenFilev
~ _ETLMaverickParseSetGPIOResponse : 404 -> 348
~ _ETLEVENTProcessEvent : 464 -> 696
~ _ETLEVENTProcessEventItem : 8 -> 296
~ _ETLEVENTProcessEventItemTSLength : 500 -> 304
~ _ETLEVENTProcessHeader : 152 -> 60
~ _ETLEVENTParseReport : 328 -> 208
~ _ETLEVENTParseEventReport : 376 -> 464
~ _ETLEVENTReportFree : 164 -> 132
~ _ETLEFS2ParseStatResponse : 416 -> 384
~ _ETLLOGParseLogHeader : 148 -> 88
~ _ETLLOGParseLog : 476 -> 440
CStrings:
- "%u.%03u %s:"
- "%u.%03u [%s] %s\n%s"
- "/private/var/wireless/Library/Logs/CrashReporter/Baseband/"
- "Buffer Length %u for payload not enough for, need %zu\n"
- "Buffer Length %u not enough, need %zu for full timestamp\n"
- "Buffer Length %u not enough, need %zu for truncated timestamp\n"
- "EFS File Mode: %u\n"
- "ETLEVENTParseReport"
- "ETLEVENTProcessEventItemTSLength"
- "ETLEVENTProcessHeader"
- "ETLEVENTReportFree"
- "ETLLOGParseLogHeader"
- "Failed to process header\n"
- "Freed %u, count was %u\n"
- "GPIO State: %u, GPIO, Number of GPIOs: %u\n"
- "Length %u\n"
- "Length %u is greater than buffer size %u\n"
- "Reading Event %u, length flag %u, timeLength %u, bufferLength %u\n"
- "Received %u bytes\n"
- "Received %u records\n"
- "Warning: Buffer Length %u is greater than field length %u\n"
- "Warning: Failed to open %s for writing\n"
- "libETL.log"
- "misc"
- "recv"
- "send"
- "w"
```
