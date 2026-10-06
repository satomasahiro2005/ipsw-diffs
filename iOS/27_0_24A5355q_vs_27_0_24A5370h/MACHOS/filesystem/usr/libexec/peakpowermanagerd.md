## peakpowermanagerd

> `/usr/libexec/peakpowermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10914` | `0x10294` | **`-0x680`** |
| `__TEXT.__objc_stubs` | `0x2240` | `0x2160` | **`-0xe0`** |
| `__TEXT.__objc_methname` | `0x2ac9` | `0x2a6a` | **`-0x5f`** |
| `__TEXT.__cstring` | `0x8a2` | `0x84a` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0xa83` | `0xa34` | **`-0x4f`** |
| `__DATA_CONST.__cfstring` | `0xaa0` | `0xa60` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x2e7` | `0x315` | **`+0x2e`** |
| `__DATA.__objc_selrefs` | `0xbf8` | `0xbd0` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2c8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0xa8` | `0x98` | **`-0x10`** |
| `__TEXT.__const` | `0x58` | `0x48` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9c` | `0x90` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1177.0.0.502.4
+1191.0.4.502.1

-  Functions: 458
-  Symbols:   140
-  CStrings:  669
+  Functions: 443
+  Symbols:   138
+  CStrings:  659
Symbols:
+ _CFRetain
+ _CFStringCreateWithFormat
+ _objc_retain_x26
- _OBJC_CLASS_$_NSDate
- _OBJC_CLASS_$_NSDateFormatter
- _dispatch_get_global_queue
- _objc_retain_x23
- _sleep
CStrings:
+ "%s <Error> hash verify failed for chemID 0x%x"
+ "%s <Error> sentHash %x for chemID 0x%x mismatches %d PPMVector dict(s); last returnedHash %x"
+ "-[BatteryModelDataHandler verifyHashData:forChemID:]"
+ "AppleSmartBatteryBank"
+ "B28@0:8*16I24"
+ "B28@0:8r^^{__CFDictionary}16i24"
+ "PPMVector%d"
+ "getPPMDebugDict:forBatteryIndex:"
+ "verifyHashData:forChemID:"
- "%s <Error> RCParamsHash nil"
- "%s <Error> battModelDict nil"
- "%s <Error> getPPMDebugDict failed"
- "%s <Error> hash verify failed"
- "%s <Error> sentHash %x mismatches with returnedHash %x"
- "-[BatteryModelDataHandler getIntValueForKeyFromBatteryData:]"
- "-[BatteryModelDataHandler verifyHashData:]"
- "AppleSmartBatteryPack"
- "Battery data upload run for chemId 0x%lx\n"
- "CaptureTimestamp"
- "dateWithTimeIntervalSince1970:"
- "getBatteryChemID"
- "getIntValueForKeyFromBatteryData:"
- "savedChemID"
- "setDateFormat:"
- "setInteger:forKey:"
- "stringFromDate:"
- "unsignedLongLongValue"
- "yyyy-MM-dd HH:mm:ss"
```
