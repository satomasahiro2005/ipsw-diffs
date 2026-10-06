## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63d50` | `0x63edc` | **`+0x18c`** |
| `__AUTH.__objc_data` | `0x1720` | `0x1810` | **`+0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0xe10` | `0xd20` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0xc927` | `0xc989` | **`+0x62`** |
| `__TEXT.__cstring` | `0xecfe` | `0xed51` | **`+0x53`** |
| `__DATA_CONST.__got` | `0x10d8` | `0x1108` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4640` | `0x4660` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2000` | `0x2008` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1898` | `0x18a0` | **`+0x8`** |

### Other Changes

```diff

-360.63.1.11.2
+360.66.1.11.1

-  Symbols:   4647
-  CStrings:  1706
+  Symbols:   4649
+  CStrings:  1709
Symbols:
+ _OBJC_CLASS_$_NSKeyedUnarchiver
+ _OBJC_CLASS_$_UTTypeCodingBox
Functions:
~ -[AVFigRouteDescriptorOutputDeviceImpl protocolTypeIdentifier] : 80 -> 476
CStrings:
+ "-[AVFigRouteDescriptorOutputDeviceImpl protocolTypeIdentifier]"
+ "<<<< AVOutputDevice (FigRouteDescriptor) >>>> %s: Failed to unarchive UTTypeCodingBox: %{public}@"
+ "ProtocolTypeArchive"
```
