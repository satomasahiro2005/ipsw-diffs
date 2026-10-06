## peakpowermanagerd

> `/usr/libexec/peakpowermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10294` | `0x1081c` | **`+0x588`** |
| `__TEXT.__objc_stubs` | `0x2160` | `0x2280` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x2a6a` | `0x2b40` | **`+0xd6`** |
| `__TEXT.__oslogstring` | `0xa34` | `0xabf` | **`+0x8b`** |
| `__TEXT.__cstring` | `0x84a` | `0x8cd` | **`+0x83`** |
| `__TEXT.__auth_stubs` | `0x6c0` | `0x730` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0xa60` | `0xac0` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0xbd0` | `0xc20` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x370` | `0x3a8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x10d4` | `0x10f4` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x315` | `0x332` | **`+0x1d`** |
| `__TEXT.__const` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1191.0.4.502.1
+1191.0.16.0.0

-  Functions: 443
-  Symbols:   138
-  CStrings:  659
+  Functions: 447
+  Symbols:   146
+  CStrings:  679
Symbols:
+ _CFDataGetTypeID
+ _CFNumberGetTypeID
+ _IORegistryEntryFromPath
+ _IOServiceNameMatching
+ _OBJC_CLASS_$_NSArray
+ _objc_retain_x20
+ _objc_retain_x22
+ _objc_retain_x25
CStrings:
+ "%@/%x.rcmodel"
+ "%s <Error> AppleSmartBatteryPack service null"
+ "%s <Error> BankCount property null"
+ "%s <Error> baseURL nil, error is %@"
+ "%s <Info> resolved battery model via casing fallback: %@ (target type \"%@\")"
+ "-[BatteryModelDataHandler getNumberOfBatteryBanks]"
+ "@36@0:8@16I24@28"
+ "AppleSmartBatteryPack"
+ "B24@0:8^I16"
+ "BankCount"
+ "Failed to read hw.targettype"
+ "IODeviceTree:/arm-io/ppm"
+ "Incorrect Number of Battery Banks of 0\n"
+ "Number of Chem IDs %lu does not match number of battery packs %d banks %d \n"
+ "PPM/BatteryModels"
+ "UTF8String"
+ "arrayWithObjects:count:"
+ "cpms-use-lpem-data"
+ "getNumberOfBatteryBanks"
+ "getPPMDebugDict:forbatteryPackIndex:"
+ "lowercaseString"
+ "path"
+ "ppm"
+ "readCPMSUseLPEMData:"
+ "resolveModelURLForDeviceType:chemID:inParentDirectory:"
+ "stringByAppendingString:"
+ "substringFromIndex:"
+ "substringToIndex:"
+ "uppercaseString"
- "%s <Error> workingDirURL nil"
- "%s workingDirURL resource: %@ \n"
- "Failed to malloc."
- "Failed to read size (%d)."
- "Failed to read value (%d)."
- "Number of Chem IDs %lu does not match number of battery packs %d \n"
- "PPM/BatteryModels/%@/%x.rcmodel"
- "fileSystemRepresentation"
- "getPPMDebugDict:forBatteryIndex:"
```
