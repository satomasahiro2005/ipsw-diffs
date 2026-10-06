## GNSSPassthroughLib

> `/System/Library/Extensions/AppleSPU.kext/PlugIns/GNSSPassthroughLib.plugin/GNSSPassthroughLib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x192c` | `0x1bdc` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0xc1` | `0x2a8` | **`+0x1e7`** |
| `__TEXT.__unwind_info` | `0x168` | `0x180` | **`+0x18`** |

### Other Changes

```diff

-1084.0.0.0.0
+1087.0.0.0.0

-  Functions: 62
+  Functions: 66

-  CStrings:  19
+  CStrings:  27
CStrings:
+ "GNSSPassthrough::RegisterDataHandler result %d"
+ "GNSSPassthrough::RegisterEventHandler result %d"
+ "GNSSPassthrough::SetDispatchQueue kIOReturnBadArgument"
+ "GNSSPassthrough::SetDispatchQueue kIOReturnStillOpen"
+ "GNSSPassthrough::_registerDataQueueHandler _dataQueueAddr already set"
+ "GNSSPassthrough::_registerDataQueueHandler _dataQueuePort already set"
+ "GNSSPassthrough::_registerEventQueueHandler _eventQueueAddr already set"
+ "GNSSPassthrough::_registerEventQueueHandler _eventQueuePort already set"
```
