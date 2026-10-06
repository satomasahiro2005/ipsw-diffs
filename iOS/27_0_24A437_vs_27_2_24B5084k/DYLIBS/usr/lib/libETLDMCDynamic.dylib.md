## libETLDMCDynamic.dylib

> `/usr/lib/libETLDMCDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1185` | `0x138c` | **`+0x207`** |
| `__TEXT.__text` | `0x1e188` | `0x1e140` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0x328` | `0x330` | **`+0x8`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  CStrings:  186
+  CStrings:  200
Functions:
~ _ETLLOGParseLogHeader : 88 -> 148
~ _ETLLOGParseLog : 440 -> 476
~ _ETLEVENTProcessEvent : 696 -> 464
~ _ETLEVENTProcessEventItem : 296 -> 8
~ _ETLEVENTProcessEventItemTSLength : 304 -> 500
~ _ETLEVENTProcessHeader : 60 -> 152
~ _ETLEVENTParseReport : 208 -> 328
~ _ETLEVENTParseEventReport : 464 -> 376
~ _ETLEVENTReportFree : 132 -> 164
CStrings:
+ "Buffer Length %u for payload not enough for, need %zu\n"
+ "Buffer Length %u not enough, need %zu for full timestamp\n"
+ "Buffer Length %u not enough, need %zu for truncated timestamp\n"
+ "ETLEVENTParseReport"
+ "ETLEVENTProcessEventItemTSLength"
+ "ETLEVENTProcessHeader"
+ "ETLEVENTReportFree"
+ "ETLLOGParseLogHeader"
+ "Failed to process header\n"
+ "Freed %u, count was %u\n"
+ "Length %u\n"
+ "Length %u is greater than buffer size %u\n"
+ "Reading Event %u, length flag %u, timeLength %u, bufferLength %u\n"
+ "Warning: Buffer Length %u is greater than field length %u\n"
```
