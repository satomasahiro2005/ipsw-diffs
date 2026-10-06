## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70778` | `0x71424` | **`+0xcac`** |
| `__AUTH_CONST.__objc_const` | `0xd1f8` | `0xd2b8` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x6804` | `0x6894` | **`+0x90`** |
| `__TEXT.__cstring` | `0x76ff` | `0x7763` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x5520` | `0x5580` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x3847` | `0x388a` | **`+0x43`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f70` | `0x1fb0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1a70` | `0x1aa0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x8a4` | `0x8b4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xdc8` | `0xdd0` | **`+0x8`** |

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 2928
-  Symbols:   4812
-  CStrings:  1300
+  Functions: 2948
+  Symbols:   4834
+  CStrings:  1305
Symbols:
+ -[UARPComponentConfiguration productGroup]
+ -[UARPComponentConfiguration productNumber]
+ -[UARPComponentConfiguration setProductGroup:]
+ -[UARPComponentConfiguration setProductNumber:]
+ -[UARPEndpointConfiguration productGroup]
+ -[UARPEndpointConfiguration productNumber]
+ -[UARPEndpointConfiguration setProductGroup:]
+ -[UARPEndpointConfiguration setProductNumber:]
+ -[UARPEndpointLayer3 clearMatchingLayer2Context:]
+ -[UARPEndpointLayer3 configureEndpointLayer2Tags]
+ -[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackRequestAssetBuffer:]
+ -[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackReturnAssetBuffer:]
+ _OBJC_IVAR_$_UARPComponentConfiguration._productGroup
+ _OBJC_IVAR_$_UARPComponentConfiguration._productNumber
+ _OBJC_IVAR_$_UARPEndpointConfiguration._productGroup
+ _OBJC_IVAR_$_UARPEndpointConfiguration._productNumber
+ _UARPEndpointLayer3RequestAssetBuffer
+ _UARPEndpointLayer3ReturnAssetBuffer
+ _UARPLayer2RequestAssetBuffer
+ _UARPLayer2ReturnAssetBuffer
+ _dispatch_assert_queue$V2
+ _kUARPLayer3StringMetricsSubfolder
CStrings:
+ "%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@"
+ "%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@"
+ "%s: uncompressedLength (%u) exceeds decompressionBuffer size (%lu)"
+ "-[UARPEndpointLayer3 configureEndpointLayer2Tags]"
+ "Product Group"
+ "Product Number"
+ "metrics"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa31"
- "%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@"
- "%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@-%@"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x831"
```
