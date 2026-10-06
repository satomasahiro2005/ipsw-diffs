## com.apple.iokit.IOReportFamily

> `com.apple.iokit.IOReportFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3030` | `0x3048` | **`+0x18`** |
| `__TEXT.__cstring` | `0x238` | `0x237` | **`-0x1`** |

### Other Changes

```diff

-115.0.0.0.0
+115.0.0.0.1
Functions:
~ sub_fffffff00a3558e8 -> sub_fffffff00a2dbac8 : 120 -> 128
~ sub_fffffff00a355960 -> sub_fffffff00a2dbb48 : 116 -> 128
~ __ZN11IOReportHub17getSnapshotDeltasEyP12OSDictionaryP24IOBufferMemoryDescriptor : 1332 -> 1336
CStrings:
+ "1211111212221212111"
- "12111112122212121111"
```
