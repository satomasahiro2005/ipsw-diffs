## NFC

> `/System/Library/CoreAccessories/PlugIns/Transports/NFC.transport/NFC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9490` | `0x9540` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1000` | `0x1040` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x910` | `0x8e0` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x478` | `0x490` | **`+0x18`** |
| `__TEXT.__cstring` | `0xd8e` | `0xd9f` | **`+0x11`** |
| `__TEXT.__gcc_except_tab` | `0xf8` | `0xfc` | **`+0x4`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Functions: 150
-  Symbols:   644
-  CStrings:  270
+  Functions: 148
+  Symbols:   645
+  CStrings:  271
Symbols:
+ GCC_except_table26
+ GCC_except_table36
+ GCC_except_table50
+ _ACCUserDefaultsKey_EnableManager2ForTransport
+ _ACCUserDefaultsKey_OverrideMPPAuthSupported
+ _kCFACCUserDefaultsKey_EnableManager2ForTransport
+ _kCFACCUserDefaultsKey_OverrideMPPAuthSupported
- GCC_except_table28
- GCC_except_table38
- GCC_except_table52
- ___74-[AccessoryTransportPluginNFC _handleNearFieldAccessoryEventNotification:]_block_invoke_2
- ___block_descriptor_48_e8_32s40s_e34_v32?0"NSString"8"NFACTag"16^B24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e35_v32?0"NSString"8"NSString"16^B24ls32l8s40l8
CStrings:
+ "EnableManager2ForTransport"
+ "OverrideMPPAuthSupported"
- "v32@?0@\"NSString\"8@\"NFACTag\"16^B24"
```
